# Inserting Images into README


## Default

![image](visuals/Overview.png)


## Side-by-Side with Text (Using Tables)

<table>
<tr>
<td><img src="visuals/Overview.png" width="50%"></td>
<td>Your descriptive text goes here.</td>
</tr>
</table>

---

<table style="width:100%">
<tr>
<td style="width:50%"><img src="visuals/Overview.png" width="100%"></td>
<td style="width:50%">Your descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes here.</td>
</tr>
</table>


## Side-by-Side Images (Gallery Style)

| ![Overview](visuals/Overview.png)     | ![Conclusion](visuals/Conclusion.png) |
|:-------------------------------------:|:-------------------------------------:|
| Caption 1                             | Your descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes hereYour descriptive text goes here                        |


<p style="clear: both;"></p>

## Center Aligned Images

<p align="center">
  <img src="visuals/Overview.png" width="500">
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
| Centered hero image                   | [<p align="center">...</p>]            |
| Text wrap (if needed)                 | Table layout (more reliable than float)|
