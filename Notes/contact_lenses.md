LongDescr needs to be added to a migration's script so that column is created. it somehow got omitted. 


patient pay amount doesn't get updated after the product field resets everything 
updating the quanity of boxes by hand doesn't update the patient pay amount or total amount field. 
script doesn't work when fields have null values. 

need to add color field 
details are not being stored in the pos_trans table 
need to update contact lenses controller so 0s and null values are saved which will help the script work in the long run...
migration script needs to be updated so values like ";20" and "20;" are not saved. Empty values should be saved with 0. 
