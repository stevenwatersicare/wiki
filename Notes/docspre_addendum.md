1. Doctors should be able to unlock a chart the day after it's open so they can make adjustments 
2. If a link is clicked to open a chart the day after it's opened AND when it's already locked then a REVISION field in
the "doctor_patient_exam_chart" table should be updated (which has been created already by Kevin)

var x = Select revision frield from doctor_patient_exam_chart
revision = revision + 1
update doctor_patient_exam_chart set revision to revision 



3. If the chart is opened again on the same day, then no revision should be made. 
4. If a revision is opened again on the same day then the doctor should be able to keep editing that reivision.
5. If a revision is opened on the next day, then a new revision should be generated. 
6. The ORIGINAL_CHART column in the "doctor_patient_exam_chart_revisions" should be updated with the original chart id. 
7. Ospre should always use the latest revision for a doctor's chart. 
8. There should a history page or tab that shows the original chart and a list of revisions for it sorted in descening order. 
9. Appointments page link should link to the original chart or to the latest revision that is locked! 
10. The action for generating the pdf should use the original chart id if no revisions are available, othewise it should use then
latest revision that is locked. 
11. Sorting will be done by revision id, locked status, date locked,
12. Should add some kind of indicator that the chart is a revision
  