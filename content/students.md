---
title: "Student Publications"
date: "2025-09-15"
---



# Student Publications Dashboard

Since 2009, **201** SES graduate students have published **279** peer-reviewed articles as co-authors, accumulating **9,338** total citations.

*The "Most Cited Publications" table below highlights research where graduate students served as **first authors**, showcasing their leadership in conducting and publishing original research.*

---

## Graduate Student Publishing Trends

<img src="/students_files/figure-html/student-pubs-by-year-1.png" width="3600" />

---

## Student Publication Impact

<img src="/students_files/figure-html/student-citations-1.png" width="3600" />

---

<!-- ## Most Productive Graduate Students -->

<!-- ```{r student-productivity} -->
<!-- # Count publications per student -->
<!-- student_productivity <- student_data %>% -->
<!--   filter(SES_Grad_Students != "") %>% -->
<!--   # Split student names and count -->
<!--   mutate(student_list = strsplit(SES_Grad_Students, ", ")) %>% -->
<!--   unnest(student_list) %>% -->
<!--   group_by(student_list) %>% -->
<!--   summarise( -->
<!--     Publications = n(), -->
<!--     Total_Citations = sum(Citations, na.rm = TRUE), -->
<!--     Avg_Citations = round(mean(Citations, na.rm = TRUE), 1), -->
<!--     Years_Active = paste(sort(unique(Year)), collapse = ", "), -->
<!--     .groups = 'drop' -->
<!--   ) %>% -->
<!--   arrange(desc(Publications)) %>% -->
<!--   top_n(20, Publications)  # Top 20 most productive -->

<!-- p3 <- ggplot(student_productivity, aes(x = reorder(student_list, Publications), y = Publications)) + -->
<!--   geom_col(fill = "#9467bd", alpha = 0.8) + -->
<!--   coord_flip() + -->
<!--   labs( -->
<!--     title = "Top 20 Most Productive Graduate Students (2009+)", -->
<!--     subtitle = "Number of publications per student", -->
<!--     x = "Graduate Student", -->
<!--     y = "Number of Publications" -->
<!--   ) + -->
<!--   theme_minimal() + -->
<!--   theme( -->
<!--     plot.title = element_text(size = 16, face = "bold"), -->
<!--     plot.subtitle = element_text(size = 12), -->
<!--     axis.text.y = element_text(size = 9), -->
<!--     axis.text.x = element_text(size = 10), -->
<!--     axis.title = element_text(size = 12, face = "bold") -->
<!--   ) -->

<!-- ggplotly(p3, tooltip = c("x", "y")) %>% -->
<!--   layout( -->
<!--     xaxis = list(fixedrange = FALSE), -->
<!--     yaxis = list(fixedrange = FALSE) -->
<!--   ) %>% -->
<!--   config(displayModeBar = TRUE, displaylogo = FALSE) -->
<!-- ``` -->

<!-- --- -->

## Most Cited Publications with Graduate Students as First Authors

<table class="table table-striped table-hover" style="font-size: 12px; margin-left: auto; margin-right: auto;">
<caption><span id="tab:top-cited-student-pubs"></span>Table 1: Top 20 Most Cited Publications with Graduate Students as First Authors</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Title </th>
   <th style="text-align:left;"> Authors </th>
   <th style="text-align:left;"> Journal </th>
   <th style="text-align:center;"> Year </th>
   <th style="text-align:right;"> Citations </th>
   <th style="text-align:left;"> First Author Student </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> MODIS phenology-derived, multi-year distribution of conterminous US crop types </td>
   <td style="text-align:left;"> R Massey, TT Sankey, RG Congalton, K Yadav, PS Thenkabail, M Ozdogan, AJSán Meador </td>
   <td style="text-align:left;"> Remote Sensing of Environment </td>
   <td style="text-align:center;"> 2017 </td>
   <td style="text-align:right;"> 175 </td>
   <td style="text-align:left;"> Richard Massey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Limits to ponderosa pine regeneration following large high-severity forest fi... </td>
   <td style="text-align:left;"> C Haffey, TD Sisk, CD Allen, AE Thode, EQ Margolis </td>
   <td style="text-align:left;"> Fire Ecology </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 120 </td>
   <td style="text-align:left;"> Collin Haffey, Cory Allen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Evaluating unmanned aerial vehicle images for estimating forest canopy fuels ... </td>
   <td style="text-align:left;"> P Shin, T Sankey, MM Moore, AE Thode </td>
   <td style="text-align:left;"> Remote Sensing </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 110 </td>
   <td style="text-align:left;"> Patrick Shin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Thermochemical evolution of young rhyolites at Yellowstone: Evidence for a co... </td>
   <td style="text-align:left;"> JA Vazquez, SF Kyriazis, MR Reid, RC Sehler, FC Ramos </td>
   <td style="text-align:left;"> Journal of Volcanology and Geothermal... </td>
   <td style="text-align:center;"> 2009 </td>
   <td style="text-align:right;"> 99 </td>
   <td style="text-align:left;"> Jorge Vazquez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Dynamics of episodic Late Cretaceous–Cenozoic magmatism across Central to Eas... </td>
   <td style="text-align:left;"> WK Schleiffarth, MH Darin, MR Reid, PJ Umhoefer </td>
   <td style="text-align:left;"> Geosphere </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 96 </td>
   <td style="text-align:left;"> Michael Darin, William Schleiffarth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Mapping and measuring aeolian sand dunes with photogrammetry and LiDAR from u... </td>
   <td style="text-align:left;"> D Solazzo, JB Sankey, TT Sankey, SM Munson </td>
   <td style="text-align:left;"> Geomorphology </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 93 </td>
   <td style="text-align:left;"> Daniel Solazzo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Integrating cloud-based workflows in continental-scale cropland extent classi... </td>
   <td style="text-align:left;"> R Massey, TT Sankey, K Yadav, RG Congalton, JC Tilton </td>
   <td style="text-align:left;"> Remote Sensing of Environment </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 75 </td>
   <td style="text-align:left;"> Richard Massey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Land carbon models underestimate the severity and duration of drought’s impac... </td>
   <td style="text-align:left;"> HR Kolus, DN Huntzinger, CR Schwalm, JB Fisher, N McKay, Y Fang, AM Michalak, K Schaefer, Y Wei, ... </td>
   <td style="text-align:left;"> Scientific Reports </td>
   <td style="text-align:center;"> 2019 </td>
   <td style="text-align:right;"> 72 </td>
   <td style="text-align:left;"> Hannah Kolus, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Invasive buffelgrass detection using high‐resolution satellite and UAV imager... </td>
   <td style="text-align:left;"> K Elkind, TT Sankey, SM Munson, CE Aslan </td>
   <td style="text-align:left;"> Remote Sensing in Ecology and Conserv... </td>
   <td style="text-align:center;"> 2019 </td>
   <td style="text-align:right;"> 70 </td>
   <td style="text-align:left;"> Kaitlyn Elkind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Holocene climate and glacier variability at Hallet and Greyling Lakes, Chugac... </td>
   <td style="text-align:left;"> NP McKay, DS Kaufman </td>
   <td style="text-align:left;"> Journal of Paleolimnology </td>
   <td style="text-align:center;"> 2009 </td>
   <td style="text-align:right;"> 68 </td>
   <td style="text-align:left;"> Nicholas McKay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Late Holocene storm-trajectory changes inferred from the oxygen isotope compo... </td>
   <td style="text-align:left;"> CJ Schiff, DS Kaufman, AP Wolfe, J Dodd, Z Sharp </td>
   <td style="text-align:left;"> Journal of Paleolimnology </td>
   <td style="text-align:center;"> 2009 </td>
   <td style="text-align:right;"> 60 </td>
   <td style="text-align:left;"> Caleb Schiff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Rapid late Eocene exhumation of the Sivas Basin (Central Anatolia) driven by ... </td>
   <td style="text-align:left;"> MH Darin, PJ Umhoefer, SN Thomson </td>
   <td style="text-align:left;"> Tectonics </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 58 </td>
   <td style="text-align:left;"> Michael Darin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Increased light‐use efficiency in northern terrestrial ecosystems indicated b... </td>
   <td style="text-align:left;"> RT Thomas, IC Prentice, H Graven, P Ciais, JB Fisher, DJ Hayes, M Huang, DN Huntzinger, A Ito, A ... </td>
   <td style="text-align:left;"> Geophysical Research Letters </td>
   <td style="text-align:center;"> 2016 </td>
   <td style="text-align:right;"> 57 </td>
   <td style="text-align:left;"> Richelle Thomas, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> A quantitative method to analyze the quality of EIA information in wind energ... </td>
   <td style="text-align:left;"> T Chang, E Nielsen, W Auberle, FI Solop </td>
   <td style="text-align:left;"> Environmental impact assessment review </td>
   <td style="text-align:center;"> 2013 </td>
   <td style="text-align:right;"> 54 </td>
   <td style="text-align:left;"> Tony Chang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Diachronous initiation of Arabia–Eurasia collision from eastern Anatolia to t... </td>
   <td style="text-align:left;"> MH Darin, PJ Umhoefer </td>
   <td style="text-align:left;"> International Geology Review </td>
   <td style="text-align:center;"> 2022 </td>
   <td style="text-align:right;"> 50 </td>
   <td style="text-align:left;"> Michael Darin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Chimera: A multi-task recurrent convolutional neural network for forest class... </td>
   <td style="text-align:left;"> T Chang, BP Rasmussen, BG Dickson, LJ Zachmann </td>
   <td style="text-align:left;"> Remote Sensing </td>
   <td style="text-align:center;"> 2019 </td>
   <td style="text-align:right;"> 47 </td>
   <td style="text-align:left;"> Tony Chang, Tze-li Chang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Capturing arthropod diversity in complex cave systems </td>
   <td style="text-align:left;"> JJ Wynne, S Sommer, FG Howarth, BG Dickson, KD Voyles </td>
   <td style="text-align:left;"> Diversity and Distributions </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 46 </td>
   <td style="text-align:left;"> Jut Wynne </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Challenges of opportunity cost analysis in planning REDD+: a Honduran case st... </td>
   <td style="text-align:left;"> ST Plumb, EA Nielsen, Y-S Kim </td>
   <td style="text-align:left;"> Forests </td>
   <td style="text-align:center;"> 2012 </td>
   <td style="text-align:right;"> 43 </td>
   <td style="text-align:left;"> Spencer Plumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Characterization and hydraulic behaviour of the complex karst of the Kaibab P... </td>
   <td style="text-align:left;"> CJR Jones, AE Springer, BW Tobin, SJ Zappitello, NA Jones </td>
   <td style="text-align:left;"> Geological Society, London, Special P... </td>
   <td style="text-align:center;"> 2018 </td>
   <td style="text-align:right;"> 42 </td>
   <td style="text-align:left;"> Casey Jones, Natalie Jones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Holocene climate inferred from glacier extent, lake sediment and tree rings a... </td>
   <td style="text-align:left;"> TA Daigle, DS Kaufman </td>
   <td style="text-align:left;"> Journal of Quaternary Science: Publis... </td>
   <td style="text-align:center;"> 2009 </td>
   <td style="text-align:right;"> 41 </td>
   <td style="text-align:left;"> Thomas Daigle </td>
  </tr>
</tbody>
</table>

---

## Student Publication Journals

<img src="/students_files/figure-html/student-journals-1.png" width="3600" />

---

## Summary Statistics

<table class="table table-striped table-hover" style="font-size: 14px; margin-left: auto; margin-right: auto;">
<caption><span id="tab:student-summary-stats"></span>Table 2: Student Research Summary Statistics</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Metric </th>
   <th style="text-align:right;"> Value </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Student Publications </td>
   <td style="text-align:right;"> 279 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Total Citations </td>
   <td style="text-align:right;"> 9,338 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Publishing Students </td>
   <td style="text-align:right;"> 201 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Avg Citations/Paper </td>
   <td style="text-align:right;"> 33.5 </td>
  </tr>
</tbody>
</table>

---

*Data includes publications from 2009 to 2025. Last updated: September 15, 2025*
