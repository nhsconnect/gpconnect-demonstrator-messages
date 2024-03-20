# GP Connect Demonstrator Message

> Sample JSON messages to be returned by the NHS Digital GP Connect Demonstrator.

## Records

*NB* All these records refer to synthetic data constructed for test purposes

Regarding the columns in the table, NHS number relates to the NHS number of
test patient setup in the test GP system. Within the Demonstrator the same
patient has a different NHS number and name, this is represented by the columns
with names beginning 'Demonstrator'.

| Filename                                                           | NHS Number | Patient Name           | Description                                                                       | Deployed? | Demonstrator Patient # | Demonstrator NHS # | Demonstrator Patient Name |
| --------                                                           | ---------- | ------------           | -----------                                                                       | --------  | ---------------------- | ------------------ | ------------------------- |
| Consolidated_Allergies_Test_Record_v0_1.json                       | 9465699012 | Chittor Unmesh         | Rich Data Demonstrator Patient                                                    | Y         | 24                     | 9690937332         | Beyer                     |
| Consolidation_meds_test_record.json                                | 9450038082 | Cudmore Maleah         | Rich Data Demonstrator Patient                                                    | Y         | 22                     | 9690937316         | Pye                       |
| Consolidation_meds_test_record_.json                               | 9465698490 | Daniels Shoshana       | Rich Data Demonstrator Patient                                                    | Y         | 23                     | 9690937324         | Oakes                     |
| ConsultationResponse1.json                                         | 9999999999 | Jackson Jane           | Patient 2 Consultations and Problems                                              | Y         | 2                      | 9690937286         | Skelly                    |
| Consultations_ConsumerData_v0_2.json                               | 9465701874 | Edenborough Emmaline   | Rich Consultations                                                                | Y         | 31                     | 9690938223         | Grace                     |
| full_record.json                                                   | 9690937286 | SKELLY Horace          | Demonstrator Patient 2 Migration record                                           | Y         | 2                      | 9690937286         | Skelly                    |
| full_record_including_confidential_data.json                       | 9690937286 | SKELLY Horace          | Demonstrator Patient 2 Migration record                                           | Y         | 2                      | 9690937286         | Skelly                    |
| Hack_9465702013_Steinberg_MA_20210322.json                         | 9465702013 | Steinberg Andy         | Oct 2021 Hack Demonstrator Patient                                                | Y         | 27                     | 9690937820         | Lynch                     |
| Hack_9465702048_Wallimohamed_MA_StructuredDoseExampe_20211004.json | 9465702048 | Wallimohamed Trish     | Oct 2021 Hack Demonstrator Patient                                                | Y         | 25                     | 9690938193         | Prout                     |
| Hack_9465702250_Beaupaire_MA_StructuredDoseExample_20211004.json   | 9465702250 | Beaurepaire Deirdre    | Oct 2021 Hack Demonstrator Patient                                                | Y         | 26                     | 9690937464         | Mackay                    |
| Immunisations_Consumer_Data_File_V2.json                           | 9465701262 | Meyers Yannis          | Rich Immunizations                                                                | Y         | 28                     | 9690938207         | Gillon                    |
| Investigations_Consumer_Data_Extract_File.json                     | 9465701718 | Guerra Jordan          | Rich Investigations                                                               | Y         | 30                     | 9690937367         | Lewin                     |
| UNCAT_Consumer_Data_file.json                                      | 9465701297 | Livermore Cericeridwen | Rich Uncategorised                                                                | Y         | 29                     | 9690938215         | Wookey                    |
| Problems_ConsumerData_v0_2.json                                    | 9465701262 | Meyers Yannis          | Rich Problems                                                                     | Y         | 32                     | 9690937340         | Mullen                    |
| EMIS_Docs_consolidated_V2.json                                     | 9465701262 | Meyers Yannis          | EMIS Docs consolidated                                                            | Y         | 33                     | 9690938088         | Cave                      |
| Referrals_ConsumerData_v0_2.json                                   | 9465699918 | Magre Topsy            | Rich Referrals                                                                    | Y         | 34                     | 9690937693         | Day                       |
| DiaryEntries_ConsumerDatav0_2.json                                 | 9465701262 | Meyers Yannis          | Rich Diary Entries                                                                | Y         | 35                     | 9690938770         | Hyland                    |
| ~~Consolidated_allergies_test_record.json~~                        | 9465698830 | Ben-Avi Nusa           | Rich Data Demonstrator Patient                                                    | Y         | 24                     | 9690937332         | Beyer                     |
| ~~Medications_consumer_data_p2_v0_1.json~~                         | 9465698490 | Daniels Shoshana       | Rich Demonstrator Patient copied to Consolidation_meds_test_record_secondary.json | N         | 23                     | 9690937324         | Oakes                     |
| ~~Medications_consumer_data_v0_1.json~~                            | 9450038082 | Cudmore Maleah         | Rich Demonstrator Patient copied to Consolidation_meds_test_record.json           | N         | 22                     | 9690937316         | Pye                       |
| ~~Medications_consumer_data_v0_2.json~~                            | 9450038082 | Cudmore Maleah         | Rich Demonstrator Patient copied to Consolidation_meds_test_record.json           | N         | 22                     | 9690937316         | Pye                       |

The repository also contains records named for GUIDs these contain FHIR Binary resources used for testing.
