<h2 align="center" style="font-size: 2.5em; font-weight: bold;">
  Slide2PPT: Reconstructing Editable PowerPoint Slides with Large Models
</h2>

<p align="center">
  <a href="https://github.com/Slide2PPT/Slide2PPT.github.io" style="margin: 0 10px;">🌐 Homepage</a>
  <span style="margin: 0 10px;">🎞️ Dataset (Coming Soon)</span> |
  <span style="margin: 0 10px;">📖 Paper (Coming Soon)</span>
</p>

---

Slide2PPT leverages large models to reconstruct PowerPoint slides from reference images and generate editable PowerPoint files.

## Reconstruction showcase

Each row follows one slide through the complete pipeline. The center animation cycles through the three generation renders and the final iterative-refinement render; the right column shows the same slide with its editable PowerPoint objects selected.

<table>
  <thead>
    <tr>
      <th align="center">Reference image</th>
      <th align="center">Generation + iterative refinement</th>
      <th align="center">Editable PowerPoint result</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><a href="assets/image_dataset/1_01.png"><img src="assets/image_dataset/1_01.png" alt="Reference slide 1_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/1_01.gif"><img src="assets/readme/process/1_01.gif" alt="Reconstruction process for slide 1_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/1_01/1_01.png"><img src="assets/gpt5.6_sol/1_01/1_01.png" alt="Editable result for slide 1_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/1_02.png"><img src="assets/image_dataset/1_02.png" alt="Reference slide 1_02" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/1_02.gif"><img src="assets/readme/process/1_02.gif" alt="Reconstruction process for slide 1_02" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/1_02/1_02.png"><img src="assets/gpt5.6_sol/1_02/1_02.png" alt="Editable result for slide 1_02" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/1_03.png"><img src="assets/image_dataset/1_03.png" alt="Reference slide 1_03" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/1_03.gif"><img src="assets/readme/process/1_03.gif" alt="Reconstruction process for slide 1_03" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/1_03/1_03.png"><img src="assets/gpt5.6_sol/1_03/1_03.png" alt="Editable result for slide 1_03" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/3_01.png"><img src="assets/image_dataset/3_01.png" alt="Reference slide 3_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/3_01.gif"><img src="assets/readme/process/3_01.gif" alt="Reconstruction process for slide 3_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/3_01/3_01.png"><img src="assets/gpt5.6_sol/3_01/3_01.png" alt="Editable result for slide 3_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/4_01.png"><img src="assets/image_dataset/4_01.png" alt="Reference slide 4_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/4_01.gif"><img src="assets/readme/process/4_01.gif" alt="Reconstruction process for slide 4_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/4_01/4_01.png"><img src="assets/gpt5.6_sol/4_01/4_01.png" alt="Editable result for slide 4_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/5_01.png"><img src="assets/image_dataset/5_01.png" alt="Reference slide 5_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/5_01.gif"><img src="assets/readme/process/5_01.gif" alt="Reconstruction process for slide 5_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/5_01/5_01.png"><img src="assets/gpt5.6_sol/5_01/5_01.png" alt="Editable result for slide 5_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/7_01.png"><img src="assets/image_dataset/7_01.png" alt="Reference slide 7_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/7_01.gif"><img src="assets/readme/process/7_01.gif" alt="Reconstruction process for slide 7_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/7_01/7_01.png"><img src="assets/gpt5.6_sol/7_01/7_01.png" alt="Editable result for slide 7_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/41_01.png"><img src="assets/image_dataset/41_01.png" alt="Reference slide 41_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/41_01.gif"><img src="assets/readme/process/41_01.gif" alt="Reconstruction process for slide 41_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/41_01/41_01.png"><img src="assets/gpt5.6_sol/41_01/41_01.png" alt="Editable result for slide 41_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/49_01.png"><img src="assets/image_dataset/49_01.png" alt="Reference slide 49_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/49_01.gif"><img src="assets/readme/process/49_01.gif" alt="Reconstruction process for slide 49_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/49_01/49_01.png"><img src="assets/gpt5.6_sol/49_01/49_01.png" alt="Editable result for slide 49_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/51_01.png"><img src="assets/image_dataset/51_01.png" alt="Reference slide 51_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/51_01.gif"><img src="assets/readme/process/51_01.gif" alt="Reconstruction process for slide 51_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/51_01/51_01.png"><img src="assets/gpt5.6_sol/51_01/51_01.png" alt="Editable result for slide 51_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/52_01.png"><img src="assets/image_dataset/52_01.png" alt="Reference slide 52_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/52_01.gif"><img src="assets/readme/process/52_01.gif" alt="Reconstruction process for slide 52_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/52_01/52_01.png"><img src="assets/gpt5.6_sol/52_01/52_01.png" alt="Editable result for slide 52_01" width="300"></a></td>
    </tr>
    <tr>
      <td align="center"><a href="assets/image_dataset/65_01.png"><img src="assets/image_dataset/65_01.png" alt="Reference slide 65_01" width="300"></a></td>
      <td align="center"><a href="assets/readme/process/65_01.gif"><img src="assets/readme/process/65_01.gif" alt="Reconstruction process for slide 65_01" width="300"></a></td>
      <td align="center"><a href="assets/gpt5.6_sol/65_01/65_01.png"><img src="assets/gpt5.6_sol/65_01/65_01.png" alt="Editable result for slide 65_01" width="300"></a></td>
    </tr>
  </tbody>
</table>
