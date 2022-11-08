New York Jets Week 9
================
Jeffrey Gordon

    ── Attaching packages ─────────────────────────────────────── tidyverse 1.3.2 ──
    ✔ ggplot2 3.3.6      ✔ purrr   0.3.5 
    ✔ tibble  3.1.8      ✔ dplyr   1.0.10
    ✔ tidyr   1.2.1      ✔ stringr 1.4.1 
    ✔ readr   2.1.3      ✔ forcats 0.5.2 
    ── Conflicts ────────────────────────────────────────── tidyverse_conflicts() ──
    ✖ dplyr::filter() masks stats::filter()
    ✖ dplyr::lag()    masks stats::lag()

I am going to take a look at the progression of expected points added
over the course of the season for the New York Jets offense. I want to
break the season into two known chunks: quarterback at the time, and
main running back.

![](jets_epa_by_player_and_playtype_files/figure-gfm/unnamed-chunk-3-1.png)

<div id="tpwdeudbmw" style="overflow-x:auto;overflow-y:auto;width:auto;height:auto;">
<style>html {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Helvetica Neue', 'Fira Sans', 'Droid Sans', Arial, sans-serif;
}

#tpwdeudbmw .gt_table {
  display: table;
  border-collapse: collapse;
  margin-left: auto;
  margin-right: auto;
  color: #333333;
  font-size: 16px;
  font-weight: normal;
  font-style: normal;
  background-color: #FFFFFF;
  width: auto;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #A8A8A8;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #A8A8A8;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
}

#tpwdeudbmw .gt_heading {
  background-color: #FFFFFF;
  text-align: center;
  border-bottom-color: #FFFFFF;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#tpwdeudbmw .gt_title {
  color: #333333;
  font-size: 125%;
  font-weight: initial;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-color: #FFFFFF;
  border-bottom-width: 0;
}

#tpwdeudbmw .gt_subtitle {
  color: #333333;
  font-size: 85%;
  font-weight: initial;
  padding-top: 0;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-color: #FFFFFF;
  border-top-width: 0;
}

#tpwdeudbmw .gt_bottom_border {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#tpwdeudbmw .gt_col_headings {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
}

#tpwdeudbmw .gt_col_heading {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 6px;
  padding-left: 5px;
  padding-right: 5px;
  overflow-x: hidden;
}

#tpwdeudbmw .gt_column_spanner_outer {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: normal;
  text-transform: inherit;
  padding-top: 0;
  padding-bottom: 0;
  padding-left: 4px;
  padding-right: 4px;
}

#tpwdeudbmw .gt_column_spanner_outer:first-child {
  padding-left: 0;
}

#tpwdeudbmw .gt_column_spanner_outer:last-child {
  padding-right: 0;
}

#tpwdeudbmw .gt_column_spanner {
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: bottom;
  padding-top: 5px;
  padding-bottom: 5px;
  overflow-x: hidden;
  display: inline-block;
  width: 100%;
}

#tpwdeudbmw .gt_group_heading {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
}

#tpwdeudbmw .gt_empty_group_heading {
  padding: 0.5px;
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  vertical-align: middle;
}

#tpwdeudbmw .gt_from_md > :first-child {
  margin-top: 0;
}

#tpwdeudbmw .gt_from_md > :last-child {
  margin-bottom: 0;
}

#tpwdeudbmw .gt_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  margin: 10px;
  border-top-style: solid;
  border-top-width: 1px;
  border-top-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 1px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 1px;
  border-right-color: #D3D3D3;
  vertical-align: middle;
  overflow-x: hidden;
}

#tpwdeudbmw .gt_stub {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
}

#tpwdeudbmw .gt_stub_row_group {
  color: #333333;
  background-color: #FFFFFF;
  font-size: 100%;
  font-weight: initial;
  text-transform: inherit;
  border-right-style: solid;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
  padding-left: 5px;
  padding-right: 5px;
  vertical-align: top;
}

#tpwdeudbmw .gt_row_group_first td {
  border-top-width: 2px;
}

#tpwdeudbmw .gt_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#tpwdeudbmw .gt_first_summary_row {
  border-top-style: solid;
  border-top-color: #D3D3D3;
}

#tpwdeudbmw .gt_first_summary_row.thick {
  border-top-width: 2px;
}

#tpwdeudbmw .gt_last_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#tpwdeudbmw .gt_grand_summary_row {
  color: #333333;
  background-color: #FFFFFF;
  text-transform: inherit;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
}

#tpwdeudbmw .gt_first_grand_summary_row {
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 5px;
  padding-right: 5px;
  border-top-style: double;
  border-top-width: 6px;
  border-top-color: #D3D3D3;
}

#tpwdeudbmw .gt_striped {
  background-color: rgba(128, 128, 128, 0.05);
}

#tpwdeudbmw .gt_table_body {
  border-top-style: solid;
  border-top-width: 2px;
  border-top-color: #D3D3D3;
  border-bottom-style: solid;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
}

#tpwdeudbmw .gt_footnotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#tpwdeudbmw .gt_footnote {
  margin: 0px;
  font-size: 90%;
  padding-left: 4px;
  padding-right: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#tpwdeudbmw .gt_sourcenotes {
  color: #333333;
  background-color: #FFFFFF;
  border-bottom-style: none;
  border-bottom-width: 2px;
  border-bottom-color: #D3D3D3;
  border-left-style: none;
  border-left-width: 2px;
  border-left-color: #D3D3D3;
  border-right-style: none;
  border-right-width: 2px;
  border-right-color: #D3D3D3;
}

#tpwdeudbmw .gt_sourcenote {
  font-size: 90%;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 5px;
  padding-right: 5px;
}

#tpwdeudbmw .gt_left {
  text-align: left;
}

#tpwdeudbmw .gt_center {
  text-align: center;
}

#tpwdeudbmw .gt_right {
  text-align: right;
  font-variant-numeric: tabular-nums;
}

#tpwdeudbmw .gt_font_normal {
  font-weight: normal;
}

#tpwdeudbmw .gt_font_bold {
  font-weight: bold;
}

#tpwdeudbmw .gt_font_italic {
  font-style: italic;
}

#tpwdeudbmw .gt_super {
  font-size: 65%;
}

#tpwdeudbmw .gt_footnote_marks {
  font-style: italic;
  font-weight: normal;
  font-size: 75%;
  vertical-align: 0.4em;
}

#tpwdeudbmw .gt_asterisk {
  font-size: 100%;
  vertical-align: 0;
}

#tpwdeudbmw .gt_indent_1 {
  text-indent: 5px;
}

#tpwdeudbmw .gt_indent_2 {
  text-indent: 10px;
}

#tpwdeudbmw .gt_indent_3 {
  text-indent: 15px;
}

#tpwdeudbmw .gt_indent_4 {
  text-indent: 20px;
}

#tpwdeudbmw .gt_indent_5 {
  text-indent: 25px;
}
</style>
<table class="gt_table">
  <thead class="gt_header">
    <tr>
      <td colspan="10" class="gt_heading gt_title gt_font_normal gt_bottom_border" style>Plays by Type 2022</td>
    </tr>
    
  </thead>
  <thead class="gt_col_headings">
    <tr>
      <th class="gt_col_heading gt_columns_bottom_border gt_left" rowspan="1" colspan="1" scope="col">play_type</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">1</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">2</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">3</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">4</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">5</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">6</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">7</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">8</th>
      <th class="gt_col_heading gt_columns_bottom_border gt_right" rowspan="1" colspan="1" scope="col">9</th>
    </tr>
  </thead>
  <tbody class="gt_table_body">
    <tr><td class="gt_row gt_left">pass</td>
<td class="gt_row gt_right">62</td>
<td class="gt_row gt_right">47</td>
<td class="gt_row gt_right">56</td>
<td class="gt_row gt_right">38</td>
<td class="gt_row gt_right">23</td>
<td class="gt_row gt_right">20</td>
<td class="gt_row gt_right">29</td>
<td class="gt_row gt_right">43</td>
<td class="gt_row gt_right">27</td></tr>
    <tr><td class="gt_row gt_left">run</td>
<td class="gt_row gt_right">17</td>
<td class="gt_row gt_right">19</td>
<td class="gt_row gt_right">20</td>
<td class="gt_row gt_right">29</td>
<td class="gt_row gt_right">30</td>
<td class="gt_row gt_right">30</td>
<td class="gt_row gt_right">23</td>
<td class="gt_row gt_right">15</td>
<td class="gt_row gt_right">33</td></tr>
  </tbody>
  
  
</table>
</div>

As of the end of week 9 of the 2022 season, the New York Jets have run
561 offensive plays classified as a run or pass according to the
nflfastR play-by-play data.

# EPA

What I want to explore next has to do with expected points added (EPA).
For more information on how this is calculated you can visit:

- [nflWAR: A Reproducible Method for Offensive Player Evaluation in
  Football (Extended Edition)](https://arxiv.org/pdf/1802.00998.pdf)

- [Calibration for nflfastR models (including expected
  points)](https://www.opensourcefootball.com/posts/2020-09-28-nflfastr-ep-wp-and-cp-models/#ep-model-features)

I am going to explore the changing expected points over the course of
the season.

``` r
jets_pbp %>%
  filter(play_type == "pass") %>%
  select(play_id, play_type, week, epa) %>%
  ggplot2::ggplot(aes(x = factor(week), y = epa, fill = factor(play_type))) +
  geom_boxplot() + geom_jitter(width=0.1, alpha = 0.2) + theme_few()
```

![](jets_epa_by_player_and_playtype_files/figure-gfm/unnamed-chunk-5-1.png)

``` r
jets_pbp %>%
  filter(play_type == "run") %>%
  select(play_id, play_type, week, epa) %>%
  ggplot2::ggplot(aes(x = factor(week), y = epa, fill = factor(play_type))) +
  geom_boxplot() + geom_jitter(width=0.1, alpha = 0.2)
```

![](jets_epa_by_player_and_playtype_files/figure-gfm/unnamed-chunk-6-1.png)

## Citations

Carl S, Baldwin B (2022). *nflfastR: Functions to Efficiently Access NFL
Play by Play Data*. https://www.nflfastr.com/,
https://github.com/nflverse/nflfastR.
