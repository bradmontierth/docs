---
id: dashboards
title: "Dashboards"
hide_title: false
toc: false
---

Dashboards run automatically on top of the Core Data Model and Data Marts.  The dashboards below are hosted by Tuva and run on synthetic datasets.  The code for these dashboards can be found [here](https://github.com/tuva-health/analytics_gallery).


<div style={{ display: "flex", flexDirection: "column", gap: "50px" }}>

<div style={{ display: "flex", alignItems: "flex-start" }}> 
    <a href="#" onClick={(e) => { window.open('https://app.fabric.microsoft.com/view?r=eyJrIjoiN2Y2YjNkYWEtY2ZkZi00ZGIxLTk4ODMtNmU2ZjMxYjM3YzUyIiwidCI6ImJiM2M3Y2U1LTI2MjgtNGM5MS04Y2VmLTgwMTdjNjExNTk3OCIsImMiOjZ9', '_blank'); e.preventDefault(); }}>
      <img src="/img/cost_drivers.png" alt="Video Thumbnail" style={{ width: "120px", height: "auto", cursor: "pointer", marginRight: "30px"}} />
    </a>

  <div>
    <h3 style={{ margin: "0 20px" }}>Cost & Utilization Drivers</h3>
    <p style={{ margin: "5px 20px", fontSize: "0.9em", lineHeight: "1.4em" }}>
      This dashboard demonstrates how you can use the Tuva service category, encounter, and condition groupers to drill into claims data to identify opportunities for improvement.
    </p>
  </div>
</div>

<div style={{ display: "flex", alignItems: "flex-start" }}> 
    <a href="#" onClick={(e) => { window.open('https://app.fabric.microsoft.com/view?r=eyJrIjoiYTFhZWE0OWEtM2NjMi00ZGJlLTgxMjEtNmZmYmFiZmM5ODczIiwidCI6ImJiM2M3Y2U1LTI2MjgtNGM5MS04Y2VmLTgwMTdjNjExNTk3OCIsImMiOjZ9', '_blank'); e.preventDefault(); }}>
      <img src="/img/dqi.png" alt="Video Thumbnail" style={{ width: "120px", height: "auto", cursor: "pointer", marginRight: "30px"}} />
    </a>

  <div>
    <h3 style={{ margin: "0 20px" }}>Data Quality</h3>
    <p style={{ margin: "5px 20px", fontSize: "0.9em", lineHeight: "1.4em" }}>
      This dashboard demonstrates how you can use the Tuva data quality tables to profile and identify atomic-level data quality issues in raw claims data.
    </p>
  </div>
</div>

<div style={{ display: "flex", alignItems: "flex-start" }}> 
    <a href="#" onClick={(e) => { window.open('https://app.fabric.microsoft.com/view?r=eyJrIjoiODc2MjNkMWQtNzFlOC00Njg1LWJiNTEtYTU3MTE1NDJlNDhmIiwidCI6ImJiM2M3Y2U1LTI2MjgtNGM5MS04Y2VmLTgwMTdjNjExNTk3OCIsImMiOjZ9', '_blank'); e.preventDefault(); }}>
      <img src="/img/pop_insights.png" alt="Video Thumbnail" style={{ width: "120px", height: "auto", cursor: "pointer", marginRight: "30px"}} />
    </a>

  <div>
    <h3 style={{ margin: "0 20px" }}>Population Insights</h3>
    <p style={{ margin: "5px 20px", fontSize: "0.9em", lineHeight: "1.4em" }}>
      This dashboard demonstrates how several data marts from Tuva can be used to profile your patient population looking at demographics, chronic disease burden, spend, utilization, and acute events.
    </p>
  </div>
</div>

<div style={{ display: "flex", alignItems: "flex-start" }}> 
    <a href="#" onClick={(e) => { window.open('https://app.fabric.microsoft.com/view?r=eyJrIjoiODdjMWI1NDEtZGMxYi00ZjIwLTgyNzctYTI0YTQzMzhkZjhiIiwidCI6ImJiM2M3Y2U1LTI2MjgtNGM5MS04Y2VmLTgwMTdjNjExNTk3OCIsImMiOjZ9', '_blank'); e.preventDefault(); }}>
      <img src="/img/quality_measures.png" alt="Video Thumbnail" style={{ width: "120px", height: "auto", cursor: "pointer", marginRight: "30px"}} />
    </a>

  <div>
    <h3 style={{ margin: "0 20px" }}>Quality Measures</h3>
    <p style={{ margin: "5px 20px", fontSize: "0.9em", lineHeight: "1.4em" }}>
      This dashboard demonstrates how you can use the quality measures data mart to analyze clinical quality measures and care gaps.
    </p>
  </div>
</div>

<div style={{ display: "flex", alignItems: "flex-start" }}> 
    <a href="#" onClick={(e) => { window.open('https://app.fabric.microsoft.com/view?r=eyJrIjoiMDY2OWY2ZjEtYjFmYS00ZmU0LTk1YTItMTA1ODEyMjY4MWJmIiwidCI6ImJiM2M3Y2U1LTI2MjgtNGM5MS04Y2VmLTgwMTdjNjExNTk3OCIsImMiOjZ9', '_blank'); e.preventDefault(); }}>
      <img src="/img/risk_adjusted_benchmarks.png" alt="Video Thumbnail" style={{ width: "120px", height: "auto", cursor: "pointer", marginRight: "30px"}} />
    </a>

  <div>
    <h3 style={{ margin: "0 20px" }}>Risk-adjusted Benchmarks</h3>
    <p style={{ margin: "5px 20px", fontSize: "0.9em", lineHeight: "1.4em" }}>
      This dashboard shows the expected values produced by the benchmarking mart and compares them to actual values for analysis.
    </p>
  </div>
</div>

</div>
