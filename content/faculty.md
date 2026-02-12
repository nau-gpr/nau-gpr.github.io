---
title: "Faculty Publications"
date: "2025-09-15"
---



# Faculty Publications Dashboard

The SES faculty have published **1,091** peer-reviewed articles since 2009, accumulating **71,631** citations with a collective H-index of **103**.

---

## Publications Through Time

<img src="/faculty_files/figure-html/publications-by-year-1.png" width="3600" />

<!-- --- -->

<!-- ## Citations Through Time -->

<!-- ```{r citations-by-year} -->
<!-- p2 <- ggplot(yearly_pubs, aes(x = Year, y = Citations)) + -->
<!--   geom_col(fill = "#2ca02c", alpha = 0.8) + -->
<!--   labs( -->
<!--     title = "Faculty Citations by Year", -->
<!--     subtitle = "Annual citation counts", -->
<!--     x = "Year", -->
<!--     y = "Total Citations" -->
<!--   ) + -->
<!--   theme_minimal() + -->
<!--   theme( -->
<!--     plot.title = element_text(size = 16, face = "bold"), -->
<!--     plot.subtitle = element_text(size = 12), -->
<!--     axis.text = element_text(size = 11), -->
<!--     axis.title = element_text(size = 12, face = "bold") -->
<!--   ) -->

<!-- ggplotly(p2, tooltip = c("x", "y")) %>% -->
<!--   layout( -->
<!--     xaxis = list(fixedrange = FALSE), -->
<!--     yaxis = list(fixedrange = FALSE) -->
<!--   ) %>% -->
<!--   config(displayModeBar = TRUE, displaylogo = FALSE) -->
<!-- ``` -->

<!-- --- -->

<!-- ## Faculty Productivity -->

<!-- ```{r faculty-productivity} -->
<!-- # Publications per year by faculty member using StartYear/EndYear -->
<!-- faculty_productivity <- faculty_data %>% -->
<!--   filter(SES_Faculty != "") %>% -->
<!--   # Split faculty names and count -->
<!--   mutate(faculty_list = strsplit(SES_Faculty, ", ")) %>% -->
<!--   unnest(faculty_list) %>% -->
<!--   group_by(faculty_list) %>% -->
<!--   summarise( -->
<!--     Publications = n(), -->
<!--     Total_Citations = sum(Citations, na.rm = TRUE), -->
<!--     Avg_Citations = round(mean(Citations, na.rm = TRUE), 1), -->
<!--     .groups = 'drop' -->
<!--   ) %>% -->
<!--   # Join with faculty info to get years active -->
<!--   left_join(faculty_info, by = c("faculty_list" = "FullName")) %>% -->
<!--   filter(!is.na(Years_Active), Years_Active > 0) %>% -->
<!--   mutate( -->
<!--     Publications_Per_Year = round(Publications / Years_Active, 2), -->
<!--     Tooltip_Text = paste0(faculty_list, "\n", -->
<!--                          "Publications: ", Publications, "\n", -->
<!--                          "Years Active: ", Years_Active, "\n", -->
<!--                          "Pubs/Year: ", Publications_Per_Year) -->
<!--   ) %>% -->
<!--   arrange(desc(Publications_Per_Year)) %>% -->
<!--   top_n(15, Publications_Per_Year)  # Top 15 by publications per year -->

<!-- p3 <- ggplot(faculty_productivity, aes(x = reorder(faculty_list, Publications_Per_Year),  -->
<!--                                       y = Publications_Per_Year, -->
<!--                                       text = Tooltip_Text)) + -->
<!--   geom_col(fill = "#9467bd", alpha = 0.8) + -->
<!--   coord_flip() + -->
<!--   labs( -->
<!--     title = "Top 15 Faculty Members by Publications per Year", -->
<!--     subtitle = "Annual publication rate based on StartYear/EndYear in database", -->
<!--     x = "Faculty Member", -->
<!--     y = "Publications per Year" -->
<!--   ) + -->
<!--   theme_minimal() + -->
<!--   theme( -->
<!--     plot.title = element_text(size = 16, face = "bold"), -->
<!--     plot.subtitle = element_text(size = 12), -->
<!--     axis.text = element_text(size = 10), -->
<!--     axis.title = element_text(size = 12, face = "bold") -->
<!--   ) -->

<!-- ggplotly(p3, tooltip = "text") %>% -->
<!--   layout( -->
<!--     xaxis = list(fixedrange = FALSE), -->
<!--     yaxis = list(fixedrange = FALSE) -->
<!--   ) %>% -->
<!--   config(displayModeBar = TRUE, displaylogo = FALSE) -->
<!-- ``` -->

<!-- --- -->

## Most Cited Publications by SES Faculty

<table class="table table-striped table-hover" style="font-size: 12px; margin-left: auto; margin-right: auto;">
<caption><span id="tab:top-cited-student-pubs"></span>Table 1: Top 20 Most Cited Publications by SES Faculty</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Title </th>
   <th style="text-align:left;"> Authors </th>
   <th style="text-align:left;"> Journal </th>
   <th style="text-align:center;"> Year </th>
   <th style="text-align:right;"> Citations </th>
   <th style="text-align:left;"> Faculty </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Technical summary </td>
   <td style="text-align:left;"> PA Arias, N Bellouin, E Coppola, RG Jones, G Krinner, J Marotzke, V Naik, MD Palmer, G-K Plattner... </td>
   <td style="text-align:left;"> Cambridge University Press </td>
   <td style="text-align:center;"> 2021 </td>
   <td style="text-align:right;"> 19094 </td>
   <td style="text-align:left;"> D Kaufman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> A meta‐analysis of context‐dependency in plant response to inoculation with m... </td>
   <td style="text-align:left;"> Hoeksema JD, Chaudhary VB, Gehring CA, Johnson NC, Karst J, Koide RT, Pringle A, Zabinski C, Beve... </td>
   <td style="text-align:left;"> Ecology letters </td>
   <td style="text-align:center;"> 2010 </td>
   <td style="text-align:right;"> 1357 </td>
   <td style="text-align:left;"> N Johnson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Continental-scale temperature variability during the past two millennia </td>
   <td style="text-align:left;"> Pages2k Consortium </td>
   <td style="text-align:left;"> Nature geoscience </td>
   <td style="text-align:center;"> 2013 </td>
   <td style="text-align:right;"> 1089 </td>
   <td style="text-align:left;"> D Kaufman, N McKay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Future global climate: scenario-based projections and near-term information </td>
   <td style="text-align:left;"> J-Y Lee, J Marotzke, G Bala, L Cao, S Corti, JP Dunne, F Engelbrecht, E Fischer, JC Fyfe, C Jones... </td>
   <td style="text-align:left;"> Climate change </td>
   <td style="text-align:center;"> 2021 </td>
   <td style="text-align:right;"> 1010 </td>
   <td style="text-align:left;"> D Kaufman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Resource stoichiometry elucidates the structure and function of arbuscular my... </td>
   <td style="text-align:left;"> NC Johnson </td>
   <td style="text-align:left;"> New Phytologist </td>
   <td style="text-align:center;"> 2010 </td>
   <td style="text-align:right;"> 984 </td>
   <td style="text-align:left;"> N Johnson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Key competencies in sustainability in higher education—toward an agreed-upon ... </td>
   <td style="text-align:left;"> K Brundiers, M Barth, G Cebrián, M Cohen, L Diaz, S Doucette-Remington, W Dripps, G Habron, N Har... </td>
   <td style="text-align:left;"> Sustainability Science </td>
   <td style="text-align:center;"> 2021 </td>
   <td style="text-align:right;"> 916 </td>
   <td style="text-align:left;"> R Parnell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Global assessment of arbuscular mycorrhizal fungus diversity reveals very low... </td>
   <td style="text-align:left;"> Davison J, Moora M, Öpik M, Adholeya A, Ainsaar L, Bâ A, Burla S, Diedhiou AG, Hiiesalu I, Jairus... </td>
   <td style="text-align:left;"> Science </td>
   <td style="text-align:center;"> 2015 </td>
   <td style="text-align:right;"> 907 </td>
   <td style="text-align:left;"> N Johnson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Global patterns of drought recovery </td>
   <td style="text-align:left;"> CR Schwalm, WRL Anderegg, AM Michalak, JB Fisher, F Biondi, G Koch, M Litvak, K Ogle, JD Shaw, A ... </td>
   <td style="text-align:left;"> Nature </td>
   <td style="text-align:center;"> 2017 </td>
   <td style="text-align:right;"> 885 </td>
   <td style="text-align:left;"> D Huntzinger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Resource limitation is a driver of local adaptation in mycorrhizal symbioses </td>
   <td style="text-align:left;"> NC Johnson, GWT Wilson, MA Bowker, JA Wilson, RM Miller </td>
   <td style="text-align:left;"> Proceedings of the National Academy o... </td>
   <td style="text-align:center;"> 2010 </td>
   <td style="text-align:right;"> 830 </td>
   <td style="text-align:left;"> N Johnson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Recent warming reverses long-term Arctic cooling </td>
   <td style="text-align:left;"> DS Kaufman, DP Schneider, NP McKay, CM Ammann, RS Bradley, KR Briffa, GH Miller, BL Otto-Bliesner... </td>
   <td style="text-align:left;"> Science </td>
   <td style="text-align:center;"> 2009 </td>
   <td style="text-align:right;"> 761 </td>
   <td style="text-align:left;"> D Kaufman, N McKay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Climate science special report: Fourth national climate assessment (NCA4), Vo... </td>
   <td style="text-align:left;"> DJ Wuebbles, DW Fahey, KA Hibbard, JR Arnold, B DeAngelo, S Doherty, DR Easterling, J Edmonds, T ... </td>
   <td style="text-align:left;"> USGCRP </td>
   <td style="text-align:center;"> 2017 </td>
   <td style="text-align:right;"> 759 </td>
   <td style="text-align:left;"> D Huntzinger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Climate-driven risks to the climate mitigation potential of forests </td>
   <td style="text-align:left;"> WRL Anderegg, AT Trugman, G Badgley, CM Anderson, A Bartuska, P Ciais, D Cullenward, CB Field, J ... </td>
   <td style="text-align:left;"> Science </td>
   <td style="text-align:center;"> 2020 </td>
   <td style="text-align:right;"> 733 </td>
   <td style="text-align:left;"> R Anderson, D Huntzinger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Changing state of the climate system </td>
   <td style="text-align:left;"> SK Gulev, PW Thorne, J Ahn, FJ Dentener, CM Domingues, S Gerland, D Gong, DS Kaufman, HC Nnamchi,... </td>
   <td style="text-align:left;"> Cambridge University Press </td>
   <td style="text-align:center;"> 2021 </td>
   <td style="text-align:right;"> 701 </td>
   <td style="text-align:left;"> D Kaufman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> The terrestrial biosphere as a net source of greenhouse gases to the atmosphere </td>
   <td style="text-align:left;"> H Tian, C Lu, P Ciais, AM Michalak, JG Canadell, E Saikawa, DN Huntzinger, KR Gurney, S Sitch, B ... </td>
   <td style="text-align:left;"> Nature </td>
   <td style="text-align:center;"> 2016 </td>
   <td style="text-align:right;"> 660 </td>
   <td style="text-align:left;"> D Huntzinger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Global climate evolution during the last deglaciation </td>
   <td style="text-align:left;"> PU Clark, JD Shakun, PA Baker, PJ Bartlein, S Brewer, E Brook, AE Carlson, H Cheng, DS Kaufman, Z... </td>
   <td style="text-align:left;"> Proceedings of the National Academy o... </td>
   <td style="text-align:center;"> 2012 </td>
   <td style="text-align:right;"> 628 </td>
   <td style="text-align:left;"> D Kaufman </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Mycorrhizal phenotypes and the law of the minimum </td>
   <td style="text-align:left;"> NC Johnson, GWT Wilson, JA Wilson, RM Miller, MA Bowker </td>
   <td style="text-align:left;"> New Phytologist </td>
   <td style="text-align:center;"> 2015 </td>
   <td style="text-align:right;"> 516 </td>
   <td style="text-align:left;"> N Johnson </td>
  </tr>
  <tr>
   <td style="text-align:left;"> UAV lidar and hyperspectral fusion for forest monitoring in the southwestern USA </td>
   <td style="text-align:left;"> T Sankey, J Donager, J McVay, JB Sankey </td>
   <td style="text-align:left;"> Remote Sensing of Environment </td>
   <td style="text-align:center;"> 2017 </td>
   <td style="text-align:right;"> 516 </td>
   <td style="text-align:left;"> T Sankey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> The time-transgressive termination of the African Humid Period </td>
   <td style="text-align:left;"> TM Shanahan, NP McKay, KA Hughen, JT Overpeck, B Otto-Bliesner, CW Heil, J King, CA Scholz, J Peck </td>
   <td style="text-align:left;"> Nature Geoscience </td>
   <td style="text-align:center;"> 2015 </td>
   <td style="text-align:right;"> 489 </td>
   <td style="text-align:left;"> N McKay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Early onset of industrial-era warming across the oceans and continents </td>
   <td style="text-align:left;"> NJ Abram, HV McGregor, JE Tierney, MN Evans, NP McKay, DS Kaufman </td>
   <td style="text-align:left;"> Nature </td>
   <td style="text-align:center;"> 2016 </td>
   <td style="text-align:right;"> 451 </td>
   <td style="text-align:left;"> D Kaufman, N McKay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Intergovernmental Panel on Climate Change (IPCC). Summary for Policymakers </td>
   <td style="text-align:left;"> RP Allan, PA Arias, S Berger, JG Canadell, C Cassou, D Chen, A Cherchi, SL Connors, E Coppola, FA... </td>
   <td style="text-align:left;"> Climate change </td>
   <td style="text-align:center;"> 2023 </td>
   <td style="text-align:right;"> 436 </td>
   <td style="text-align:left;"> D Kaufman </td>
  </tr>
</tbody>
</table>

---

## Journal Distribution

<img src="/faculty_files/figure-html/journal-distribution-1.png" width="3600" />

---

## Summary Statistics

<table class="table table-striped table-hover" style="font-size: 14px; margin-left: auto; margin-right: auto;">
<caption><span id="tab:faculty-summary-stats"></span>Table 2: Faculty Research Summary Statistics</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Metric </th>
   <th style="text-align:right;"> Value </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Total Publications </td>
   <td style="text-align:right;"> 1,091 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Total Citations </td>
   <td style="text-align:right;"> 71,631 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Department H-Index </td>
   <td style="text-align:right;"> 103 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Actively Publishing Faculty (past 2 years) </td>
   <td style="text-align:right;"> 36 </td>
  </tr>
</tbody>
</table>

---

*Data includes publications from 2009 to 2025. Last updated: September 15, 2025*
