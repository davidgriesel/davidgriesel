# Inserting Images into README


## Default (Full Width Inline)

![image](visuals/Overview.png)


## Side-by-Side with Text (Using Tables) ✅ GitHub-compatible

<table>
<tr>
<td><img src="visuals/Overview.png" width="600"></td>
<td>Your descriptive text goes here.</td>
</tr>
</table>


## Side-by-Side Images (Gallery Style)

| ![Overview](visuals/Overview.png)     | ![Conclusion](visuals/Conclusion.png) |
|:-------------------------------------:|:-------------------------------------:|
| Caption 1                             | Caption 2                             |


## HTML Float (Limited GitHub support)

<div>
  <img src="visuals/Overview.png" align="left" width="300">
  <p>Your paragraph starts here and wraps around the image if allowed.</p>
</div>

<!-- Add a full-width spacer to break the layout -->

<p style="clear: both;"></p>

## Center Aligned Images

<p align="center">
  <img src="visuals/Overview.png" width="400">
</p>


## Link an Image

[![Overview](visuals/Overview.png)](https://public.tableau.com/views/MedicalStaffingPlan_17430147849920/Story1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)



## Summary of Best Practices:

| Use Case                              | Best Option                            |
|:-------------------------------------:|:--------------------------------------:|
| Simple inline image                   | ![Text](img.png) (Markdown)            |
| Image + caption or paragraph          | HTML table layout                      |
| Image gallery                         | Markdown table                         |
| Clickable image                       | '[![Text](img.png)](URL)               |
| Centered hero image                   | <p align="center">...</p>              |
| Text wrap (if needed)                 | Table layout (more reliable than float)|
