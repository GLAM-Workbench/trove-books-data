# trove-books-data

*A GLAM Workbench data repository*

CURRENT VERSION: v1.0

These datasets were generated using notebooks in the [trove-books](https://github.com/GLAM-Workbench/trove-books/) repository.

For more information and documentation see the [Trove books](https://glam-workbench.net/trove-books) section of the [GLAM Workbench](https://glam-workbench.net).

## Dataset summary
- [trove-books.csv](https://github.com/GLAM-Workbench/trove-books-data/blob/main/trove-books.csv) (20.3 MB, text/csv)


## Dataset details

### [trove-books.csv](https://github.com/GLAM-Workbench/trove-books-data/blob/main/trove-books.csv)


<table id="T_bd33e">
  <thead>
  </thead>
  <tbody>
    <tr>
      <th id="T_bd33e_level0_row0" class="row_heading level0 row0" >date harvested</th>
      <td id="T_bd33e_row0_col0" class="data row0 col0" >2024-02-14</td>
    </tr>
    <tr>
      <th id="T_bd33e_level0_row1" class="row_heading level0 row1" >file size</th>
      <td id="T_bd33e_row1_col0" class="data row1 col0" >20.3 MB</td>
    </tr>
    <tr>
      <th id="T_bd33e_level0_row2" class="row_heading level0 row2" >format</th>
      <td id="T_bd33e_row2_col0" class="data row2 col0" >text/csv</td>
    </tr>
    <tr>
      <th id="T_bd33e_level0_row3" class="row_heading level0 row3" >created by</th>
      <td id="T_bd33e_row3_col0" class="data row3 col0" ><a href='https://github.com/GLAM-Workbench/trove-books/blob/master/Harvesting-digitised-books.ipynb'>Harvesting the text of digitised books (and ephemera)</a></td>
    </tr>
    <tr>
      <th id="T_bd33e_level0_row4" class="row_heading level0 row4" >number of rows</th>
      <td id="T_bd33e_row4_col0" class="data row4 col0" >21,218</td>
    </tr>
  </tbody>
</table>


### Examples of use

- [Explore using Datasette](https://glam-workbench.net/datasette-lite/?csv=https://github.com/GLAM-Workbench/trove-books-data/blob/main/trove-books.csv&fts=title,sub_title,is_part_of&drop=work_type,fulltext_url_text,parent,parent_url,children,text_file)
- [Visualised in the *Trove Data Guide*](https://tdg.glam-workbench.net/other-digitised-resources/books/overview.html)
### Columns

| name                | type    | description                                                                                                        |
|:--------------------|:--------|:-------------------------------------------------------------------------------------------------------------------|
| `title`             | string  | title of the work                                                                                                  |
| `sub_title`         | string  | additional title or publication information, eg: 'Volume 1'                                                        |
| `contributor`       | string  | contributors including authors, editors, translators; multiple values separated by | symbol                        |
| `publisher`         | string  | multiple values separated by | symbol                                                                              |
| `date`              | string  | publication date; multiple values separated by | symbol                                                            |
| `type`              | string  | eg: 'text'; multiple values separated by | symbol                                                                  |
| `format`            | string  | eg: 'Book', 'volume'; multiple values separated by | symbol                                                        |
| `extent`            | string  | size or physical dimensions, can include number of pages or number of words; multiple values separated by | symbol |
| `language`          | string  | publication language; multiple values separated by | symbol                                                        |
| `subject`           | string  | associated subject headings; multiple values separated by | symbol                                                 |
| `spatial`           | string  | associated places (mostly using Library of Congress geographic area codes); multiple values separated by | symbol  |
| `is_part_of`        | string  | collections or series this publication is part of; multiple values separated by | symbol                           |
| `identifier`        | string  | library identifiers; multiple values separated by | symbol                                                         |
| `rights`            | string  | copyright and licensing information; multiple values separated by | symbol                                         |
| `pages`             | integer | number of digitised pages                                                                                          |
| `fulltext_url`      | string  | link to digitised book viewer                                                                                      |
| `fulltext_url_text` | string  | text of link to digitised book viewer                                                                              |
| `text_download_url` | string  | link to download OCRd text of book                                                                                 |
| `catalogue_url`     | string  | ; multiple values separated by | symbol                                                                            |
| `work_url`          | string  | link to work record in Trove; multiple values separated by | symbol                                                |
| `work_type`         | string  | Trove work format, eg: 'Book'; multiple values separated by | symbol                                               |
| `parent`            | string  | parent work identifiers; multiple values separated by | symbol                                                     |
| `parent_url`        | string  | parent work links; multiple values separated by | symbol                                                           |
| `children`          | any     | child work identifiers; multiple values separated by | symbol                                                      |
| `text_file`         | string  | file name of downloaded text                                                                                       |

----
Created by [Tim Sherratt](https://timsherratt.au) for the [GLAM Workbench](https://glam-workbench.net)