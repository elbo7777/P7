???z      ?sklearn.pipeline??Pipeline???)??}?(?steps?]?(?
preprocess?h)??}?(h]?(?imputer??sklearn.impute._base??SimpleImputer???)??}?(?missing_values?G?      ?add_indicator???strategy??median??
fill_value?N?verbose?K ?copy???feature_names_in_??numpy.core.multiarray??_reconstruct????numpy??ndarray???K ??Cb???R?(KM??h?dtype????O8?????R?(K?|?NNNJ????J????K?t?b?]?(?NAME_CONTRACT_TYPE??CODE_GENDER??FLAG_OWN_CAR??FLAG_OWN_REALTY??CNT_CHILDREN??AMT_INCOME_TOTAL??
AMT_CREDIT??AMT_ANNUITY??AMT_GOODS_PRICE??REGION_POPULATION_RELATIVE??
DAYS_BIRTH??DAYS_EMPLOYED??DAYS_REGISTRATION??DAYS_ID_PUBLISH??OWN_CAR_AGE??CNT_FAM_MEMBERS??REGION_RATING_CLIENT??REGION_RATING_CLIENT_W_CITY??HOUR_APPR_PROCESS_START??EXT_SOURCE_1??EXT_SOURCE_2??EXT_SOURCE_3??APARTMENTS_AVG??BASEMENTAREA_AVG??YEARS_BEGINEXPLUATATION_AVG??YEARS_BUILD_AVG??COMMONAREA_AVG??ELEVATORS_AVG??ENTRANCES_AVG??FLOORSMAX_AVG??FLOORSMIN_AVG??LANDAREA_AVG??LIVINGAPARTMENTS_AVG??LIVINGAREA_AVG??NONLIVINGAPARTMENTS_AVG??NONLIVINGAREA_AVG??APARTMENTS_MODE??BASEMENTAREA_MODE??YEARS_BEGINEXPLUATATION_MODE??YEARS_BUILD_MODE??COMMONAREA_MODE??ELEVATORS_MODE??ENTRANCES_MODE??FLOORSMAX_MODE??FLOORSMIN_MODE??LANDAREA_MODE??LIVINGAPARTMENTS_MODE??LIVINGAREA_MODE??NONLIVINGAPARTMENTS_MODE??NONLIVINGAREA_MODE??APARTMENTS_MEDI??BASEMENTAREA_MEDI??YEARS_BEGINEXPLUATATION_MEDI??YEARS_BUILD_MEDI??COMMONAREA_MEDI??ELEVATORS_MEDI??ENTRANCES_MEDI??FLOORSMAX_MEDI??FLOORSMIN_MEDI??LANDAREA_MEDI??LIVINGAPARTMENTS_MEDI??LIVINGAREA_MEDI??NONLIVINGAPARTMENTS_MEDI??NONLIVINGAREA_MEDI??TOTALAREA_MODE??EMERGENCYSTATE_MODE??OBS_30_CNT_SOCIAL_CIRCLE??DEF_30_CNT_SOCIAL_CIRCLE??OBS_60_CNT_SOCIAL_CIRCLE??DEF_60_CNT_SOCIAL_CIRCLE??DAYS_LAST_PHONE_CHANGE??AMT_REQ_CREDIT_BUREAU_HOUR??AMT_REQ_CREDIT_BUREAU_DAY??AMT_REQ_CREDIT_BUREAU_WEEK??AMT_REQ_CREDIT_BUREAU_MON??AMT_REQ_CREDIT_BUREAU_QRT??AMT_REQ_CREDIT_BUREAU_YEAR??
FLAG_MOBIL??FLAG_EMP_PHONE??FLAG_WORK_PHONE??FLAG_CONT_MOBILE??
FLAG_PHONE??
FLAG_EMAIL??REG_REGION_NOT_LIVE_REGION??REG_REGION_NOT_WORK_REGION??LIVE_REGION_NOT_WORK_REGION??REG_CITY_NOT_LIVE_CITY??REG_CITY_NOT_WORK_CITY??LIVE_CITY_NOT_WORK_CITY??FLAG_DOCUMENT_2??FLAG_DOCUMENT_3??FLAG_DOCUMENT_4??FLAG_DOCUMENT_5??FLAG_DOCUMENT_6??FLAG_DOCUMENT_7??FLAG_DOCUMENT_8??FLAG_DOCUMENT_9??FLAG_DOCUMENT_10??FLAG_DOCUMENT_11??FLAG_DOCUMENT_12??FLAG_DOCUMENT_13??FLAG_DOCUMENT_14??FLAG_DOCUMENT_15??FLAG_DOCUMENT_16??FLAG_DOCUMENT_17??FLAG_DOCUMENT_18??FLAG_DOCUMENT_19??FLAG_DOCUMENT_20??FLAG_DOCUMENT_21??COUNT(bureau)??MEDIAN(bureau.AMT_ANNUITY)??%MEDIAN(bureau.AMT_CREDIT_MAX_OVERDUE)??MEDIAN(bureau.AMT_CREDIT_SUM)??"MEDIAN(bureau.AMT_CREDIT_SUM_DEBT)??#MEDIAN(bureau.AMT_CREDIT_SUM_LIMIT)??%MEDIAN(bureau.AMT_CREDIT_SUM_OVERDUE)??!MEDIAN(bureau.CNT_CREDIT_PROLONG)??!MEDIAN(bureau.CREDIT_DAY_OVERDUE)??MEDIAN(bureau.DAYS_CREDIT)??"MEDIAN(bureau.DAYS_CREDIT_ENDDATE)??!MEDIAN(bureau.DAYS_CREDIT_UPDATE)?? MEDIAN(bureau.DAYS_ENDDATE_FACT)??COUNT(bureau_balance)??%MEDIAN(bureau_balance.MONTHS_BALANCE)??COUNT(prev_app)??MEDIAN(prev_app.AMT_ANNUITY)?? MEDIAN(prev_app.AMT_APPLICATION)??MEDIAN(prev_app.AMT_CREDIT)??!MEDIAN(prev_app.AMT_DOWN_PAYMENT)?? MEDIAN(prev_app.AMT_GOODS_PRICE)??MEDIAN(prev_app.CNT_PAYMENT)??MEDIAN(prev_app.DAYS_DECISION)??#MEDIAN(prev_app.DAYS_FIRST_DRAWING)??MEDIAN(prev_app.DAYS_FIRST_DUE)??MEDIAN(prev_app.DAYS_LAST_DUE)??*MEDIAN(prev_app.DAYS_LAST_DUE_1ST_VERSION)??!MEDIAN(prev_app.DAYS_TERMINATION)??(MEDIAN(prev_app.HOUR_APPR_PROCESS_START)??*MEDIAN(prev_app.NFLAG_INSURED_ON_APPROVAL)??"MEDIAN(prev_app.RATE_DOWN_PAYMENT)??!MEDIAN(prev_app.SELLERPLACE_AREA)??COUNT(cash_balance)??#MEDIAN(cash_balance.CNT_INSTALMENT)??*MEDIAN(cash_balance.CNT_INSTALMENT_FUTURE)??#MEDIAN(cash_balance.MONTHS_BALANCE)??MEDIAN(cash_balance.SK_DPD)??MEDIAN(cash_balance.SK_DPD_DEF)??COUNT(payments)??MEDIAN(payments.AMT_INSTALMENT)??MEDIAN(payments.AMT_PAYMENT)??#MEDIAN(payments.DAYS_ENTRY_PAYMENT)?? MEDIAN(payments.DAYS_INSTALMENT)??&MEDIAN(payments.NUM_INSTALMENT_NUMBER)??'MEDIAN(payments.NUM_INSTALMENT_VERSION)??COUNT(card_balance)?? MEDIAN(card_balance.AMT_BALANCE)??,MEDIAN(card_balance.AMT_CREDIT_LIMIT_ACTUAL)??-MEDIAN(card_balance.AMT_DRAWINGS_ATM_CURRENT)??)MEDIAN(card_balance.AMT_DRAWINGS_CURRENT)??/MEDIAN(card_balance.AMT_DRAWINGS_OTHER_CURRENT)??-MEDIAN(card_balance.AMT_DRAWINGS_POS_CURRENT)??,MEDIAN(card_balance.AMT_INST_MIN_REGULARITY)??(MEDIAN(card_balance.AMT_PAYMENT_CURRENT)??.MEDIAN(card_balance.AMT_PAYMENT_TOTAL_CURRENT)??-MEDIAN(card_balance.AMT_RECEIVABLE_PRINCIPAL)??"MEDIAN(card_balance.AMT_RECIVABLE)??)MEDIAN(card_balance.AMT_TOTAL_RECEIVABLE)??-MEDIAN(card_balance.CNT_DRAWINGS_ATM_CURRENT)??)MEDIAN(card_balance.CNT_DRAWINGS_CURRENT)??/MEDIAN(card_balance.CNT_DRAWINGS_OTHER_CURRENT)??-MEDIAN(card_balance.CNT_DRAWINGS_POS_CURRENT)??.MEDIAN(card_balance.CNT_INSTALMENT_MATURE_CUM)??#MEDIAN(card_balance.MONTHS_BALANCE)??MEDIAN(card_balance.SK_DPD)??MEDIAN(card_balance.SK_DPD_DEF)??CUM_SUM(AMT_ANNUITY)??CUM_SUM(AMT_CREDIT)??CUM_SUM(AMT_GOODS_PRICE)??CUM_SUM(AMT_INCOME_TOTAL)??"CUM_SUM(AMT_REQ_CREDIT_BUREAU_DAY)??#CUM_SUM(AMT_REQ_CREDIT_BUREAU_HOUR)??"CUM_SUM(AMT_REQ_CREDIT_BUREAU_MON)??"CUM_SUM(AMT_REQ_CREDIT_BUREAU_QRT)??#CUM_SUM(AMT_REQ_CREDIT_BUREAU_WEEK)??#CUM_SUM(AMT_REQ_CREDIT_BUREAU_YEAR)??CUM_SUM(APARTMENTS_AVG)??CUM_SUM(APARTMENTS_MEDI)??CUM_SUM(APARTMENTS_MODE)??CUM_SUM(BASEMENTAREA_AVG)??CUM_SUM(BASEMENTAREA_MEDI)??CUM_SUM(BASEMENTAREA_MODE)??CUM_SUM(CNT_CHILDREN)??CUM_SUM(CNT_FAM_MEMBERS)??CUM_SUM(COMMONAREA_AVG)??CUM_SUM(COMMONAREA_MEDI)??CUM_SUM(COMMONAREA_MODE)??CUM_SUM(DAYS_BIRTH)??CUM_SUM(DAYS_EMPLOYED)??CUM_SUM(DAYS_ID_PUBLISH)??CUM_SUM(DAYS_LAST_PHONE_CHANGE)??CUM_SUM(DAYS_REGISTRATION)??!CUM_SUM(DEF_30_CNT_SOCIAL_CIRCLE)??!CUM_SUM(DEF_60_CNT_SOCIAL_CIRCLE)??CUM_SUM(ELEVATORS_AVG)??CUM_SUM(ELEVATORS_MEDI)??CUM_SUM(ELEVATORS_MODE)??CUM_SUM(ENTRANCES_AVG)??CUM_SUM(ENTRANCES_MEDI)??CUM_SUM(ENTRANCES_MODE)??CUM_SUM(EXT_SOURCE_1)??CUM_SUM(EXT_SOURCE_2)??CUM_SUM(EXT_SOURCE_3)??CUM_SUM(FLOORSMAX_AVG)??CUM_SUM(FLOORSMAX_MEDI)??CUM_SUM(FLOORSMAX_MODE)??CUM_SUM(FLOORSMIN_AVG)??CUM_SUM(FLOORSMIN_MEDI)??CUM_SUM(FLOORSMIN_MODE)?? CUM_SUM(HOUR_APPR_PROCESS_START)??CUM_SUM(LANDAREA_AVG)??CUM_SUM(LANDAREA_MEDI)??CUM_SUM(LANDAREA_MODE)??CUM_SUM(LIVINGAPARTMENTS_AVG)??CUM_SUM(LIVINGAPARTMENTS_MEDI)??CUM_SUM(LIVINGAPARTMENTS_MODE)??CUM_SUM(LIVINGAREA_AVG)??CUM_SUM(LIVINGAREA_MEDI)??CUM_SUM(LIVINGAREA_MODE)?? CUM_SUM(NONLIVINGAPARTMENTS_AVG)??!CUM_SUM(NONLIVINGAPARTMENTS_MEDI)??!CUM_SUM(NONLIVINGAPARTMENTS_MODE)??CUM_SUM(NONLIVINGAREA_AVG)??CUM_SUM(NONLIVINGAREA_MEDI)??CUM_SUM(NONLIVINGAREA_MODE)??!CUM_SUM(OBS_30_CNT_SOCIAL_CIRCLE)??!CUM_SUM(OBS_60_CNT_SOCIAL_CIRCLE)??CUM_SUM(OWN_CAR_AGE)??#CUM_SUM(REGION_POPULATION_RELATIVE)??CUM_SUM(REGION_RATING_CLIENT)??$CUM_SUM(REGION_RATING_CLIENT_W_CITY)??CUM_SUM(TARGET)??CUM_SUM(TOTALAREA_MODE)??$CUM_SUM(YEARS_BEGINEXPLUATATION_AVG)??%CUM_SUM(YEARS_BEGINEXPLUATATION_MEDI)??%CUM_SUM(YEARS_BEGINEXPLUATATION_MODE)??CUM_SUM(YEARS_BUILD_AVG)??CUM_SUM(YEARS_BUILD_MEDI)??CUM_SUM(YEARS_BUILD_MODE)??$MEDIAN(bureau.COUNT(bureau_balance))??#MEDIAN(bureau.CUM_SUM(AMT_ANNUITY))??.MEDIAN(bureau.CUM_SUM(AMT_CREDIT_MAX_OVERDUE))??&MEDIAN(bureau.CUM_SUM(AMT_CREDIT_SUM))??+MEDIAN(bureau.CUM_SUM(AMT_CREDIT_SUM_DEBT))??,MEDIAN(bureau.CUM_SUM(AMT_CREDIT_SUM_LIMIT))??.MEDIAN(bureau.CUM_SUM(AMT_CREDIT_SUM_OVERDUE))??*MEDIAN(bureau.CUM_SUM(CNT_CREDIT_PROLONG))??*MEDIAN(bureau.CUM_SUM(CREDIT_DAY_OVERDUE))??#MEDIAN(bureau.CUM_SUM(DAYS_CREDIT))??+MEDIAN(bureau.CUM_SUM(DAYS_CREDIT_ENDDATE))??*MEDIAN(bureau.CUM_SUM(DAYS_CREDIT_UPDATE))??)MEDIAN(bureau.CUM_SUM(DAYS_ENDDATE_FACT))??4MEDIAN(bureau.MEDIAN(bureau_balance.MONTHS_BALANCE))??)MEDIAN(bureau_balance.bureau.AMT_ANNUITY)??4MEDIAN(bureau_balance.bureau.AMT_CREDIT_MAX_OVERDUE)??,MEDIAN(bureau_balance.bureau.AMT_CREDIT_SUM)??1MEDIAN(bureau_balance.bureau.AMT_CREDIT_SUM_DEBT)??2MEDIAN(bureau_balance.bureau.AMT_CREDIT_SUM_LIMIT)??4MEDIAN(bureau_balance.bureau.AMT_CREDIT_SUM_OVERDUE)??0MEDIAN(bureau_balance.bureau.CNT_CREDIT_PROLONG)??0MEDIAN(bureau_balance.bureau.CREDIT_DAY_OVERDUE)??)MEDIAN(bureau_balance.bureau.DAYS_CREDIT)??1MEDIAN(bureau_balance.bureau.DAYS_CREDIT_ENDDATE)??0MEDIAN(bureau_balance.bureau.DAYS_CREDIT_UPDATE)??/MEDIAN(bureau_balance.bureau.DAYS_ENDDATE_FACT)??%MEDIAN(prev_app.CUM_SUM(AMT_ANNUITY))??)MEDIAN(prev_app.CUM_SUM(AMT_APPLICATION))??$MEDIAN(prev_app.CUM_SUM(AMT_CREDIT))??*MEDIAN(prev_app.CUM_SUM(AMT_DOWN_PAYMENT))??)MEDIAN(prev_app.CUM_SUM(AMT_GOODS_PRICE))??%MEDIAN(prev_app.CUM_SUM(CNT_PAYMENT))??'MEDIAN(prev_app.CUM_SUM(DAYS_DECISION))??,MEDIAN(prev_app.CUM_SUM(DAYS_FIRST_DRAWING))??(MEDIAN(prev_app.CUM_SUM(DAYS_FIRST_DUE))??'MEDIAN(prev_app.CUM_SUM(DAYS_LAST_DUE))??3MEDIAN(prev_app.CUM_SUM(DAYS_LAST_DUE_1ST_VERSION))??*MEDIAN(prev_app.CUM_SUM(DAYS_TERMINATION))??1MEDIAN(prev_app.CUM_SUM(HOUR_APPR_PROCESS_START))??3MEDIAN(prev_app.CUM_SUM(NFLAG_INSURED_ON_APPROVAL))??+MEDIAN(prev_app.CUM_SUM(RATE_DOWN_PAYMENT))??*MEDIAN(prev_app.CUM_SUM(SELLERPLACE_AREA))??,MEDIAN(cash_balance.CUM_SUM(CNT_INSTALMENT))??3MEDIAN(cash_balance.CUM_SUM(CNT_INSTALMENT_FUTURE))??,MEDIAN(cash_balance.CUM_SUM(MONTHS_BALANCE))??$MEDIAN(cash_balance.CUM_SUM(SK_DPD))??(MEDIAN(cash_balance.CUM_SUM(SK_DPD_DEF))??(MEDIAN(payments.CUM_SUM(AMT_INSTALMENT))??%MEDIAN(payments.CUM_SUM(AMT_PAYMENT))??,MEDIAN(payments.CUM_SUM(DAYS_ENTRY_PAYMENT))??)MEDIAN(payments.CUM_SUM(DAYS_INSTALMENT))??/MEDIAN(payments.CUM_SUM(NUM_INSTALMENT_NUMBER))??0MEDIAN(payments.CUM_SUM(NUM_INSTALMENT_VERSION))??)MEDIAN(card_balance.CUM_SUM(AMT_BALANCE))??5MEDIAN(card_balance.CUM_SUM(AMT_CREDIT_LIMIT_ACTUAL))??6MEDIAN(card_balance.CUM_SUM(AMT_DRAWINGS_ATM_CURRENT))??2MEDIAN(card_balance.CUM_SUM(AMT_DRAWINGS_CURRENT))??8MEDIAN(card_balance.CUM_SUM(AMT_DRAWINGS_OTHER_CURRENT))??6MEDIAN(card_balance.CUM_SUM(AMT_DRAWINGS_POS_CURRENT))??5MEDIAN(card_balance.CUM_SUM(AMT_INST_MIN_REGULARITY))??1MEDIAN(card_balance.CUM_SUM(AMT_PAYMENT_CURRENT))??7MEDIAN(card_balance.CUM_SUM(AMT_PAYMENT_TOTAL_CURRENT))??6MEDIAN(card_balance.CUM_SUM(AMT_RECEIVABLE_PRINCIPAL))??+MEDIAN(card_balance.CUM_SUM(AMT_RECIVABLE))??2MEDIAN(card_balance.CUM_SUM(AMT_TOTAL_RECEIVABLE))??6MEDIAN(card_balance.CUM_SUM(CNT_DRAWINGS_ATM_CURRENT))??2MEDIAN(card_balance.CUM_SUM(CNT_DRAWINGS_CURRENT))??8MEDIAN(card_balance.CUM_SUM(CNT_DRAWINGS_OTHER_CURRENT))??6MEDIAN(card_balance.CUM_SUM(CNT_DRAWINGS_POS_CURRENT))??7MEDIAN(card_balance.CUM_SUM(CNT_INSTALMENT_MATURE_CUM))??,MEDIAN(card_balance.CUM_SUM(MONTHS_BALANCE))??$MEDIAN(card_balance.CUM_SUM(SK_DPD))??(MEDIAN(card_balance.CUM_SUM(SK_DPD_DEF))??CUM_SUM(COUNT(bureau))??CUM_SUM(COUNT(bureau_balance))??CUM_SUM(COUNT(card_balance))??CUM_SUM(COUNT(cash_balance))??CUM_SUM(COUNT(payments))??CUM_SUM(COUNT(prev_app))??#CUM_SUM(MEDIAN(bureau.AMT_ANNUITY))??.CUM_SUM(MEDIAN(bureau.AMT_CREDIT_MAX_OVERDUE))??&CUM_SUM(MEDIAN(bureau.AMT_CREDIT_SUM))??+CUM_SUM(MEDIAN(bureau.AMT_CREDIT_SUM_DEBT))??,CUM_SUM(MEDIAN(bureau.AMT_CREDIT_SUM_LIMIT))??.CUM_SUM(MEDIAN(bureau.AMT_CREDIT_SUM_OVERDUE))??*CUM_SUM(MEDIAN(bureau.CNT_CREDIT_PROLONG))??*CUM_SUM(MEDIAN(bureau.CREDIT_DAY_OVERDUE))??#CUM_SUM(MEDIAN(bureau.DAYS_CREDIT))??+CUM_SUM(MEDIAN(bureau.DAYS_CREDIT_ENDDATE))??*CUM_SUM(MEDIAN(bureau.DAYS_CREDIT_UPDATE))??)CUM_SUM(MEDIAN(bureau.DAYS_ENDDATE_FACT))??.CUM_SUM(MEDIAN(bureau_balance.MONTHS_BALANCE))??)CUM_SUM(MEDIAN(card_balance.AMT_BALANCE))??5CUM_SUM(MEDIAN(card_balance.AMT_CREDIT_LIMIT_ACTUAL))??6CUM_SUM(MEDIAN(card_balance.AMT_DRAWINGS_ATM_CURRENT))??2CUM_SUM(MEDIAN(card_balance.AMT_DRAWINGS_CURRENT))??8CUM_SUM(MEDIAN(card_balance.AMT_DRAWINGS_OTHER_CURRENT))??6CUM_SUM(MEDIAN(card_balance.AMT_DRAWINGS_POS_CURRENT))??5CUM_SUM(MEDIAN(card_balance.AMT_INST_MIN_REGULARITY))??1CUM_SUM(MEDIAN(card_balance.AMT_PAYMENT_CURRENT))??7CUM_SUM(MEDIAN(card_balance.AMT_PAYMENT_TOTAL_CURRENT))??6CUM_SUM(MEDIAN(card_balance.AMT_RECEIVABLE_PRINCIPAL))??+CUM_SUM(MEDIAN(card_balance.AMT_RECIVABLE))??2CUM_SUM(MEDIAN(card_balance.AMT_TOTAL_RECEIVABLE))??6CUM_SUM(MEDIAN(card_balance.CNT_DRAWINGS_ATM_CURRENT))??2CUM_SUM(MEDIAN(card_balance.CNT_DRAWINGS_CURRENT))??8CUM_SUM(MEDIAN(card_balance.CNT_DRAWINGS_OTHER_CURRENT))??6CUM_SUM(MEDIAN(card_balance.CNT_DRAWINGS_POS_CURRENT))??7CUM_SUM(MEDIAN(card_balance.CNT_INSTALMENT_MATURE_CUM))??,CUM_SUM(MEDIAN(card_balance.MONTHS_BALANCE))??$CUM_SUM(MEDIAN(card_balance.SK_DPD))??(CUM_SUM(MEDIAN(card_balance.SK_DPD_DEF))??,CUM_SUM(MEDIAN(cash_balance.CNT_INSTALMENT))??3CUM_SUM(MEDIAN(cash_balance.CNT_INSTALMENT_FUTURE))??,CUM_SUM(MEDIAN(cash_balance.MONTHS_BALANCE))??$CUM_SUM(MEDIAN(cash_balance.SK_DPD))??(CUM_SUM(MEDIAN(cash_balance.SK_DPD_DEF))??(CUM_SUM(MEDIAN(payments.AMT_INSTALMENT))??%CUM_SUM(MEDIAN(payments.AMT_PAYMENT))??,CUM_SUM(MEDIAN(payments.DAYS_ENTRY_PAYMENT))??)CUM_SUM(MEDIAN(payments.DAYS_INSTALMENT))??/CUM_SUM(MEDIAN(payments.NUM_INSTALMENT_NUMBER))??0CUM_SUM(MEDIAN(payments.NUM_INSTALMENT_VERSION))??%CUM_SUM(MEDIAN(prev_app.AMT_ANNUITY))??)CUM_SUM(MEDIAN(prev_app.AMT_APPLICATION))??$CUM_SUM(MEDIAN(prev_app.AMT_CREDIT))??*CUM_SUM(MEDIAN(prev_app.AMT_DOWN_PAYMENT))??)CUM_SUM(MEDIAN(prev_app.AMT_GOODS_PRICE))??%CUM_SUM(MEDIAN(prev_app.CNT_PAYMENT))??'CUM_SUM(MEDIAN(prev_app.DAYS_DECISION))??,CUM_SUM(MEDIAN(prev_app.DAYS_FIRST_DRAWING))??(CUM_SUM(MEDIAN(prev_app.DAYS_FIRST_DUE))??'CUM_SUM(MEDIAN(prev_app.DAYS_LAST_DUE))??3CUM_SUM(MEDIAN(prev_app.DAYS_LAST_DUE_1ST_VERSION))??*CUM_SUM(MEDIAN(prev_app.DAYS_TERMINATION))??1CUM_SUM(MEDIAN(prev_app.HOUR_APPR_PROCESS_START))??3CUM_SUM(MEDIAN(prev_app.NFLAG_INSURED_ON_APPROVAL))??+CUM_SUM(MEDIAN(prev_app.RATE_DOWN_PAYMENT))??*CUM_SUM(MEDIAN(prev_app.SELLERPLACE_AREA))??PROPORTION_LIFE_EMPLOYED??INCOME_TO_CREDIT_RATIO??INCOME_TO_ANNUITY_RATIO??INCOME_TO_ANNUITY_RATIO_BY_AGE??CREDIT_TO_ANNUITY_RATIO??CREDIT_TO_ANNUITY_RATIO_BY_AGE??INCOME_TO_FAMILYSIZE_RATIO??WEEKDAY_APPR_PROCESS_START_1??WEEKDAY_APPR_PROCESS_START_2??NAME_TYPE_SUITE_Children??NAME_TYPE_SUITE_Family??NAME_TYPE_SUITE_Group of people??NAME_TYPE_SUITE_Other_A??NAME_TYPE_SUITE_Other_B??NAME_TYPE_SUITE_Spouse, partner??NAME_TYPE_SUITE_Unaccompanied??NAME_INCOME_TYPE_Businessman??%NAME_INCOME_TYPE_Commercial associate??NAME_INCOME_TYPE_Pensioner??NAME_INCOME_TYPE_State servant??NAME_INCOME_TYPE_Student??NAME_INCOME_TYPE_Unemployed??NAME_INCOME_TYPE_Working??#NAME_EDUCATION_TYPE_Academic degree??$NAME_EDUCATION_TYPE_Higher education??%NAME_EDUCATION_TYPE_Incomplete higher??#NAME_EDUCATION_TYPE_Lower secondary??1NAME_EDUCATION_TYPE_Secondary / secondary special??!NAME_FAMILY_STATUS_Civil marriage??NAME_FAMILY_STATUS_Married??NAME_FAMILY_STATUS_Separated??'NAME_FAMILY_STATUS_Single / not married??NAME_FAMILY_STATUS_Widow??!NAME_HOUSING_TYPE_Co-op apartment??#NAME_HOUSING_TYPE_House / apartment??%NAME_HOUSING_TYPE_Municipal apartment??"NAME_HOUSING_TYPE_Office apartment??"NAME_HOUSING_TYPE_Rented apartment??NAME_HOUSING_TYPE_With parents??OCCUPATION_TYPE_Accountants??OCCUPATION_TYPE_Cleaning staff??OCCUPATION_TYPE_Cooking staff??OCCUPATION_TYPE_Core staff??OCCUPATION_TYPE_Drivers??OCCUPATION_TYPE_HR staff??%OCCUPATION_TYPE_High skill tech staff??OCCUPATION_TYPE_IT staff??OCCUPATION_TYPE_Laborers??"OCCUPATION_TYPE_Low-skill Laborers??OCCUPATION_TYPE_Managers??OCCUPATION_TYPE_Medicine staff??%OCCUPATION_TYPE_Private service staff??OCCUPATION_TYPE_Realty agents??OCCUPATION_TYPE_Sales staff??OCCUPATION_TYPE_Secretaries??OCCUPATION_TYPE_Security staff??$OCCUPATION_TYPE_Waiters/barmen staff??ORGANIZATION_TYPE_Advertising??ORGANIZATION_TYPE_Agriculture??ORGANIZATION_TYPE_Bank??(ORGANIZATION_TYPE_Business Entity Type 1??(ORGANIZATION_TYPE_Business Entity Type 2??(ORGANIZATION_TYPE_Business Entity Type 3??ORGANIZATION_TYPE_Cleaning??ORGANIZATION_TYPE_Construction??ORGANIZATION_TYPE_Culture??ORGANIZATION_TYPE_Electricity??ORGANIZATION_TYPE_Emergency??ORGANIZATION_TYPE_Government??ORGANIZATION_TYPE_Hotel??ORGANIZATION_TYPE_Housing??"ORGANIZATION_TYPE_Industry: type 1??#ORGANIZATION_TYPE_Industry: type 10??#ORGANIZATION_TYPE_Industry: type 11??#ORGANIZATION_TYPE_Industry: type 12??#ORGANIZATION_TYPE_Industry: type 13??"ORGANIZATION_TYPE_Industry: type 2??"ORGANIZATION_TYPE_Industry: type 3??"ORGANIZATION_TYPE_Industry: type 4??"ORGANIZATION_TYPE_Industry: type 5??"ORGANIZATION_TYPE_Industry: type 6??"ORGANIZATION_TYPE_Industry: type 7??"ORGANIZATION_TYPE_Industry: type 8??"ORGANIZATION_TYPE_Industry: type 9??ORGANIZATION_TYPE_Insurance??ORGANIZATION_TYPE_Kindergarten?? ORGANIZATION_TYPE_Legal Services??ORGANIZATION_TYPE_Medicine??ORGANIZATION_TYPE_Military??ORGANIZATION_TYPE_Mobile??ORGANIZATION_TYPE_Other??ORGANIZATION_TYPE_Police??ORGANIZATION_TYPE_Postal??ORGANIZATION_TYPE_Realtor??ORGANIZATION_TYPE_Religion??ORGANIZATION_TYPE_Restaurant??ORGANIZATION_TYPE_School??ORGANIZATION_TYPE_Security??%ORGANIZATION_TYPE_Security Ministries??ORGANIZATION_TYPE_Self-employed??ORGANIZATION_TYPE_Services??ORGANIZATION_TYPE_Telecom??ORGANIZATION_TYPE_Trade: type 1??ORGANIZATION_TYPE_Trade: type 2??ORGANIZATION_TYPE_Trade: type 3??ORGANIZATION_TYPE_Trade: type 4??ORGANIZATION_TYPE_Trade: type 5??ORGANIZATION_TYPE_Trade: type 6??ORGANIZATION_TYPE_Trade: type 7??#ORGANIZATION_TYPE_Transport: type 1??#ORGANIZATION_TYPE_Transport: type 2??#ORGANIZATION_TYPE_Transport: type 3??#ORGANIZATION_TYPE_Transport: type 4??ORGANIZATION_TYPE_University??ORGANIZATION_TYPE_XNA?? FONDKAPREMONT_MODE_not specified??#FONDKAPREMONT_MODE_org spec account??#FONDKAPREMONT_MODE_reg oper account??(FONDKAPREMONT_MODE_reg oper spec account??HOUSETYPE_MODE_block of flats??HOUSETYPE_MODE_specific housing??HOUSETYPE_MODE_terraced house??WALLSMATERIAL_MODE_Block??WALLSMATERIAL_MODE_Mixed??WALLSMATERIAL_MODE_Monolithic??WALLSMATERIAL_MODE_Others??WALLSMATERIAL_MODE_Panel??WALLSMATERIAL_MODE_Stone, brick??WALLSMATERIAL_MODE_Wooden?et?b?n_features_in_?M?
indicator_?N?statistics_?hhK ??h ??R?(KM??h%?f8?????R?(K?<?NNNJ????J????K t?b?B                                 ??             ?A    ?OA    ?P?@    @wAvOjM??     ???     ???     ???     h??      "@       @       @       @      (@?Ue?{0???]?V???Zè? ??w-!?l??????ׁ??~8gDi????0?*??^K?=???        ?'????-!?lV?????????_)?Ǻ???ݓ??Z???	???        ??H?}m?/?$????O??n??~8gDi???b?=y????~j?t??        ?'????-!?lV?????????9??m4??????ZӼ??46<???        /n??R?V????_????N@a??~8gDi????ʡE????_?L??        ?'????-!?lV??????????HP?????9#J{??D????9??        ?~j?t?h?"??u????      ??                                     ???                                              ??      ??      ??              ??                                                                              ??                                                                                                                                                      @     î@            ?< A                                              ??      q?     ?v?     X??             ?4?      @R????@    8y?@    ?<?@     ??@    ܻ?@      (@     @??    ?JA      ??     ?|?     `t?     ?y?      *@        i,??.???     ?=@      5@      (@      @      8?                      7@????B?@H?z.??@     <??     ???      @      ??                    ?9A                                             ڶ@???Q???                                                              @      (?                  @?}?A  ?"Dm5B ?^?{=3B v??+B     Ќ@     Ȋ@    @^?@    ??@     ??@    ??A??ĐQ?@?$(?_?@#?D|??@???1??@?ŏ???@^?I?˵@    `_?@    ?6A??h ?!?@J?????@?	h???@   ?zW??  ??Rݱ?  ?&?j??   ????  ?????    ?c?@    ???@5?Dذ??@+?Q???@\>?c??@էq?Z?@?;x?E?@&<x[??@a?z?rg?@?nA;?@<?`????@?g oi??@?????@???????@xI?z?M?@\/?dH?@L???1??@   ??H<A???/"?@s?`TrU?@N??h??@D?2???@nl???J?@@/????@a=?U7?@]m?>.?@@????@@?ݓ.z@?Q???y@J@????w@X߾W?@]?C?9?@???(??@    \?
A    ?]
A    21#A?l??a?@    ?AA    ?A    ?{?@???|¿@?? ???@??L????@V???)??@??????@6?W[???@v镲N?@        tR???A?xIt???A???܏?QB_??^?L7B?C???AS??3?A     v?@    ?|%A   a?.??  @>?Z?A   ??Z??  ?S-g??      1?                    ???@                                             ??     ???     ???     ???N?
s?3Bw?t?$?@B?lբ??BBx?+D0?Ax,c?y?@B   @??cA   ә??? ?k?2?CB  ?z???A ??(??!B  ??*KB ??F??"B   ?(?cA    ?"A??a#?@   ?׮A   ??@?A   8?ۈA   ??Ӥ?   XK?A   ??<GAUi3b?:B??#?:7;B  ?????  ??\??   @???A   ?$'VA??ԔS?9B ??QB??#Bx??? ?
B??̃n¹A?=???(?A+???$?A?ɍ?>SB?c???B#j?6y?8B#[B?9BGRd??9B    ??A   ??_4A     ??@    ?*A   놁A   L????   ?
 qA    ??A    ?U&A   ??\A    ??8A    ?:PA   `MVA    ?u%AtA ??.?A?p?e?b?A??괠 BW?Q!&B?"{BŚ?A533???RA     0u@    `??@   4????   ???dA   ?f???   6??    ??.?????A  ???BB{?	z?A3
7??p?A   @6/A^?o?AN??S7?A63?????AW3??c??A?]6??Ah??~??A?G????A     ڹ@    ?o?@     ?3@    ???@    |?A    d?)?    ?+?@    ?j?@   @@@A    ??2A   ??$Q?    ??A    `??@)?Rb??At\o!?'?A   >???   Z????   ??53A    ?g A??
7?-?A?[?
?B??wͲB?p??c??A5{y?
NB   ?:L>A   ??v??  ????'B  ?s???A  ??& B  ???E?A  ???B    k?;A    `m?@?????V?@   ?W??A?|?x?S??k?????ܶm۶?@?|?x@??      4@Ygs??    ?O?@?E??{̿ëqM????                                                      ??                                                      ??                                      ??              ??                                      ??                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ?t?b?_sklearn_version??1.0.1?ub???scaler??sklearn.preprocessing._data??RobustScaler???)??}?(?with_centering???with_scaling???quantile_range?G@9      G@R?     ???unit_variance??h?j1  M?center_?hhK ??h ??R?(KM??j:  ?B                                 ??             ?A    ?OA    ?P?@    @wAvOjM??     ???     ???     ???     h??      "@       @       @       @      (@?Ue?{0???]?V???Zè? ??w-!?l??????ׁ??~8gDi????0?*??^K?=???        ?'????-!?lV?????????_)?Ǻ???ݓ??Z???	???        ??H?}m?/?$????O??n??~8gDi???b?=y????~j?t??        ?'????-!?lV?????????9??m4??????ZӼ??46<???        /n??R?V????_????N@a??~8gDi????ʡE????_?L??        ?'????-!?lV??????????HP?????9#J{??D????9??        ?~j?t?h?"??u????      ??                                     ???                                              ??      ??      ??              ??                                                                              ??                                                                                                                                                      @     î@            ?< A                                              ??      q?     ?v?     X??             ?4?      @R????@    8y?@    ?<?@     ??@    ܻ?@      (@     @??    ?JA      ??     ?|?     `t?     ?y?      *@        i,??.???     ?=@      5@      (@      @      8?                      7@????B?@H?z.??@     <??     ???      @      ??                    ?9A                                             ڶ@???Q???                                                              @      (?                  @?}?A  ?"Dm5B ?^?{=3B v??+B     Ќ@     Ȋ@    @^?@    ??@     ??@    ??A??ĐQ?@?$(?_?@#?D|??@???1??@?ŏ???@^?I?˵@    `_?@    ?6A??h ?!?@J?????@?	h???@   ?zW??  ??Rݱ?  ?&?j??   ????  ?????    ?c?@    ???@5?Dذ??@+?Q???@\>?c??@էq?Z?@?;x?E?@&<x[??@a?z?rg?@?nA;?@<?`????@?g oi??@?????@???????@xI?z?M?@\/?dH?@L???1??@   ??H<A???/"?@s?`TrU?@N??h??@D?2???@nl???J?@@/????@a=?U7?@]m?>.?@@????@@?ݓ.z@?Q???y@J@????w@X߾W?@]?C?9?@???(??@    \?
A    ?]
A    21#A?l??a?@    ?AA    ?A    ?{?@???|¿@?? ???@??L????@V???)??@??????@6?W[???@v镲N?@        tR???A?xIt???A???܏?QB_??^?L7B?C???AS??3?A     v?@    ?|%A   a?.??  @>?Z?A   ??Z??  ?S-g??      1?                    ???@                                             ??     ???     ???     ???N?
s?3Bw?t?$?@B?lբ??BBx?+D0?Ax,c?y?@B   @??cA   ә??? ?k?2?CB  ?z???A ??(??!B  ??*KB ??F??"B   ?(?cA    ?"A??a#?@   ?׮A   ??@?A   8?ۈA   ??Ӥ?   XK?A   ??<GAUi3b?:B??#?:7;B  ?????  ??\??   @???A   ?$'VA??ԔS?9B ??QB??#Bx??? ?
B??̃n¹A?=???(?A+???$?A?ɍ?>SB?c???B#j?6y?8B#[B?9BGRd??9B    ??A   ??_4A     ??@    ?*A   놁A   L????   ?
 qA    ??A    ?U&A   ??\A    ??8A    ?:PA   `MVA    ?u%AtA ??.?A?p?e?b?A??괠 BW?Q!&B?"{BŚ?A533???RA     0u@    `??@   4????   ???dA   ?f???   6??    ??.?????A  ???BB{?	z?A3
7??p?A   @6/A^?o?AN??S7?A63?????AW3??c??A?]6??Ah??~??A?G????A     ڹ@    ?o?@     ?3@    ???@    |?A    d?)?    ?+?@    ?j?@   @@@A    ??2A   ??$Q?    ??A    `??@)?Rb??At\o!?'?A   >???   Z????   ??53A    ?g A??
7?-?A?[?
?B??wͲB?p??c??A5{y?
NB   ?:L>A   ??v??  ????'B  ?s???A  ??& B  ???E?A  ???B    k?;A    `m?@?????V?@   ?W??A?|?x?S??k?????ܶm۶?@?|?x@??      4@Ygs??    ?O?@?E??{̿ëqM????                                                      ??                                                      ??                                      ??              ??                                      ??                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ?t?b?scale_?hhK ??h ??R?(KM??j:  ?B         ??      ??      ??      ??      ??     ??@    4p A    ???@    ??A֪]???     q?@     h?@     d?@    ?$?@      ??      ??      ??      ??      @      ?????L????9?@??      ??      ?? ???Mb@?      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ?? ???Mb@?      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ?? C??6j?      ??       @      ??       @      ??     <?@      ??      ??      ??      ??      ??       @      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      @      ??      ??    ?fA    ??@      ??      ??      ??      ??     ??@     8?@     ?@      ~@      =@      ??      @ףp???@    ?<?@    x??@     }?@    ?3?@      @     (?@      ??     d?@     ??@     ??@     ?@      @      ????????     @Y@      ;@       @      @      <@      ??      ??     ?B@????'?@֣p=???@     ??@     ??@      @      ??      @      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??  `???A ??<y5B ????B3B??P6?'B     (?@     ??@    ???@    ???@     ??@    l?	A      ??      ??      ??      ??      ??      ??    hY?@    ?9A      ??      ??      ??  8??d?A  ??$??A  ?1?t?A   \¬?A  ?????A    ???@    ?.?@      ??      ??      ??      ??      ??      ??      ???흜?>?@?h$tX#?@ ????0`@ k+v3`@ ,_??_@      ??      ??      ??    ?[<A      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??    x?
A    ?>
A      ?????S?@    XIA    ?A    ???@?????@???ۀ?@????8?@?s?j??@      ??      ??      ??      "@      ??|?m?7?A?*=?DUMB??5?U2B??R?t6?A?Q?fvltA     ٱ@    ??"A  p??B?A  `A??A  ?%?<?A   ????A      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ????_D?-B\z?{L@Bw?5)??ABr?̡J??A?KSr	@B   ??bA  ?$t??A ??;ҩBB  ??A??A ?:?? B  ?~B ?????!B   \??bA    .A??ˌ\X?@  ?%X?A  ? ?A   ?Al?A  ?h՚?A   !Y?A   ??zBA]u?W?9Bx+????9B  ??Z;?A  ??K?A  ?QZ??A   `?UA      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??    ^R&A    ??[A    ??8A    -VPA   ?v*VA   ??%A      ????*??A?`????BH????I B/???AK?z??+FA     @q@     ??@  ?	(u?A    	/aA   ???A   ??J?A      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??    ??>A   `]?1A   @fPA    ?>A     ?@~f(	J-?A\?V???A  ?U\?A   ???A   ?6:2A    ??@??b?|??A?M???VBw???8-B?{@?֢?A?ҏW?B   ?P?<A  ?I,ܛA  ?0??&B  ?&׽A  ??jF?A  8?G??A  ?S? B   ?3s:A    ?g?@_??'???@   ??A,????@???~???L??r????b@/cm?z?@??Q???&@?[ 4kA    @??@"?+?.d??Z?͑s??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ??      ???t?bj?  j@  ub??e?memory?Nh?j?  j@  ub???	regressor??lightgbm.sklearn??LGBMClassifier???)??}?(?boosting_type??gbdt??	objective?N?
num_leaves?K?	max_depth?K?learning_rate?h?scalar???j:  C??k?tD?????R??n_estimators?KȌsubsample_for_bin?J@ ?min_split_gain?G        ?min_child_weight?G?PbM?????min_child_samples?K?	subsample?jk  j:  C???????????R??subsample_freq?K ?colsample_bytree?jk  j:  Cgfffff?????R??	reg_alpha?jk  j:  C433333?????R??
reg_lambda?jk  j:  C???????????R??random_state?N?n_jobs?J?????silent??warn??importance_type??split??_Booster??lightgbm.basic??Booster???)??}?(?handle?X?X
 tree
version=v3
num_class=1
num_tree_per_iteration=1
label_index=0
max_feature_idx=515
objective=binary sigmoid:1
feature_names=Column_0 Column_1 Column_2 Column_3 Column_4 Column_5 Column_6 Column_7 Column_8 Column_9 Column_10 Column_11 Column_12 Column_13 Column_14 Column_15 Column_16 Column_17 Column_18 Column_19 Column_20 Column_21 Column_22 Column_23 Column_24 Column_25 Column_26 Column_27 Column_28 Column_29 Column_30 Column_31 Column_32 Column_33 Column_34 Column_35 Column_36 Column_37 Column_38 Column_39 Column_40 Column_41 Column_42 Column_43 Column_44 Column_45 Column_46 Column_47 Column_48 Column_49 Column_50 Column_51 Column_52 Column_53 Column_54 Column_55 Column_56 Column_57 Column_58 Column_59 Column_60 Column_61 Column_62 Column_63 Column_64 Column_65 Column_66 Column_67 Column_68 Column_69 Column_70 Column_71 Column_72 Column_73 Column_74 Column_75 Column_76 Column_77 Column_78 Column_79 Column_80 Column_81 Column_82 Column_83 Column_84 Column_85 Column_86 Column_87 Column_88 Column_89 Column_90 Column_91 Column_92 Column_93 Column_94 Column_95 Column_96 Column_97 Column_98 Column_99 Column_100 Column_101 Column_102 Column_103 Column_104 Column_105 Column_106 Column_107 Column_108 Column_109 Column_110 Column_111 Column_112 Column_113 Column_114 Column_115 Column_116 Column_117 Column_118 Column_119 Column_120 Column_121 Column_122 Column_123 Column_124 Column_125 Column_126 Column_127 Column_128 Column_129 Column_130 Column_131 Column_132 Column_133 Column_134 Column_135 Column_136 Column_137 Column_138 Column_139 Column_140 Column_141 Column_142 Column_143 Column_144 Column_145 Column_146 Column_147 Column_148 Column_149 Column_150 Column_151 Column_152 Column_153 Column_154 Column_155 Column_156 Column_157 Column_158 Column_159 Column_160 Column_161 Column_162 Column_163 Column_164 Column_165 Column_166 Column_167 Column_168 Column_169 Column_170 Column_171 Column_172 Column_173 Column_174 Column_175 Column_176 Column_177 Column_178 Column_179 Column_180 Column_181 Column_182 Column_183 Column_184 Column_185 Column_186 Column_187 Column_188 Column_189 Column_190 Column_191 Column_192 Column_193 Column_194 Column_195 Column_196 Column_197 Column_198 Column_199 Column_200 Column_201 Column_202 Column_203 Column_204 Column_205 Column_206 Column_207 Column_208 Column_209 Column_210 Column_211 Column_212 Column_213 Column_214 Column_215 Column_216 Column_217 Column_218 Column_219 Column_220 Column_221 Column_222 Column_223 Column_224 Column_225 Column_226 Column_227 Column_228 Column_229 Column_230 Column_231 Column_232 Column_233 Column_234 Column_235 Column_236 Column_237 Column_238 Column_239 Column_240 Column_241 Column_242 Column_243 Column_244 Column_245 Column_246 Column_247 Column_248 Column_249 Column_250 Column_251 Column_252 Column_253 Column_254 Column_255 Column_256 Column_257 Column_258 Column_259 Column_260 Column_261 Column_262 Column_263 Column_264 Column_265 Column_266 Column_267 Column_268 Column_269 Column_270 Column_271 Column_272 Column_273 Column_274 Column_275 Column_276 Column_277 Column_278 Column_279 Column_280 Column_281 Column_282 Column_283 Column_284 Column_285 Column_286 Column_287 Column_288 Column_289 Column_290 Column_291 Column_292 Column_293 Column_294 Column_295 Column_296 Column_297 Column_298 Column_299 Column_300 Column_301 Column_302 Column_303 Column_304 Column_305 Column_306 Column_307 Column_308 Column_309 Column_310 Column_311 Column_312 Column_313 Column_314 Column_315 Column_316 Column_317 Column_318 Column_319 Column_320 Column_321 Column_322 Column_323 Column_324 Column_325 Column_326 Column_327 Column_328 Column_329 Column_330 Column_331 Column_332 Column_333 Column_334 Column_335 Column_336 Column_337 Column_338 Column_339 Column_340 Column_341 Column_342 Column_343 Column_344 Column_345 Column_346 Column_347 Column_348 Column_349 Column_350 Column_351 Column_352 Column_353 Column_354 Column_355 Column_356 Column_357 Column_358 Column_359 Column_360 Column_361 Column_362 Column_363 Column_364 Column_365 Column_366 Column_367 Column_368 Column_369 Column_370 Column_371 Column_372 Column_373 Column_374 Column_375 Column_376 Column_377 Column_378 Column_379 Column_380 Column_381 Column_382 Column_383 Column_384 Column_385 Column_386 Column_387 Column_388 Column_389 Column_390 Column_391 Column_392 Column_393 Column_394 Column_395 Column_396 Column_397 Column_398 Column_399 Column_400 Column_401 Column_402 Column_403 Column_404 Column_405 Column_406 Column_407 Column_408 Column_409 Column_410 Column_411 Column_412 Column_413 Column_414 Column_415 Column_416 Column_417 Column_418 Column_419 Column_420 Column_421 Column_422 Column_423 Column_424 Column_425 Column_426 Column_427 Column_428 Column_429 Column_430 Column_431 Column_432 Column_433 Column_434 Column_435 Column_436 Column_437 Column_438 Column_439 Column_440 Column_441 Column_442 Column_443 Column_444 Column_445 Column_446 Column_447 Column_448 Column_449 Column_450 Column_451 Column_452 Column_453 Column_454 Column_455 Column_456 Column_457 Column_458 Column_459 Column_460 Column_461 Column_462 Column_463 Column_464 Column_465 Column_466 Column_467 Column_468 Column_469 Column_470 Column_471 Column_472 Column_473 Column_474 Column_475 Column_476 Column_477 Column_478 Column_479 Column_480 Column_481 Column_482 Column_483 Column_484 Column_485 Column_486 Column_487 Column_488 Column_489 Column_490 Column_491 Column_492 Column_493 Column_494 Column_495 Column_496 Column_497 Column_498 Column_499 Column_500 Column_501 Column_502 Column_503 Column_504 Column_505 Column_506 Column_507 Column_508 Column_509 Column_510 Column_511 Column_512 Column_513 Column_514 Column_515
feature_infos=[0:1] [0:1] [0:1] [-1:0] [0:19] [-1.3149999999999999:198.40100000000001] [-0.86883040935672518:6.5664243943191307] [-1.2664054238974933:12.889469428375941] [-0.9285714285714286:8.1632653061224492] [-0.99480087902663883:2.8760250844187172] [-1.3005081719544018:1.1106990797967313] [-8.9471947194719466:0.90539053905390543] [-3.5109569028487946:0.82395909422936453] [-1.5301076311451567:1.2613206632405702] [-9:82] [-1:18] [-1:1] [-1:1] [-3:2.75] [-0.49135025378583674:0.45677438436302353] [-2.0945591351953099:1.0683471174532559] [-2.438697162363086:1.645106951088678] [-0.087599999999999997:0.91239999999999999] [-0.076200000000000004:0.92379999999999995] [-1963.2000000002163:36.800000000003998] [-0.75519999999999998:0.24480000000000002] [-0.021100000000000001:0.97889999999999999] [0:1] [-0.13789999999999999:0.86209999999999998] [-0.16669999999999999:0.83330000000000004] [-0.20830000000000001:0.79169999999999996] [-0.048300000000000003:0.95169999999999999] [-0.075600000000000001:0.9244] [-0.074700000000000003:0.92530000000000001] [0:1] [-0.0035999999999999999:0.99639999999999995] [-0.084000000000000005:0.91600000000000004] [-0.074499999999999997:0.92549999999999999] [-0.98160000000000003:0.018399999999999972] [-0.76480000000000004:0.23519999999999996] [-0.019:0.98099999999999998] [0:1] [-0.13789999999999999:0.86209999999999998] [-0.16669999999999999:0.83330000000000004] [-0.20830000000000001:0.79169999999999996] [-0.045900000000000003:0.95409999999999995] [-0.077100000000000002:0.92290000000000005] [-0.073200000000000001:0.92679999999999996] [0:1] [-0.0011000000000000001:0.99890000000000001] [-0.087400000000000005:0.91259999999999997] [-0.075700000000000003:0.92430000000000001] [-1963.2000000002163:36.800000000003998] [-0.75849999999999995:0.24150000000000005] [-0.020799999999999999:0.97919999999999996] [0:1] [-0.13789999999999999:0.86209999999999998] [-0.16669999999999999:0.83330000000000004] [-0.20830000000000001:0.79169999999999996] [-0.048800000000000003:0.95120000000000005] [-0.076100000000000001:0.92389999999999994] [-0.0751:0.92490000000000006] [0:1] [-0.0030000000000000001:0.997] [-21.500000000000036:291.00000000000051] [0:1] [0:174] [0:34] [0:172] [0:24] [-2.6463320463320463:0.58532818532818531] [0:3] [0:9] [0:8] [0:27] [0:8] [-0.5:10.5] none [-1:0] [0:1] [-1:0] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] none [-1:0] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] none [0:1] none [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [-0.66666666666666663:18.666666666666668] [-3937.5:27278491.252500001] [0:115987185] [-0.93313288192307087:1388.5290102119734] [-119.49792692760994:4813.5971713913532] [-34173.404999999999:2207250] [0:1617403.5] [0:6] [0:2644] [-2.823021582733813:1.3812949640287771] [-49.56615017878427:37.508939213349223] [-37.617001828153562:0.6882998171846435] [-4.1742738589211621:1.8153526970954357] [0:91.620689655172413] [-72:20.5] [-0.75:17.5] [-1.1337853165504068:32.325453024146846] [-0.91284786547505137:47.946092302681137] [-0.89149687847843972:42.664617916081887] [-0.37244827586206897:309.97241379310344] [-0.91248094818392977:34.147730094808651] [-2:10] [-2.941785252263907:0.83570504527813716] [-368165:0] [-2.5735384615384613:450.51446153846155] [-2.8527679623085982:430.74676089517078] [-3.0036452004860266:444.19076549210206] [-2.9220623501199041:438.43884892086334] [-3.7142857142857144:2.8571428571428572] [0:2] [-0.51475507081202776:8.8390320355192848] [-0.30198019801980197:39603.668316831681] [-0.77777777777777779:8.3333333333333339] [-1.375:7.5] [-1.4444444444444444:11.888888888888889] [-2.5714285714285716:0.8214285714285714] [0:2695.5] [0:1685] [-0.6216216216216216:9.4324324324324316] [-1.0645982783357244:259.84164787866359] [-1.049566675325289:266.15268561592984] [-2.6194240542066627:0.7639751552795031] [-2.5411499436302143:0.74971815107102591] [-1.25:34.125] [-1:38] [0:18] [0:948466.10250000004] [-157500:1192500] [0:675000] [0:1125000] [0:133650] [0:900000] [0:46857.442500000012] [-5850:1119150] [-0.58499999999999996:1124999.415] [0:899653.94999999995] [0:939918.39749999996] [0:939918.39749999996] [0:35] [0:116.5] [0:2] [0:116.5] [-4:69.5] [-42.5:11] [0:1326.5] [0:1250] [-0.99741160670854045:0.99865441588096049] [-0.99784609810221936:0.99944207493482862] [-0.99891491212997452:1.0005748533005454] [-1.0006604348496382:1.0005749009087861] [-1.1453416149068323:1.1677018633540373] [-1.1820689655172414:1.1668965517241379] [-1.1998043613917326:1.199197207090213] [-1.186050448620281:1.204773996952768] [-1.1473442288049029:1.1866700715015321] [-1.1775974445397002:1.196359408580052] [-8867.0104000000774:8918.7811000022266] [-8895.1450500001429:8952.6476499989749] [-8622.8532500011534:8676.8550499969442] [-5639.7468999999974:5642.1948000000912] [-5605.8538000000071:5613.9158000000889] [-5579.7683999999681:5587.4727000000876] [-1.0007437318204297:0.99663179044674532] [-0.99936703178647168:0.99816597648738103] [-2064.8607499999985:2068.9818500001238] [-2062.7456000000202:2068.7233999999971] [-1967.3445000000283:1974.9558000000675] [-1.0003957126330292:0.99721290051415845] [-1.2881621902325588:1.2810094072076745] [-1.0001715453068014:0.99856760472037276] [-1.0004933386867274:0.99642878797760615] [-1.0003974923901255:0.99618224164213287] [-0.99027809179290072:0.99701560027130909] [-0.98615155633210383:0.99767035527082115] [-5612.6107999984006:5724.4892000007667] [-5549.0399999982883:5664.0200000006762] [-5294.0302999993555:5403.7021999979461] [-11445.306199994993:11414.450300014598] [-11403.798599994749:11377.801100014802] [-11100.611099995012:11067.184300013094] [-33595.196574683541:33752.235185040678] [-0.99930119681300666:1.0030104116484] [-1.3255410534693275:1.3322546276720342] [-134.37389365693329:135.50310230536184] [-134.09611932251431:135.1560455195339] [-134.2181573698297:135.29176121937206] [-11418.764200000833:11507.2725999951] [-11408.329700000808:11491.154599994694] [-11233.92920000079:11312.944199994952] [-0.99737881421138441:0.99855179686953532] [-4130.1370500000248:4156.0714500001486] [-4181.3959000000132:4209.1887000000652] [-4045.1536000000092:4069.2221000002219] [-4882.8781499999823:4923.4502500007402] [-4938.6973500011181:4982.4253500010418] [-5117.9287500005112:5162.2979499991325] [-8196.3584000001629:8252.4849999995877] [-8284.4153000000206:8349.3941999996787] [-8086.0070999999507:8144.7204999997557] [-418.87294999990235:409.10805000027335] [-412.22234999989092:400.93915000015488] [-383.18479999993417:375.9675000000791] [-1941.7675999999826:1966.7318000001424] [-1934.421900000028:1957.2845000001319] [-1851.2896000000023:1873.1569000001541] [-1.0046763763713158:0.99856836241801983] [-1.0045835716976657:0.99849539782425689] [-628838:632455] [-0.99875583076081054:0.99954483171354724] [-0.9984983702015886:0.99880850659831011] [-0.9985595339348865:0.99887288726314649] [-0.99896389575197253:0.97935761536622301] [-15.157324503158751:15.255574433384398] [-22.253854501353409:22.287100446634618] [-22.25847641875772:22.291528823017654] [-22.250655049077952:22.28611797231121] [-38699.493200000448:38817.676799995825] [-38868.994400001007:38985.541900005599] [-39073.021199999217:39182.349200007215] [0:10.777777777777779] [-3963562156.2600651:3729909317.7330322] [-3.3191097699757903:3.7039080447998818] [-1.2026536894218938:1.2155512529290304] [-1.2708975841305965:1.2688480271289273] [-1.3588553273747859:1.3580226565922189] [-1.5863423221592472:1.4522820749688947] [-1.2024513022543226:1.2055154300722259] [-1.1774775362355197:1.1710356660863632] [-1.205341075876865:1.2027923432863712] [-1.2170176687034682:1.2322450293100569] [-1.2042001891532612:1.2027931785753527] [-1.5132464124685592:1.510847748684425] [-75.5:17] [0:54562657.5] [0:115987185] [-121500:35032500] [-152983.035:33902743.5] [-1747.0350000000001:1755000] [0:121653] [0:6] [0:2592] [-1701:1219] [-2298:31690] [-2351:530] [-1903:989] [-1.0562516382271885:1.0656822373650416] [-1.0538859405904553:1.0651064122064411] [-1.0540886451508062:1.0649416022087281] [-1.1336067071998788:1.1491824188717732] [-1.0581469243274013:1.0695197814024102] [-1.0557174152612698:1.0644121815958474] [-1.0615386355988836:1.0556755627164216] [-1.0626507459323196:1.0658301759520015] [-1.0710382932471145:1.0730628734760848] [-1.0625813073503181:1.0677937343420603] [-1.0610664206714679:1.0655026237107426] [-1.0613657188631025:1.066700917087972] [-1.0551709980853834:1.0628595826296001] [-1.0579566063058916:1.0690399413763412] [-1.1397798109936261:1.1461318219672285] [-1.0510498087964304:1.0791687442064613] [-1.0604655209090408:1.067730180400895] [-1.0612908791188416:1.0676836502772886] [-1.0668876772386844:1.0623688038209329] [-1.0283411217273606:1.0725136414246781] [-1.257368350598149:1.4449040161428874] [-1.0532841208868167:1.0598790267621114] [-1.053244295896391:1.0595553111679039] [-1.0576097888594522:1.0533386065823711] [-1.0576380219878561:1.0533367553711903] [-1.054669891308283:1.0574412072689863] [-1.0496486640685163:1.0569404515171237] [-111020315860.82663:112868386921.22842] [-292937622750:297719930250] [-9155235477.8700047:9266116689.4049854] [-14231280446.999741:14315069378.248928] [-431964744.30000001:458414266.00500017] [-4605186744.9451027:4568992272.089941] [-6212382544.9350996:6302417623.920022] [-15741335931.143427:15840334865.008255] [-14526568499.173769:14616989629.828844] [-106560042694.4146:108364364617.1971] [-110612333147.13696:112464758630.0531] [-110627284050.27753:112486192041.22415] [-473211.5:483051.5] [-1335240.5:1365043.5] [-7353:7515] [-853448.5:875456.5] [-36756834.25:36861364.75] [-66180732.5:66394016] [-17957032.5:17695146.5] [-501486.5:772045.5] [-1.0005475507868735:1.002732285262339] [-1.004032061859617:1.0025813057746549] [-0.99875795251104216:1.0008598313788895] [-0.99346113575376149:1.0013706793245516] [-0.99326723489040925:1.0015398015842027] [-0.9945087368397606:1.0047424063336741] [-543000708.25199747:513323621.82000375] [-3.6089046069758064:4.8430829062963756] [-1.1890195300521629:1.2088818381920861] [-1.2370384755279358:1.2389252089043561] [-1.349915325535668:1.3084046514051118] [-1.6790611576023291:0.31419980517067547] [-1.2282608695652173:1.269927536231884] [-1.3028172488652063:1.0221531478192225] [-1.1991580561628319:1.2022898133187307] [-1.1966711343095549:1.2354581553907245] [-1.1991160800985268:1.2036867432628062] [-1.5062468457229088:1.5054185556365358] [-1005895.5:1006103.5] [-2929223224.0349927:2985123627.562469] [-9266609250:9425871000] [-98469570.420000002:100132249.90499999] [-221800689.60749969:225508406.35499796] [-1022729.625:925378.1100000001] [-127649537.28000018:128775625.58250064] [-152807934.05999988:155887207.89749879] [-317026408.23000014:318441231.60749793] [-226439678.47500107:231931436.19749817] [-2822572466.9325013:2877250964.512527] [-2911105213.8300056:2966601438.6074924] [-2911231474.2450056:2966718360.9374933] [-6618:6745] [-39806:40907.5] [-19.5:24.5] [-34575:35665.5] [-483615:486604.5] [-847059.5:848942.5] [-90815.5:86548.5] [-4202.5:2552.5] [-1.0642418503787501:1.0678794495632882] [-1.0630705998790642:1.068419846795106] [-1.0661620358133024:1.0654127941227021] [-1.0266579595274845:1.0372230200032708] [-1.5910894941634242:1.3336186770428016] [-1.0592146340785806:1.0631510226772447] [-1.0579199123594194:1.0628338394344174] [-1.0562426168177084:1.0573686681016177] [-1.0562364293793784:1.0573280603942781] [-1.053853399086079:1.0583337440525502] [-1.0544928127550059:1.0549439771514657] [-1.0588198454737787:1.0614009638786825] [-1.0512639349693793:1.0573824609825688] [-1.0515187213500337:1.0578537301629243] [-1.1405603045723356:1.1337479356043441] [-1.0613629797947115:1.0668721826995207] [-1.0572185721021257:1.0634197976515052] [-1.0584656327523905:1.0575703152825049] [-1.0633473789981298:1.064843706154472] [-1.0721070978780405:1.0300421528586241] [-1.0669225132075641:1.056355572110061] [-1.0586563710181816:1.0425627895041654] [-1.0604334779973048:1.0560841044655225] [-1.0564334163913092:1.0591846126843187] [-1.0622814197484931:1.0753627502046283] [-1.1411270074426949:1.1434663464942252] [-1.0793998894384365:1.0492506992237853] [-0.97036478836219187:4.9995350861619858] [-0.97832043247456102:87.412630693504838] [-1.2896144310856941:67.608492140929172] [-53.362606202504594:1.1453417731331066] [-1.0437197331370769:2.2076980041245844] [-3.1334249258624434:1.0891328599349042] [-1.1063218390804597:102.29885057471265] [-0.44504186791262879:0.80193773580483807] [-1.1588336036970479:0.44504186791262884] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [-1:0] none [0:1] [0:1] [0:1] none [0:1] [-1:0] [0:1] [0:1] [0:1] [0:1] [-1:0] [0:1] [-1:0] [0:1] [0:1] [0:1] [0:1] [-1:0] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] none [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1] [0:1]
tree_sizes=3132 3249 3228 3216 3232 3262 3244 3250 3248 3231 3251 3225 3231 3236 3232 3227 3248 3250 3272 3248 3254 3235 3263 3241 3250 3248 3254 3261 3259 3259 3264 3267 3235 3249 3258 3277 3265 3234 3259 3269 3254 3256 3254 3276 3268 3266 3283 3285 3274 3269 3255 3269 3262 3281 3257 3263 3267 3274 3259 3266 3273 3279 3280 3277 3279 3254 3278 3283 3271 3281 3271 3280 3256 3262 3271 3271 3274 3270 3245 3286 3264 3281 3285 3278 3282 3269 3302 3259 3283 3270 3277 3295 3295 3291 3271 3273 3256 3286 3287 3282 3264 3286 3285 3249 3269 3252 3274 3252 3282 3277 3250 3263 3282 3288 3292 3284 3280 3278 3272 3281 3270 3267 3285 3282 3276 3291 3286 3266 3282 3281 3253 3309 3273 3283 3250 3286 3298 3280 3257 3245 3288 3289 3273 3249 3280 3284 3277 3276 3280 3286 3285 3275 3253 3286 3277 3244 3287 3269 3299 3282 3284 3287 3282 3293 3290 3277 3252 3279 3273 3275 3296 3303 3277 3277 3298 3280 3293 3276 3267 3284 3293 3295 3278 3286 3290 3263 3274 3287 3276 3281 3291 3284 3289 3291 3268 3220 3277 3278 3286 3275

Tree=0
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 20 20 10 19 19 21 164 1 1 19 19 119 21 10 411 20 20 21 141 411
split_gain=4462.68 2813.03 1268.01 876.617 727.651 530.818 449.257 281.851 274.156 212.15 199.504 198.967 195.3 155.806 154.85 148.059 134.056 114.934 112.088 107.381 103.226 104.748 102.839 98.0849 97.7929 88.5096 80.0926
threshold=-1.2291473454499886 -0.78572725661621623 -0.66331481234292167 1.0000000180025095e-35 1.0000000180025095e-35 -1.6199246107459455 0.18151951921313889 -1.6199246107459455 0.26791529036287415 -0.55809641532756482 -0.31528071226839544 0.026287426246023041 -1.811377762099047 36029.92500000001 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 -0.26283576276536469 0.77145411203814074 -1.7794007366397382 -0.16446916632330721 1.0000000180025095e-35 -2.0097992159524432 0.046583211681296859 -1.6137283389819139 -0.12962962962962959 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 7 5 6 14 10 24 12 -7 -3 25 -4 16 -2 -5 20 -8 -14 -9 -12 -22 -16 -6 -1 26 -11
right_child=1 4 8 15 23 9 17 19 -10 11 13 -13 18 -15 22 -17 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=-2.3657791799595485 -2.4125469375374471 -2.4181981344431742 -2.4059404953960568 -2.4392038838277976 -2.4430916441988826 -2.4345205220453292 -2.4289589448982909 -2.390915280833092 -2.4313354177061002 -2.4111954623376737 -2.4390889436048915 -2.4378393429587439 -2.4260095507349351 -2.4263482986814768 -2.3679574294017742 -2.4282774948060051 -2.4428057716134268 -2.4431427228753186 -2.411561035462491 -2.4070887343211749 -2.4304504433805674 -2.4397206629474217 -2.3997229115156968 -2.4471710546478072 -2.3917690258267381 -2.4230576348998216 -2.4268300248717622
leaf_weight=83.175197124481201 293.85116350650787 162.05843567848206 260.32948708534241 902.86528480052948 2190.4528559446335 352.60659635066986 138.30466496944427 149.92255282402039 491.35525703430176 413.95200419425964 917.88713979721069 143.26261711120605 435.18979918956757 384.79628562927246 29.525714993476868 424.90389847755432 651.11971485614777 3112.2619578838348 178.26427924633026 290.44719636440277 1199.1584247350693 370.95841920375824 151.25453996658325 3771.151597738266 64.305379271507263 543.96874916553497 96.495068550109863
leaf_count=1124 3971 2190 3518 12201 29601 4765 1869 2026 6640 5594 12404 1936 5881 5200 399 5742 8799 42058 2409 3925 16205 5013 2044 50962 869 7351 1304
internal_value=-2.4359 -2.43852 -2.4141 -2.42607 -2.44176 -2.41974 -2.4384 -2.39535 -2.42218 -2.42408 -2.43475 -2.42102 -2.41705 -2.43552 -2.40561 -2.43571 -2.43664 -2.44254 -2.42179 -2.40154 -2.43503 -2.43265 -2.39441 -2.44567 -2.37697 -2.41872 -2.41413
internal_weight=0 16250.8 1952.99 3352.69 12898.1 2024.92 6936.55 587.85 1365.14 1550.29 3685.98 1197.68 873.784 3523.92 474.631 1327.77 3139.12 3250.57 613.454 440.37 2488 1570.12 180.78 5961.6 147.481 1054.42 510.447
internal_count=246000 219608 26392 45307 174301 27364 93738 7944 18448 20950 49811 16185 11808 47621 6414 17943 42421 43927 8290 5951 33622 21218 2443 80563 1993 14249 6898
is_linear=0
shrinkage=1


Tree=1
num_leaves=28
num_cat=0
split_feature=20 20 20 11 11 11 19 19 19 164 19 120 120 165 19 11 120 155 411 119 20 120 414 19 141 155 388
split_gain=4067.07 1164.6 761.416 551.984 443.56 351.807 231.163 215.608 213.301 159.929 152.151 151.169 150.299 141.771 126.727 110.541 109.932 109.416 108.268 105.914 103.514 97.7572 86.1089 80.3829 79.5221 72.5344 72.5228
threshold=-0.69501558637790939 -1.6199246107459455 0.18705904504727433 1.0000000180025095e-35 1.0000000180025095e-35 0.010176017601760177 -0.25931946189574345 1.0000000180025095e-35 1.0000000180025095e-35 30463.627500000006 -0.33317285005261182 -0.1119744058500914 -0.1119744058500914 40606.06500000001 -0.38840974305326348 1.0000000180025095e-35 -1.0000000180025095e-35 14573.587500000001 1.0000000180025095e-35 -0.074791418355184727 -1.805970119445869 -0.029707495429616083 -1.0000000180025095e-35 -0.26591259781672544 -0.12962962962962959 128176.24500000001 1.0034446283418978
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 4 12 10 21 -4 9 11 14 -2 -5 -3 19 -6 -8 -16 22 -18 -12 26 -1 -13 -14 -24 -25 -7
right_child=2 3 6 8 7 20 15 -9 -10 -11 13 17 23 -15 16 -17 18 -19 -20 -21 -22 -23 24 25 -26 -27 -28
leaf_value=0.010136493341937173 0.019630907721677485 -0.0016031657128517242 0.0060833603956792128 0.0095757243027746203 0.02790970391494834 0.048265962921923401 -0.009723555117714066 -0.00463605623955616 0.00069277689799767989 0.017281903594730818 -0.0080358950959152162 0.010716595915774783 0.026596902073650154 0.0046092315040836647 -0.00071357403772309355 -0.0055818568438012854 0.0089210779224663216 0.034935664421287364 -0.0012418163003517595 -0.0027537393802815704 0.02907324881012447 0.024776588414944952 0.027045770012416377 0.0051471714568945195 0.015969003418169415 0.021610846404729725 0.026557400729575163
leaf_weight=181.0024306550622 63.237178310751915 800.35561644285917 272.74775191396475 369.15127820521593 52.80791974812746 213.5016421303153 4211.2607928439975 552.17352489382029 192.71957285702229 258.62000314891338 1609.7504989728332 214.58202398568392 46.995849162340164 385.18661195039749 749.18891875445843 2357.8549280315638 1047.2490947619081 119.00928966701031 316.64053961634636 1981.8814068734646 180.01023383438587 268.74523938447237 341.52340202778578 1021.0001686885953 283.97828024625778 66.738015830516815 46.660414807498455
leaf_count=2415 847 10783 3683 4953 705 2809 57302 7484 2597 3473 21838 2865 626 5186 10142 32058 14096 1584 4277 26814 2375 3548 4536 13702 3796 893 613
internal_value=0 0.012885 -0.00404209 0.00886969 -0.00050692 0.0284627 -0.00766615 0.00396338 0.015753 0.00592588 -0.0038029 0.0179308 0.00345368 -0.00417881 0.0045642 -0.00823858 0.00397385 0.0211344 0.00655511 -0.00512404 0.0381873 0.0189121 0.0191605 0.00702813 0.0220383 0.0061695 0.0444311
internal_weight=0 4345.97 13858.6 3456.05 7016.74 889.92 6841.86 2976.68 1520.96 2424.51 4040.06 1328.24 1935.09 3976.82 2165.89 6569.12 2113.08 959.093 1363.89 3591.63 440.172 449.748 840.084 1134.73 625.502 1087.74 260.162
internal_count=246000 58095 187905 46335 94862 11760 93043 40177 20331 32693 54685 17734 26004 53838 29220 89360 28515 12781 18373 48652 5797 5963 11197 15221 8332 14595 3422
is_linear=0
shrinkage=0.0152673


Tree=2
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 21 1 19 11 20 19 20 11 20 20 20 19 20 135 19 135 119 411 90
split_gain=4237.33 2386.83 1352.83 715.205 601.022 459.95 389.572 334.757 288.841 186.188 182.126 175.793 168.566 159.562 155.742 140.689 124.708 105.994 104.569 98.0373 95.9659 92.6397 91.0944 90.7855 87.6089 80.9713 71.3969
threshold=-1.0130370759385332 -0.78572725661621623 -0.67885497766863889 0.1746120078555157 1.0000000180025095e-35 -1.523630872707755 0.16973448481238679 -1.8457901202353957 -1.7114100693421259 1.0000000180025095e-35 -0.33317285005261182 1.0000000180025095e-35 -1.8843834570786695 1.0000000180025095e-35 0.25232495053545462 0.093784378437843804 -1.5861933488948645 -1.6199246107459455 0.30984881848572216 0.047078586903806847 0.046583211681296859 0.39277035236938035 -0.26283576276536469 1.031895504252734 0.77145411203814074 1.0000000180025095e-35 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 5 6 9 13 18 16 21 -9 -7 -10 15 24 -3 -1 -5 -4 26 -6 -2 -8 -14 -12 -17 -13
right_child=1 4 7 17 20 11 22 10 12 -11 14 19 23 -15 -16 25 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.063888094811472076 0.013077980752777423 -0.00076510305269747805 0.029206024023721546 0.0085566153703894674 -0.0071050923216566652 0.0043847200161859145 0.0055668848828468271 0.032435247012503311 0.052716817268252697 0.035866654649978617 0.0072829579272888269 0.0074599401908385333 0.022640248762186725 -0.0060434124502291558 2.582007777468141e-05 0.0083635671101752757 0.040431946048043628 -0.0033437006639412824 0.01135306823940214 -0.0030183458213151344 -0.011161594794168721 0.029437009211831334 -0.0074038254764051785 0.045108108967630178 0.017920207114169907 -0.0012753230989992149 0.019622114727777445
leaf_weight=79.442038983106613 255.76300369203091 1487.9635493010283 254.40661803632975 214.09978495538235 2173.8004851788282 798.32574439793825 130.95954834669828 65.322744503617287 57.767961665987968 231.79671052843332 643.60098874568939 150.9065185636282 430.514114767313 655.18064283579588 558.8548010289669 933.19296178221703 180.14485158026218 934.03270994126797 112.64688940346241 63.659235134720802 3713.5102209597826 120.87478234618902 2918.2944071739912 47.654139570891857 254.16790066659451 257.57322834432125 480.31909824162722
leaf_count=988 3334 20111 3354 2836 29601 10678 1750 863 731 2976 8652 1983 5634 8919 7593 12457 2326 12568 1525 861 50962 1572 39935 621 3382 3479 6309
internal_value=0 -0.00306509 0.0177081 0.00856733 -0.00614671 0.013861 -0.00289951 0.0106658 0.0344121 0.0250574 0.00749879 0.00928999 0.0279487 0.000705116 0.00636992 0.00235946 0.0476892 -0.00111549 0.0237612 0.0149094 -0.00966564 0.0183652 -0.00684343 0.0249165 0.010308 0.00627103 0.0167323
internal_weight=0 15520.3 2684.52 3249.78 12270.5 2101.65 6383.16 1889 795.523 608.434 1521.95 1493.21 535.936 3333.91 1456.62 2678.73 259.587 1148.13 367.054 694.885 5887.31 376.638 3049.25 478.168 897.769 1190.77 631.226
internal_count=246000 210331 35669 43117 167214 27713 86651 25369 10300 7882 20490 19831 6986 44966 19627 36047 3314 15404 4879 9153 80563 4906 41685 6255 12034 15936 8292
is_linear=0
shrinkage=0.0152673


Tree=3
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 21 20 21 19 11 11 20 20 20 19 20 11 20 19 119 19 135 20 19 7 141
split_gain=4058.43 2316.13 1244.54 751.622 522.618 489.012 314.139 313.407 255.276 157.249 155.188 152.662 149.529 135.894 135.38 133.678 109.397 106.776 106.255 98.2979 92.9926 87.0284 81.3157 77.6039 75.6487 72.001 71.4181
threshold=-1.0130370759385332 -0.63287083336150685 -0.67885497766863889 0.036774081860548251 1.0000000180025095e-35 -1.5038460197363992 -1.811377762099047 0.18151951921313889 -1.7114100693421259 -0.33317285005261182 1.0000000180025095e-35 0.018426842684268429 -1.8843834570786695 0.26791529036287415 -1.6199246107459455 -0.31528071226839544 0.33014794124083729 0.010176017601760177 -1.5861933488948645 0.018489692726097188 0.77145411203814074 -0.26283576276536469 1.031895504252734 0.12356881070161159 0.044598349626972018 -0.52410275548920804 0.092592592592592601
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 5 7 11 16 15 18 -8 -7 -2 -10 20 -5 -3 26 -17 -1 -12 -11 -9 25 -6 -13 -14 -4
right_child=1 4 6 14 23 10 9 21 12 13 19 24 22 -15 -16 17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.059693214986487622 0.016543663306786187 0.015143517671879823 0.033453010356069818 0.009358453556730319 -0.0076163119222116132 0.0040190146132768594 0.030354890457726057 0.0054345490618108458 0.049701696204423156 0.0065254386408174258 0.015130986640199972 0.033733021868399993 0.010999548393915979 -0.00012356699276872265 -0.0029502103677200124 -0.0031969157664424436 0.0094729027918445362 0.0026589501150214791 0.038496414561389115 -0.0019999986966082227 0.017451653446646939 -0.0074098717729351666 0.042786013265673994 -0.011301529764561762 0.0019133978433741718 0.025473424261975745 0.018093816399643733
leaf_weight=83.706094607710838 303.74397011101246 131.66317468881607 173.57249383628368 247.28455795347691 2270.0330246165395 881.15572012960911 64.912808895111084 127.5521354675293 60.328469134867191 644.64972165226936 724.61018726974726 295.88485611975193 109.87172221392393 523.34476233273745 1310.0573075860739 1618.7622643783689 117.20837792754173 1314.3823560699821 186.27472859621048 86.407998271286488 255.69997074455023 2840.1331369653344 49.469717144966125 3309.477084569633 19.181481473147869 328.82349494099617 126.51908404380083
leaf_count=988 3898 1727 2239 3246 31148 11767 835 1697 731 8621 9420 3714 1411 7113 17696 21985 1573 17633 2326 1171 3355 39118 621 45865 246 4223 1633
internal_value=0 -0.00302666 0.01718 0.00720361 -0.00643554 0.012728 0.0104089 -0.00331814 0.0329297 0.00711628 0.00847098 0.0243479 0.0268877 0.00604617 -0.000988931 0.000103293 0.0221235 -0.000569697 0.0451416 0.0132945 0.00964185 -0.0068544 0.0240304 -0.00980416 0.0318273 0.021876 0.0270244
internal_weight=0 15480.3 2724.38 3868.33 11612 2310.98 1905.91 6032.49 818.474 1488.61 1692.17 618.81 548.493 1423.69 1557.34 3064.81 417.3 2933.14 269.981 811.018 900.35 2967.69 488.165 5579.51 315.066 438.695 300.092
internal_count=246000 210331 35669 51158 159173 30216 25369 82160 10300 19924 22358 7858 6986 19089 20942 41345 5445 39618 3314 10591 11976 40815 6255 77013 3960 5634 3872
is_linear=0
shrinkage=0.0152673


Tree=4
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 21 11 19 19 20 11 20 11 20 20 20 19 20 19 135 414 135 414 434
split_gain=3889.01 2250.22 1147.81 652.252 583.124 399.285 371.641 294.395 228.756 158.592 157.722 153.986 139.823 137.329 134.7 130.894 99.1957 94.664 94.0104 88.7202 88.2655 86.93 84.8504 81.1743 75.3806 72.5406 71.1576
threshold=-1.0130370759385332 -0.78572725661621623 -0.66331481234292167 0.1746120078555157 1.0000000180025095e-35 -1.523630872707755 0.16973448481238679 -1.8457901202353957 -1.7114100693421259 1.0000000180025095e-35 -0.33317285005261182 1.0000000180025095e-35 0.25232495053545462 0.018426842684268429 -1.8843834570786695 0.093784378437843804 -1.5861933488948645 0.046583211681296859 -1.4667066540297049 0.047078586903806847 0.30984881848572216 -0.26283576276536469 0.50455650060753354 -1.0000000180025095e-35 1.031895504252734 -1.0000000180025095e-35 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 5 6 13 11 20 18 -7 -9 15 22 -2 -10 -3 -5 -6 -1 -11 -4 -8 -12 -17 26 -15 -16
right_child=1 4 7 16 17 9 21 10 14 19 12 -13 -14 25 24 23 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.054120014607038296 0.015973324502076145 -0.00073063713051141821 0.027041780951924058 0.007665172639389854 -0.0069731217808000345 0.0042316272440123927 0.0053464365497160361 0.02985875762096225 0.046995384400789375 0.015841707016872514 0.0072687207878903565 -0.0059753346625287009 1.6234702877691231e-05 0.017044737050748202 0.017778011824669974 -0.00026800419337519971 -0.0033969300273388775 -0.011031053896053244 0.035550554505422119 -0.0029550637558763723 0.010816853301700496 -0.007270485342031811 0.018694132711940033 0.0085257164155183411 0.040651860450164543 0.034368389877544418 0.032586363851605002
leaf_weight=107.61570330709219 308.35075052827597 1485.0186468884349 263.74475704878569 238.10289194434881 2148.1168638169765 803.76256959140301 132.18443600088358 67.839345507323742 62.820000879466534 647.66466493159533 709.54942171275616 651.51759139448404 559.14837991446257 76.852371357381344 355.47653752565384 338.60819554328918 908.33513321727514 3644.9609917476773 175.85955659300089 63.393888168036938 114.73035697638988 2882.4424330219626 194.87744811922312 863.41176649928093 52.325278915464878 248.05244047939777 99.377791501581669
leaf_count=1227 3901 20111 3319 3117 29601 10678 1750 851 731 8292 9360 8919 7593 947 4490 4538 12287 50962 2129 861 1525 39935 2559 11398 635 3034 1250
internal_value=0 -0.00298862 0.0166766 0.00820079 -0.00602444 0.0131635 -0.00282792 0.0100901 0.0313993 0.00889587 0.00709964 0.000678468 0.00603452 0.0233517 0.0257673 0.00229553 -0.00109052 -0.00952822 0.0426656 0.0141527 0.0221559 -0.00671391 0.00974428 0.00604128 0.0231024 0.0303119 0.0210464
internal_weight=0 15440.8 2763.36 3294.51 12146.3 2148.08 6353.18 1909.89 853.475 1514.82 1531.41 3338.56 1463.58 633.256 570 2687.04 1146.44 5793.08 283.475 711.059 378.475 3014.63 904.427 1202.02 507.18 324.905 454.854
internal_count=246000 210331 35669 43117 167214 27713 86651 25207 10462 19831 20363 44966 19512 7882 7106 36047 15404 80563 3356 9153 4844 41685 11919 15936 6375 3981 5740
is_linear=0
shrinkage=0.0152673


Tree=5
num_leaves=28
num_cat=0
split_feature=21 21 19 21 11 17 19 414 135 19 11 19 155 19 19 149 19 161 388 392 147 414 11 120 135 10 414
split_gain=3728.49 1250.7 592.272 536.429 501.04 322.46 288.477 225.443 188.316 180.341 146.65 145.145 122.331 116.228 104.925 95.1697 93.2157 92.6276 83.1344 112.492 79.7046 77.4408 77.2339 72.1839 66.8853 62.6551 67.5451
threshold=-1.0130370759385332 1.0000000180025095e-35 1.0000000180025095e-35 -1.7794007366397382 1.0000000180025095e-35 1.0000000180025095e-35 0.0028346554504373738 -1.0000000180025095e-35 0.43772782503037672 -0.2981030959718084 1.0000000180025095e-35 0.039544982278674708 78807.645000000004 -0.2836795503754817 1.0000000180025095e-35 -0.30609803134421176 -0.3376378893188533 2261.2387500000004 0.45678925033826762 0.10964755390054655 0.55405405405405417 -1.0000000180025095e-35 1.0000000180025095e-35 -0.014168190127970747 0.65036452004860279 -0.55809641532756482 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 4 11 9 7 8 -6 16 -2 -3 18 25 -10 -12 20 -5 -15 19 -1 -9 -7 -18 -17 -25 -11 -27
right_child=1 10 -4 6 5 21 -8 15 13 12 14 -13 -14 17 -16 23 22 -19 -20 -21 -22 -23 -24 24 -26 26 -28
leaf_value=0.026671018853064887 0.018151706858373803 -0.0092218310761277306 -0.0070494693458843438 0.028417490726507164 -0.0015575352393955404 0.0087572733947035939 0.00085537342761561564 0.016647155808770516 0.047600884509109126 -0.0050810058264646697 -0.0028108652871176678 0.01042338759354681 0.0080765744370888282 0.016601498273948793 -0.010509687917642433 -0.00073188091374081974 0.0069885541970902826 0.033840382550859083 0.022866290743555329 0.043343753186424763 0.0041783609848799969 0.02261128815570022 0.014914355478504948 0.0062751441697991824 0.018046062827511301 -0.0054070102757585335 0.0010660268083197513
leaf_weight=203.46165155619383 112.76801294833422 4718.7069622799754 1674.0668689757586 76.678560182452202 758.83368295431137 131.09679889678955 415.43010821938515 443.71388123929501 43.57874121516943 1193.1642575412989 1832.2499592602253 100.75238776952028 287.12206174433231 287.09697809070349 534.80425219982862 292.39294262230396 580.49133060872555 99.926930010318756 227.58529701828957 186.75622358173132 166.6785216704011 360.04752714186907 579.73538699001074 825.08371847122908 131.60834462940693 508.89800602197647 1430.3924308791757
leaf_count=2492 1469 65779 23024 933 10174 1712 5460 5788 532 16250 25265 1260 3866 3679 7462 3879 7578 1262 2777 2251 2200 4601 7445 10819 1725 6954 19364
internal_value=0 -0.00295102 0.00106402 0.0161964 0.00311056 0.00757999 0.0122625 0.00544484 0.0150985 -0.000821413 -0.00766428 0.0275804 -0.0014508 0.0238163 -0.00455492 0.00830722 0.0120528 0.0210913 0.0303593 0.0346921 0.0132598 0.0189371 0.0109587 0.00587796 0.00790743 -0.00232746 -0.000628252
internal_weight=0 15401.6 8315.87 2801.49 6641.8 3109.46 2082.94 2618.31 1667.51 3532.34 7085.76 718.556 3419.58 430.603 2367.05 1859.48 1236.91 387.024 617.803 390.218 610.392 491.144 1160.23 1249.09 956.692 3132.45 1939.29
internal_count=246000 210331 111825 35669 88801 40898 26889 34585 21429 47903 98506 8780 46434 5473 32727 24411 15956 4941 7520 4743 7988 6313 15023 16423 12544 42568 26318
is_linear=0
shrinkage=0.0152673


Tree=6
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 20 1 1 19 10 21 19 19 20 20 164 19 141 414 11 19 20 135 119
split_gain=3575.96 2182.59 1037.71 666.75 496.779 423.318 297.13 260.206 192.742 144.229 143.235 142.019 146.339 142.015 127.516 123.578 112.458 110.22 100.008 90.4 85.7705 84.5568 83.9612 81.4198 77.1439 74.0356 73.9469
threshold=-1.0130370759385332 -0.63287083336150685 -0.67885497766863889 0.036774081860548251 1.0000000180025095e-35 -1.5038460197363992 0.18151951921313889 -1.7460870472760039 -1.805970119445869 1.0000000180025095e-35 1.0000000180025095e-35 0.026287426246023041 -0.55809641532756482 -1.7794007366397382 -0.29070757998552249 -0.33317285005261182 0.27816610872809261 0.22532716222380531 35341.492500000015 1.0000000180025095e-35 -0.092592592592592574 -1.0000000180025095e-35 0.093784378437843804 -0.26283576276536469 0.12356881070161159 0.71051032806804393 0.77145411203814074
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 5 6 10 15 17 -1 -5 -2 12 -7 -10 -9 -3 26 -4 19 22 21 -14 -17 -8 -6 -15 -16
right_child=1 4 7 9 24 11 23 14 13 -11 -12 -13 20 25 16 18 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.045739579490088819 0.016821944647463283 0.015954369523433459 0.024156793662244248 -0.0040901540845580345 -0.0074126384283321432 0.00052045929294961023 0.0050664150466635883 0.022817397734963576 0.03729792642861518 0.0058723680922426972 0.031708257253477139 -0.0034064301267039583 0.006318858669991604 0.019610941919037565 0.0053771328066108647 -0.0027602092503673675 -0.0010353064384296296 0.0096913620325811932 0.0075002312197886842 -0.0070838502980923902 0.0079985991662237139 0.01961575409611924 0.0033939815820715818 -0.0072665188054740803 -0.011126880198756271 0.035653394972124081 0.015373859773544942
leaf_weight=144.98701403290033 396.52060499787331 109.96829736977816 329.65735448896885 1044.7821701318026 2226.7689379751682 318.21686344593763 129.56536051630974 99.916031882166862 201.83576217293739 500.62009844183922 248.81139665842056 218.32671070098877 151.61363401263952 447.36057616770267 616.95383211225271 1180.7325285226107 474.17973279953003 200.42384389787912 322.81701094657183 537.50830704718828 581.10938008874655 448.87957570701838 918.41863937675953 2802.5293818563223 3226.0391157120466 81.3853395357728 242.34141467511654
leaf_count=1589 4895 1404 4007 14214 31148 4241 1697 1225 2281 6728 2963 2961 1966 5477 8079 16084 6397 2579 4283 7459 7506 5684 12115 39118 45865 953 3082
internal_value=0 -0.00291364 0.0157364 0.00693568 -0.00627566 0.0120343 -0.00324253 0.00956406 0.0295622 -0.00085661 0.0225837 0.00806452 0.00974067 0.0263276 0.00617312 7.47568e-05 0.00491588 0.0187104 -0.000513241 -0.00149833 0.0122155 0.016277 -6.32032e-05 -0.00671811 -0.0096121 0.0221101 0.00821002
internal_weight=0 15363.2 2839.04 3908.88 11454.3 2363.48 6001.54 1963.47 875.569 1545.4 645.332 1718.15 1499.82 730.582 1433.39 3069.44 1333.47 530.081 2959.48 2636.66 1181.6 600.493 2099.15 2932.09 5452.81 528.746 859.295
internal_count=246000 210331 35669 51158 159173 30216 82160 25369 10300 20942 7858 22358 19397 8711 18783 41345 17558 6586 39941 35658 15156 7650 28199 40815 77013 6430 11161
is_linear=0
shrinkage=0.0152673


Tree=7
num_leaves=28
num_cat=0
split_feature=21 21 11 21 414 17 411 411 11 11 390 8 70 10 149 158 391 411 8 7 9 390 10 10 248 155 70
split_gain=3431.15 1195.28 495.928 463.78 358.723 266.737 176.924 148.882 145.405 145.361 142.533 147.931 131.805 117.399 113.616 89.124 86.4671 73.9626 69.9742 133.764 59.9295 58.034 57.5943 55.8451 55.2887 54.9447 54.285
threshold=-1.0130370759385332 1.0000000180025095e-35 1.0000000180025095e-35 -1.7460870472760039 -1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 -0.20200074523897418 1.0000000180025095e-35 -0.30540540540540534 0.10335118802362314 -0.27498209239536847 178.65000000000003 -0.65476695674678731 1.0000000180025095e-35 1.0000000180025095e-35 -0.43328979287180441 0.82148791338371685 0.46323641188326148 0.23616261502540861 0.052808680126356276 0.41666666666666669 41866.132500000007 -0.64208494208494205
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 7 10 -4 12 9 13 -3 23 -1 16 -6 15 -14 -2 -12 22 19 -11 24 -7 -10 25 -21 -5 -15
right_child=1 8 4 6 5 21 -8 -9 17 18 11 -13 14 26 -16 -17 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.017065773238385443 -0.0034099637869604406 -0.0090941704886508858 -0.0018761293492986612 0.0037492357645354632 -0.00010708663086232918 0.015214392860477766 0.003790018228580595 -0.0075563320492744229 -0.0051631017358773224 0.013380428937243191 0.017976285175032993 0.021143444603106056 0.014216972470048701 -0.0023553045288643745 0.0055542494645327567 0.0097190940763161628 0.041961149624167499 -0.0088493507956903493 0.012607907253267129 0.038106327569789787 0.0074650972045796531 0.027377532513669266 0.00050502937916132109 0.014425891963864417 0.022556238133962254 0.018827051609336572 0.0053945407594914695
leaf_weight=324.76867339015007 2337.497063100338 4651.3535982519388 1178.5422192066908 394.66649612039328 577.29175072163343 268.2730829641223 530.15622881054878 1005.4084246456623 979.43045515567064 217.43383087217808 43.881736889481544 231.09176500141621 525.69022177159786 285.78089697659016 1093.5228655487299 126.55560175329447 220.65634132176638 640.46151243150234 277.95493058860302 145.17500586807728 26.696185052394867 145.31080853193998 723.83996103703976 304.54028454422951 92.429278679192066 66.20214319229126 785.97821597009897
leaf_count=3866 31951 65779 15875 5081 7718 3391 6806 13883 13689 2696 513 2729 6771 3879 14308 1704 2534 9011 3489 1781 337 1805 10027 3863 1137 837 10540
internal_value=0 -0.00287684 0.00102949 0.0152969 0.0051086 0.00826584 0.011413 -0.00237166 -0.00752977 0.0140561 0.0250103 0.0301887 0.0061408 -0.000894469 0.00837374 -0.00273119 0.0380337 -0.00442065 0.0187994 0.0223461 0.0296717 0.0195212 -0.00274916 0.00933254 0.0321198 0.00594221 0.00331947
internal_weight=0 15324.9 8329.85 2875.65 3788.63 2610.09 2055.25 4541.22 6995.09 1525.1 820.399 495.63 2196.5 3535.81 1619.21 2464.05 264.538 2343.73 759.689 481.734 264.3 413.584 1703.27 765.409 237.604 460.869 1071.76
internal_count=246000 210331 111825 35669 49868 33993 26027 61957 98506 19221 9642 5776 28797 48074 21079 33655 3047 32727 9440 5951 3255 5196 23716 9781 2918 5918 14419
is_linear=0
shrinkage=0.0152673


Tree=8
num_leaves=28
num_cat=0
split_feature=20 20 20 11 11 10 19 19 19 10 166 19 141 166 19 19 11 90 391 6 166 118 135 8 391 6 8
split_gain=3332.03 870.337 629.444 417.158 361.462 234.529 207.554 173.618 172.67 141.266 133.616 133.058 122.854 122.341 120.667 111.929 105.812 104.02 100.523 104.516 90.5696 90.4106 85.9172 84.5423 79.6252 99.1133 75.8942
threshold=-0.63287083336150685 -1.6199246107459455 0.18705904504727433 1.0000000180025095e-35 1.0000000180025095e-35 -0.32941903584672433 -0.25593239003289309 1.0000000180025095e-35 0.034352697987202814 0.11090509545392117 35950.713750000003 -0.33317285005261182 0.055555555555555559 40623.423750000009 1.0000000180025095e-35 -0.38840974305326348 1.0000000180025095e-35 -1.0000000180025095e-35 0.12742144408804593 -0.3717000835421887 39268.473750000005 -0.11187050359712229 0.83748481166464173 1.0000000180025095e-35 0.1379033485638034 -0.43503759398496239 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 4 9 11 -1 -4 12 10 22 15 -2 17 21 20 -6 -8 -5 19 -19 -7 -13 -3 -21 25 -17 -27
right_child=2 3 6 7 8 14 16 -9 -10 -11 -12 13 -14 -15 -16 24 -18 18 -20 23 -22 -23 -24 -25 -26 26 -28
leaf_value=0.011451338473909946 0.018068765759755339 -0.0010721459638637861 0.0053872192106341407 0.0096288134200612652 0.025394065640919835 0.027820993913726888 -0.0093710383274583572 0.00011079762487244684 -0.0052518640847477099 0.0087368232432562705 0.015366565596928507 -0.0078957673567154659 0.0091687080234084638 0.0041824640080633723 0.008304979703096944 0.00068342799847968079 -0.0052499667932032826 0.016778856477702799 0.011616477322825782 0.036028184437327616 0.04473185853338045 -0.0028466640559389185 0.010530922802160036 0.017781458914759039 -0.0011811106191762454 0.012198801459559691 0.0025474721207029505
leaf_weight=273.79302602261305 63.694292291998863 1280.6110723689198 286.43608669191599 253.02111209183931 54.319660171866417 565.19011831283569 4030.8816447779536 214.61466857790947 452.60298496484756 673.73043227940798 259.62422097474337 1466.9172144606709 573.74217630922794 370.87404131889343 66.432735063135624 644.29032748192549 2292.4838379845023 230.31311392039061 194.42818032950163 206.91136431694031 88.115243300795555 1913.5020437091589 168.04879004508257 87.148241080343723 660.6961652263999 524.89980220794678 301.9322933703661
leaf_count=3367 805 17129 3793 3141 664 6580 57259 2858 6244 8778 3335 20528 7225 4975 803 8501 31991 2829 2423 2514 1010 26263 2211 1080 8804 6876 4014
internal_value=0 0.0107923 -0.00395781 0.00752523 -0.000663492 0.0235463 -0.00730223 0.0130216 0.00339909 0.00296176 0.00500404 -0.00375238 0.0148082 -0.00412627 0.0281301 0.00376791 -0.00787864 0.0181256 0.0211003 0.0245935 0.0301289 -0.00504075 0.000268789 0.0306674 0.00321024 0.00518856 0.00868699
internal_weight=0 4876.1 13323.2 3882.57 6713.35 993.531 6609.8 1760.18 2898.37 2122.39 2445.76 3814.99 1545.56 3751.29 719.738 2186.14 6323.37 971.822 718.801 524.373 653.305 3380.42 1448.66 294.06 2131.82 1471.12 826.832
internal_count=246000 61948 184052 50188 91009 11760 93043 22070 38438 28118 32194 52571 19212 51766 8393 28859 89250 11987 8846 6423 7590 46791 19340 3594 28195 19391 10890
is_linear=0
shrinkage=0.0152673


Tree=9
num_leaves=28
num_cat=0
split_feature=21 20 21 20 20 21 20 20 19 10 20 19 20 10 21 414 164 135 19 141 11 389 141 119 164 434 10
split_gain=3268.2 2245 792.738 699.275 496.295 448.595 204.029 189.424 163.914 164.444 150.882 145.173 137.12 131.474 108.999 100.827 99.139 90.0821 89.3755 75.0628 74.1689 73.7675 75.9515 72.414 66.6328 64.3925 60.0425
threshold=-1.2291473454499886 -0.39425883824369934 1.0000000180025095e-35 -0.66331481234292167 -1.4667066540297049 1.0000000180025095e-35 0.34028619137497118 0.26791529036287415 0.026287426246023041 -0.56647438538662265 -1.5541831278822766 -0.31528071226839544 -1.3243683937921145 -0.54216453783820895 -1.8457901202353957 -1.0000000180025095e-35 36029.92500000001 0.89216281895504268 0.0028346554504373738 -0.092592592592592574 1.0000000180025095e-35 0.36961545671919621 -0.055555555555555546 0.77145411203814074 169387.97625000004 1.0000000180025095e-35 -0.31170168932838888
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 4 12 13 6 11 14 9 -6 26 -3 -1 -2 -5 -11 18 21 -13 -17 -12 22 -15 -16 -21 -14 -4
right_child=1 5 10 7 8 -7 -8 -9 -10 15 20 16 25 17 23 19 -18 -19 -20 24 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.03719144553208753 0.0084642854270990577 0.013342169780510378 -0.00015944099782242717 0.023682850695773184 -7.7870605072913592e-05 -0.0098225890796024978 -0.0072884176039280085 0.0038760086994063122 -0.002977615424571103 0.003947526982055128 -0.0058124773373836669 -0.0015400720823136602 0.020359969868799569 0.031769257575317074 0.0089155325074423888 0.016433934358464398 0.0052348832737263776 0.03939656501543895 -0.0078260496221453438 0.007776431396897673 0.00079013617881322409 0.013143813687724668 0.018141816677964728 0.019786277370505471 0.027938384534818495 0.035906501129803259 0.013545870782481975
leaf_weight=328.37259555608034 162.97374361753464 149.82581658661366 121.85198282450438 270.98811166733503 412.98777720332146 4897.5065185204148 2145.7893673628569 506.63608417659998 331.47076808661222 405.15098526328802 1122.1863794252276 2454.8334445431828 307.67687083780766 208.62600885331631 484.00653531402349 643.63604581356049 392.54646361619234 78.592671401798725 673.4611964225769 618.87686397135258 609.67187750339508 168.46887933462858 186.32972889393568 206.72570622712374 41.029546976089478 81.158791102468967 186.39221872389317
leaf_count=3514 2012 1869 1603 3128 5515 70607 30175 6640 4510 5243 15640 33282 3516 2406 6158 7979 5211 897 9441 7894 8272 1963 2189 2522 516 914 2384
internal_value=0 -0.00239662 0.00573165 0.0175055 0.0104049 -0.00641707 -0.00354779 0.0114573 0.00698489 0.00854578 -0.00172754 -0.00135832 0.0298687 0.0208114 0.01544 0.0106352 -0.00198721 0.0239278 -0.00289666 0.0127059 -0.00348303 0.0217405 0.0253758 0.012187 0.00905196 0.0236452 0.00810174
internal_weight=0 16012.2 5298.25 2185.56 3258.14 10714 5816.46 1468.36 2453.15 2121.68 2040.1 3670.67 717.208 804.991 961.72 1708.69 3520.84 642.017 3128.29 1303.54 1731.86 563.425 394.956 690.732 659.906 388.836 308.244
internal_count=246000 219608 69023 26392 41124 150585 79978 18448 31657 27147 27899 49803 7944 9467 11808 21632 47934 7455 42723 16389 23912 6558 4595 8680 8410 4430 3987
is_linear=0
shrinkage=0.0152673


Tree=10
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 1 21 19 1 135 20 19 11 20 10 20 19 19 20 90 20 168 90 1
split_gain=3149.16 1975.31 849.298 611.828 428.736 405.155 246.835 225.108 162.705 154.987 137.43 133.858 111.544 106.585 102.441 96.2759 86.3182 82.9943 80.0442 76.2886 75.5661 70.5078 70.0053 69.6405 69.5864 65.2022 64.8425
threshold=-0.99172777905286968 -0.56049749714782426 -0.67885497766863889 0.1746120078555157 1.0000000180025095e-35 -1.4484078925093731 0.19275266783187991 -1.8457901202353957 1.0000000180025095e-35 -1.6426344058948754 0.066137329671330417 1.0000000180025095e-35 0.44380315917375462 -1.5861933488948645 1.0000000180025095e-35 0.093784378437843804 -1.417518363968721 -0.5103007828594972 0.35009543907003798 0.018489692726097188 -0.26283576276536469 0.12356881070161159 -1.0000000180025095e-35 -1.8843834570786695 1.0000000180025095e-35 -1.0000000180025095e-35 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 9 5 6 8 14 -4 24 16 12 17 18 -5 15 -3 -1 -7 -9 -19 -8 -6 -13 -11 -2 -10 -15
right_child=1 4 7 13 21 11 20 10 25 23 -12 22 -14 26 -16 -17 -18 19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.04263036902190049 0.01200906607760046 -0.0016720263411135164 0.018740692800733382 0.0072298218178367913 -0.0072546578034338735 -0.0030851984478663555 0.0048715550103861326 0.0081957861571382573 0.016585732310276144 0.035836782577962585 -0.0033668791206080016 0.0044890105784902703 0.015772904537657013 -0.0062831483232809564 -0.0060804803603795353 0.0045281994592578948 0.027398954777162914 0.0077504063525760877 -0.0014965412797092977 -0.0040094189283612584 -0.0071938796247931524 -0.010914848577539061 0.014972840820118839 0.019214277457893818 0.032754670367040009 0.032023229631281756 0.0012167825917057395
leaf_weight=156.50326538830996 476.80749972909689 1302.2852729782462 416.44907288998365 242.14547749608755 2056.5601138472557 339.32174918800592 125.68338230997324 757.00297348201275 93.556206934154034 68.234057903289795 289.46442282944918 219.37787983566523 340.69224836677313 825.43390712887049 575.80141634494066 1055.9605912715197 213.39006480574608 754.32905878871679 267.12344059348106 153.75933031737804 2671.1405850425363 3128.8517391979694 479.80775643885136 519.77737545967102 41.511246547102928 228.88898107409477 395.50569318234921
leaf_count=1545 5725 17747 4879 3117 29410 4565 1631 9581 1079 692 3832 2819 4299 11466 8081 13698 2300 9507 3576 2103 37974 45865 6049 6006 481 2591 5382
internal_value=0 -0.00284511 0.0142062 0.00598346 -0.00628355 0.0101804 -0.0034028 0.00869932 0.0190416 0.0260967 0.00616401 0.00634679 0.00819232 -0.00200621 -0.000305921 0.00110054 0.0338877 0.00333823 0.00565899 0.00574868 -0.0066481 -0.0094653 0.0116987 0.0211703 0.0137002 0.0275855 -0.00384635
internal_weight=0 15166.7 3028.64 4250.44 10916.3 2787.36 5730.87 2070.73 840.764 957.905 1654.28 1946.6 1364.82 1463.09 2934.05 2358.25 369.893 1247.41 1024.13 908.088 2796.82 5185.41 699.186 588.011 518.319 322.445 1220.94
internal_count=246000 209290 36710 54884 154406 34919 79131 26167 9876 10543 21288 25043 17456 19965 39526 31445 3845 16175 13157 11610 39605 75275 8868 6698 6206 3670 16848
is_linear=0
shrinkage=0.0152673


Tree=11
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 21 10 20 20 164 20 11 20 20 135 150 10 411 135 135 11 411 411 11
split_gain=3028.47 1856.55 863.275 482.597 482.267 312.111 285.846 243.386 159.655 145.796 117.608 106.354 104.977 91.8173 89.7403 87.759 85.7658 79.2173 73.9724 71.2582 71.1446 68.6095 67.1095 66.1305 64.875 62.1566 62.2839
threshold=-0.91949617505527348 -0.78572725661621623 -0.67885497766863889 0.1746120078555157 1.0000000180025095e-35 0.12356881070161159 -1.6973680938911146 -1.7460870472760039 -1.3471229168525309 -0.58254360664743843 0.30984881848572216 -1.3243683937921145 35341.492500000015 0.046583211681296859 0.093784378437843804 0.24707661030359654 -1.5861933488948645 0.44380315917375462 0.35375494071146252 -0.38449388820216995 1.0000000180025095e-35 0.71051032806804393 0.52946537059538279 -0.29180418041804174 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 6 5 12 19 15 11 -8 17 -1 14 -6 -3 -4 -5 -9 -14 -2 23 -10 -21 -11 -16 26 -7
right_child=1 4 7 16 13 25 9 10 21 20 -12 -13 18 -15 24 -17 -18 -19 -20 22 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.036171089969920217 0.011294520283122783 -0.0028611718060458525 0.021015088468819547 0.0070766709915561221 -0.0065558051671014235 -0.0069822495083779164 0 0.0054005396751769267 0.014709463944837988 0.0064365255420686445 -0.00086764750651263829 0.023374194040404257 0.002563008731518727 -0.010640106004872795 0.0047981042823140481 0.0082716855460539408 -0.0031361663162997062 0.014614085926030786 0.017287149240172831 0.021972773367235021 0.003083263052946263 0.031753785693910741 0.038728183190057525 0.014742937932149343 -0.0036794962839363857 -0.0096849885183987582 -0.0016702277402163978
leaf_weight=297.96306567639112 109.75075544416904 1471.0557930096984 365.01413285732269 243.60196844488382 2070.0626234635711 1303.8580421209335 369.06506058573723 881.62602586299181 366.75878166407347 316.24702759087086 544.83132127672434 325.85549965500832 190.85257366299629 3450.5587220937014 895.00857742130756 197.268110871315 892.51628117263317 291.71828058362007 138.44771091639996 267.05629306286573 233.2373549118638 66.372301168739796 73.644394233822823 804.736636698246 273.6664222702384 893.16133866459131 858.67900145053864
leaf_count=2994 1299 20228 4136 3117 29601 18596 4874 11263 4241 4034 7368 3544 2487 50962 11542 2450 12287 3638 1772 2975 2968 728 801 9692 3704 12773 11926
internal_value=0 -0.00295989 0.0131342 0.00711891 -0.00585018 -0.00286087 0.0113335 0.00784084 0.0245427 0.00849258 0.00497886 0.0295109 0.00066165 -0.00911057 -0.000349214 0.0165651 -0.000937449 0.00770113 0.00878802 0.0221732 0.0108105 0.0173559 0.025642 0.0124093 0.00280479 -0.0062863 -0.00487759
internal_weight=0 14855.2 3337.41 3309.86 11545.4 6024.73 2173.74 2280.46 1056.95 1723.29 1718.18 623.819 2969.03 5520.62 2639.73 562.282 1136.12 1173.34 329.3 450.451 1354.22 433.131 340.701 1120.98 1168.67 3055.7 2162.54
internal_count=246000 205638 40362 42047 163591 83028 26643 28855 11507 21568 22269 6538 39733 80563 35474 6586 15404 14901 4259 5075 16694 4969 3776 13726 15246 43295 30522
is_linear=0
shrinkage=0.0152673


Tree=12
num_leaves=28
num_cat=0
split_feature=21 20 20 21 20 21 21 20 21 20 1 1 19 118 20 1 19 7 19 19 90 19 416 20 90 19 155
split_gain=2912.77 1804.33 807.956 580.577 382.501 340.395 229.459 177.611 165.747 140.974 139.276 128.31 117.404 105.624 96.2388 92.887 82.9108 80.078 78.8281 78.7588 76.7952 73.9547 70.1861 70.0144 69.6653 65.0153 64.1216
threshold=-0.91949617505527348 -0.39425883824369934 -0.56049749714782426 1.0000000180025095e-35 -1.4484078925093731 0.020441442567955586 -1.4231812591257043 0.19275266783187991 -1.7114100693421259 -1.1812398945549447 1.0000000180025095e-35 1.0000000180025095e-35 -0.3376378893188533 0.43057553956834538 -1.8843834570786695 1.0000000180025095e-35 -0.18975535038981672 -0.54077253218884114 0.031620260851838951 0.066137329671330417 -1.0000000180025095e-35 -0.2981030959718084 -1.0000000180025095e-35 -2.0097992159524432 -1.0000000180025095e-35 1.0000000180025095e-35 115710.60375000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 8 4 11 7 12 18 -1 15 16 -2 -4 -14 -10 -5 -6 -16 -3 26 -12 -9 -22 -13 -25 -19 -8
right_child=1 5 6 9 10 -7 19 21 14 -11 20 23 13 -15 17 -17 -18 25 -20 -21 22 -23 -24 24 -26 -27 -28
leaf_value=0.031383757399610496 0.013177483390858807 0.00029420758021279057 0.035146007218499309 -5.7156996628284118e-05 0.013657280144504572 -0.0096565095641314123 0.0031266372923231893 0.0073644595914187172 0.034358021987161085 -0.0046355051864009787 0.0036968825802181455 0.047561966255211814 0.0062606895638023163 0.016285514258731832 0.0080652660145733388 0.011602624124697427 0.0014056091069042705 0.02215762797187297 -0.0068436276748038965 -0.0060552634988390742 0.021342458713542126 -0.0071213099706415655 0.0097650775498083035 0.010932345232676523 0.028377568957897691 0.0072896506595556783 0.017354410430778167
leaf_weight=371.36514018476009 468.90893688797951 2002.9245544299483 50.657004006206989 481.72075118869543 144.13133758306503 4720.5239480510354 849.07663951069117 84.027698211371899 86.618156418204308 1312.9090649709105 245.79154039919376 32.272703267633915 497.98296877741814 490.79643917828798 174.46702554821968 236.57368614524603 1222.1399673074484 483.02771367132664 439.10081918537617 205.01818192005157 197.1262521147728 2625.617754817009 335.46960195153952 77.353241503238678 190.36721470206976 82.443434491753578 81.1617716178298
leaf_count=3677 5448 26797 561 6462 1775 69755 11018 1088 846 18374 3147 332 6130 5900 2008 3063 15875 5446 6212 2772 2424 37729 4213 871 2073 979 1025
internal_value=0 -0.00292269 0.0127973 0.004604 0.00897228 -0.00669359 0.0072439 -0.00397659 0.0228683 -0.00165761 0.00565287 0.0182151 0.0124282 0.0112482 0.0190246 0.00377246 0.00270658 0.0172085 -0.000985952 0.00248774 0.0108106 -0.00666821 0.0140737 0.0260448 0.0233832 0.0200095 0.0043813
internal_weight=0 14817 3372.61 4944.76 2913.56 9872.19 2174.69 5151.67 1197.92 2031.2 2144.66 768.902 1039.44 988.779 826.556 718.294 1366.27 739.938 2442.03 1135.26 778.387 2709.65 532.596 299.993 267.72 565.471 930.238
internal_count=246000 205638 40362 64057 36158 141581 27406 71826 12956 27899 27434 8724 12591 12030 9279 9525 17650 8433 33009 14815 9784 38817 6637 3276 2944 6425 12043
is_linear=0
shrinkage=0.0152673


Tree=13
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 21 20 20 1 1 20 164 21 109 21 119 411 143 391 6 149 20 387 135 1 149 416
split_gain=2816.07 1299.1 1246.11 542.01 421.986 351.738 208.951 190.278 179.552 162.695 137.09 97.5091 95.6749 93.888 87.8358 87.2962 81.4771 79.3316 77.2798 91.84 75.7355 68.7682 67.2997 61.5845 61.0991 58.9041 58.6936
threshold=-0.39425883824369934 -0.86788298377637296 -1.2291473454499886 -1.523630872707755 1.0000000180025095e-35 0.15850492709346628 -1.3243683937921145 0.34028619137497118 1.0000000180025095e-35 1.0000000180025095e-35 0.26791529036287415 35341.492500000015 -1.7794007366397382 -0.41666666666666657 -1.6426344058948754 0.51281287246722307 1.0000000180025095e-35 1.166666666666667 0.12742144408804593 -0.40212197159565571 -0.1987258706506824 -2.0580407920971773 -0.13980218390021007 0.81318347509113009 1.0000000180025095e-35 -0.32493840571154203 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 10 9 7 8 14 11 20 13 15 16 -8 -3 -1 -2 18 -14 19 -4 22 -11 -5 -16 -7 -21 -10
right_child=2 3 4 5 -6 24 12 -9 26 21 -12 -13 17 -15 23 -17 -18 -19 -20 25 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.036682314151383739 0.0093182490944832691 0.018046133892823144 -0.0025706524710710226 0.013062207908737586 -0.0095528647611125943 -0.0062205907079846794 0.025076942559584914 -0.0070598040388684634 0.015992886420344497 0.048616813705394536 0.0034560380564381999 0.0056972888938247052 0.011298967877743574 0.005215784739702016 0.020758882470351722 0.01967269045982185 -0.0064780044407788638 0.024591458766474662 -0.0043063479333135387 0.011762106173357427 -0.00033424301509769845 0.02097800452649622 0.002488612681497528 0.039671324008213396 0.00039767151824911072 0.0023517778363558099 0.0078243999762467077
leaf_weight=193.73373483121395 467.97387233376503 206.17721839249134 743.59863253682852 228.91396295279264 4739.2939776480198 988.24843218177557 227.79043047130108 2100.8811488822103 329.47458882629871 22.94259512424469 516.34577977657318 412.11284003406763 602.27766045928001 383.00135732442141 285.74386990815401 326.58136214315891 781.19203874468803 128.84522983431816 923.56844699382782 213.13818423449993 978.73229543864727 339.07514727115631 369.55252441763878 48.548244506120682 480.72893600910902 581.7505267187953 566.05265078693628
leaf_count=1780 5611 2357 10062 2828 70607 13964 2336 30175 4044 242 6640 5421 7053 4651 3043 3774 10904 1495 12678 2860 12715 3770 4857 488 6628 7878 7139
internal_value=0 0.00816428 -0.00442456 0.00436363 -0.00617804 0.00186447 0.0206622 -0.00339762 0.0053811 0.0147078 0.00960624 -0.00129004 0.0163864 0.00972578 0.0284008 0.0135896 -0.00218103 0.0136601 -0.000813494 0.00127763 0.00227318 0.0227808 0.00655134 0.0235549 -0.00404874 0.00488887 0.0108428
internal_weight=0 6379.84 11806.4 4892.9 10495.5 3941.7 1486.94 5756.24 2472.73 951.196 1310.9 3655.36 958.913 589.179 528.026 794.555 3243.25 731.123 2462.06 1538.49 1577.2 362.018 598.466 334.292 1468.98 794.889 895.527
internal_count=246000 79390 166610 63195 150585 52175 16195 79978 31583 11020 16025 49803 10884 7008 5311 9385 44382 8548 33478 20800 20400 4012 7685 3531 20592 10738 11183
is_linear=0
shrinkage=0.0152673


Tree=14
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 19 20 1 1 19 20 20 10 21 21 164 143 149 158 21 411 1 19 168 20
split_gain=2722.86 1227.22 1209.56 520.921 416.009 381.435 192.844 187.351 166.078 144.281 133.83 133.43 101.9 96.6512 89.9718 88.8684 79.7749 77.6725 73.839 71.1161 70.5065 69.1901 63.3951 62.3666 58.3064 53.5078 52.9729
threshold=-0.39425883824369934 -0.86788298377637296 -1.2291473454499886 0.1746120078555157 1.0000000180025095e-35 -1.3728960730153772 -1.3243683937921145 -0.31528071226839544 0.18151951921313889 1.0000000180025095e-35 1.0000000180025095e-35 0.066137329671330417 -1.5861933488948645 0.33014794124083729 -0.14716385111935171 -1.7794007366397382 -1.6426344058948754 35341.492500000015 1.166666666666667 -0.18481959892213282 556.97625000000005 -2.0621762643796608 1.0000000180025095e-35 1.0000000180025095e-35 0.031620260851838951 1.0000000180025095e-35 -2.0097992159524432
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 11 5 7 9 16 -4 17 20 14 13 -5 21 -7 -8 -1 24 -17 -16 -3 -2 25 -14 -9 -10 -11
right_child=2 3 4 12 -6 10 15 8 22 26 -12 -13 23 -15 19 18 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.035141314629082897 0.02689884526045197 0.0096776523784300461 0.011090291932383096 0.0065848639386762312 -0.0094848470493649282 -0.0029884843894201103 0.024214156287058624 -0.00081105129318233076 -0.005516977423172224 0.041156898612878398 0.009450842278753235 -0.0013648302512749317 -0.0061579098969783029 0.004796919309122215 0.010067583554362835 0.011024513325906529 0.022770024218040589 0.0063697980412027802 0.023738487992008478 0.0010463108755887514 0.029630344475491836 0.012838119554419882 -0.0097395169282034951 0.00048696298267342464 -0.0071044152210502937 0.0043077433731197479 0.021491794551921954
leaf_weight=199.10782264173031 94.894514054059982 537.26119158416986 201.39641279727221 248.37981759756804 4700.7036594450474 576.1266613304615 232.2770151719451 1848.4234338477254 1940.8241023346782 36.804469376802444 806.00594802200794 222.26990715414286 996.20590210705996 342.57749827951193 352.2186067700386 607.80901429802179 340.50138133019209 292.13860999792814 131.42393692582846 488.89357629418373 45.197711974382401 661.42593552172184 897.11075525730848 487.99333399534225 422.56947668641806 137.22299578040838 334.9937687292695
leaf_count=1780 1024 6287 2502 3117 70607 7698 2336 24820 27881 360 10035 2809 14144 4382 4434 7053 3531 3746 1495 6251 500 7810 13068 6719 6021 1940 3650
internal_value=0 0.00798708 -0.00437405 0.00428161 -0.00611627 0.00795416 0.020019 -0.00335563 -0.00388298 0.016031 0.00448218 0.00938555 -0.00244859 0.0115682 0.00164903 0.0159256 0.0273631 -0.00103019 0.0133031 0.00483638 0.0112513 0.0146211 -0.00633738 -0.00396718 -0.00198663 -0.00486345 0.0234842
internal_weight=0 6421.2 11761.6 4910.08 10440.4 3177.5 1511.12 5739.69 5538.29 954.257 2223.24 1321.17 1732.58 1098.9 1417.24 971.51 539.609 2563.13 739.233 841.112 582.459 756.32 2975.16 1484.2 2270.99 2078.05 371.798
internal_count=246000 79390 166610 63195 150585 39215 16195 79978 77476 10797 28418 16025 23980 13216 18383 10884 5311 34587 8548 10685 6787 8834 42889 20863 30841 29821 4010
is_linear=0
shrinkage=0.0152673


Tree=15
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 20 1 19 1 19 11 20 19 21 20 164 21 90 19 143 135 90 158 141 161
split_gain=2633.09 1174.19 1160.28 501.121 410.057 361.562 183.715 178.329 134.384 131.129 128.101 127.357 99.0156 91.378 89.2364 83.2425 81.4415 74.8949 74.2427 72.7748 71.899 67.585 67.0673 66.453 65.6284 61.7129 58.1058
threshold=-0.39425883824369934 -1.2291473454499886 -0.86788298377637296 0.1746120078555157 1.0000000180025095e-35 -1.3728960730153772 0.34028619137497118 -1.3243683937921145 1.0000000180025095e-35 -0.31528071226839544 1.0000000180025095e-35 0.066137329671330417 1.0000000180025095e-35 0.33014794124083729 0.031620260851838951 -1.8821381414301499 -1.6973680938911146 38432.463750000003 -1.3471229168525309 -1.0000000180025095e-35 -0.18975535038981672 1.166666666666667 0.457168894289186 -1.0000000180025095e-35 556.97625000000005 0.055555555555555559 17753.523750000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 11 7 5 6 8 9 18 24 -3 20 13 -5 22 17 -9 -14 -11 -1 -10 -7 -17 -2 -12 -4 -25 -23
right_child=1 4 3 12 -6 10 -8 15 19 14 23 -13 16 -15 -16 21 -18 -19 -20 -21 -22 26 -24 25 -26 -27 -28
leaf_value=0.031069273412725851 0.011611622739828673 0.012538866534539547 0.0094550746436589828 -0.0051168252405931099 -0.0094168761232547842 0.011732844878221559 -0.0069381998050577435 0.025227658470502578 0.012161648787362435 -0.0015377766221497681 0.0027115472881906444 -0.0013455378763310376 0.017876106784906528 0.0047048626864392117 -0.0068425382786793162 0.011327968923768653 0.00047697380392035341 0.0063992001560079963 0.019454517607865877 0.027054688198127532 0.00044590911850360046 0.021125011837580109 0.022213579499175053 0.016490447814885581 0.028498481220301693 0.0061082324527261265 0.079902734928807714
leaf_weight=327.66473587602377 577.6451897919178 153.69326508045197 541.48474871367216 1118.7945964112878 4662.6426556259394 146.81309876590967 2077.654471039772 171.07279824465513 111.56255789101124 2505.8507889211178 254.0490055680275 222.01949714124203 70.955803714692593 343.94121176749468 674.96011139452457 667.33169241249561 539.19348082691431 311.13173430413008 223.27234630286694 267.15971429646015 1272.3454009070992 141.4586663544178 187.63724779337645 325.5991690531373 46.274777933955193 232.64500198513269 3.9922778308391562
leaf_count=2994 6707 1869 6287 15714 70607 1791 30175 1680 1220 34237 3212 2809 856 4382 9666 7593 7410 4031 2317 2790 16592 1568 2127 3929 500 2894 43
internal_value=0 -0.00432401 0.00781514 0.00420153 -0.00605488 0.00778221 -0.0033141 0.0194072 0.0155854 -0.00124593 0.00439729 0.00917167 -0.00241629 0.0112849 -0.00185596 0.0154845 0.00252057 -0.000657505 0.0263877 0.0227005 0.00162149 0.0134168 0.0142282 0.00923402 0.0109791 0.0121839 0.0229087
internal_weight=0 11717.2 6461.67 4926.88 10385.9 3197.93 5723.29 1534.79 966.482 3645.64 2231.45 1331.24 1728.94 1109.22 3491.94 983.855 610.149 2816.98 550.937 378.722 1419.16 812.783 765.282 812.293 587.76 558.244 145.451
internal_count=246000 166610 79390 63195 150585 39215 79978 16195 10797 49803 28418 16025 23980 13216 47934 10884 8266 38268 5311 4010 18383 9204 8834 10035 6787 6823 1611
is_linear=0
shrinkage=0.0152673


Tree=16
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 20 1 20 10 20 164 10 21 119 411 390 90 21 150 149 1 1 391 391 141
split_gain=2546.63 1139.95 1097.95 478.923 404.147 338.706 179.911 173.086 143.796 119.968 111.975 97.4196 89.5988 86.6343 80.5855 79.398 78.9979 76.0215 71.0573 67.2294 67.0801 65.7524 61.2551 60.9688 59.8727 67.1721 57.5462
threshold=-0.39425883824369934 -1.2291473454499886 -0.85298474263107094 0.1746120078555157 1.0000000180025095e-35 -1.4484078925093731 0.34028619137497118 -1.3243683937921145 1.0000000180025095e-35 0.26791529036287415 -0.36581513528361481 -1.5861933488948645 35341.492500000015 -0.14716385111935171 -1.7794007366397382 0.51281287246722307 1.0000000180025095e-35 0.040864697395078142 -1.0000000180025095e-35 -1.6426344058948754 0.58582721626199896 -0.18481959892213282 1.0000000180025095e-35 1.0000000180025095e-35 0.12650512597654215 -0.80185022711144738 0.055555555555555559
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 9 7 5 6 10 12 19 13 15 -4 -5 16 -7 -9 -2 17 -3 -10 -1 22 -15 -12 -13 25 -19 -20
right_child=1 4 3 11 -6 8 -8 14 18 -11 20 23 -14 21 -16 -17 -18 24 26 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.032489470564277576 0.008580931935432197 -0.0034467010573208372 0.006601220300794108 0.0064088684827942125 -0.0093489536210761975 -0.0027506988060428785 -0.0068730768820262061 0.022676337957219107 0.0030034439158901837 0.0032188174328245914 0.013001697339678476 -0.0060615497396728016 0.0054250408161337655 0.0096726916942107208 0.012472777747223537 0.018299038661751161 -0.0063495729636236179 -0.0049266874092700605 0.01656102319545151 0.021392718051915595 0.035028399426616369 0.0011990297018298211 0.023223702683521839 0.00052127050057861209 -0.0022423687457464835 0.0068281215951302449 0.006797433144222975
leaf_weight=209.0271503329277 480.55427200347185 1221.4093132838607 228.32514615356922 250.12500673532486 4625.1051702797413 602.57713248580694 2065.4159540608525 240.68975750356913 268.75531180202961 521.99092903733253 317.88150671869516 988.15588192641735 416.81605044752359 368.74949985742569 769.4664498642087 338.60394345968962 772.56841462850571 138.13725469261408 345.18405581265688 358.22046270221472 57.598080143332481 513.46969811618328 250.83617767691612 487.09144775569439 484.03726246207952 608.7611648440361 245.13366980850697
leaf_count=1780 5611 16816 2647 3117 70607 8054 30175 2336 3383 6640 3525 14144 5421 4587 8726 3774 10904 1872 4100 3589 588 6534 2535 6719 6654 8136 3026
internal_value=0 -0.00427436 0.00764833 0.00409442 -0.0059938 0.00759205 -0.00327293 0.0187342 0.00458579 0.00896431 0.015823 -0.00238433 -0.00122831 0.00170141 0.0149171 0.0126126 -0.00209137 -0.000745758 0.00955885 0.025508 0.0191671 0.00475262 0.0175329 -0.00388208 0.00192697 0.0046411 0.0125258
internal_weight=0 11673.4 6501.29 4923.88 10332.3 3198.51 5707.15 1577.4 2343.87 1341.15 854.641 1725.37 3641.73 1484.8 1010.16 819.158 3224.91 2452.34 859.073 567.248 626.316 882.219 568.718 1475.25 1230.94 746.898 590.318
internal_count=246000 166610 79390 62959 150585 38979 79978 16431 29684 16025 9295 23980 49803 19175 11062 9385 44382 33478 10509 5369 6648 11121 6060 20863 16662 10008 7126
is_linear=0
shrinkage=0.0152673


Tree=17
num_leaves=28
num_cat=0
split_feature=20 20 11 20 118 164 11 118 164 11 143 20 10 11 171 414 11 90 152 119 135 165 414 392 8 7 7
split_gain=2463.28 667.229 425.649 395.944 268.737 162.182 157.452 140.765 131.416 112.143 108.936 98.8149 92.1484 87.3112 78.3343 71.8152 69.4326 67.2546 64.5322 63.2983 62.8468 59.6396 59.2635 60.6108 56.1766 97.0528 55.5328
threshold=-0.39425883824369934 -1.6199246107459455 1.0000000180025095e-35 0.33014794124083729 -0.0075539568345323735 37601.448750000003 0.010176017601760177 -0.0075539568345323735 31510.372500000001 0.084433443344334447 2.8333333333333335 -1.0752515050792439 -0.2233896442796319 1.0000000180025095e-35 11.250000000000002 -1.0000000180025095e-35 0.35726072607260734 -1.0000000180025095e-35 4.4375000000000009 -0.016388557806912989 0.51245443499392473 154407.20625000002 -1.0000000180025095e-35 -0.072201095388263983 0.51063775510204101 -0.44772034583566583 -0.49648566274802508
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 7 4 16 9 21 -3 11 -6 12 24 -9 -5 -7 -11 -2 -8 20 -13 -10 -1 -21 -24 25 -4 -17
right_child=3 2 8 13 5 14 17 10 18 15 -12 19 -14 -15 -16 26 -18 -19 -20 22 -22 -23 23 -25 -26 -27 -28
leaf_value=0.010935369599661585 -0.006719565026466567 -0.002566047366373345 0.0070295308434125889 -0.0093912434424744048 -0.0029057936844772781 0.013147417102303672 0.013691059881158671 -0.00074259374053088352 0.013837984581053803 -0.0021268354079242205 0.017812070593915801 0.0013690080155920391 0.0067740076654540411 -0.0049671579666075976 -0.001053113379305981 -0.00080368584529598973 -0.0011125782581743763 0.026361242572781909 0.00023908458144809372 0.0023786010997816211 0.029393870885931109 0.033357800499962377 0.0025216522451886867 0.013396562478737753 0.0038014506124937507 0.019058589955587794 0.0067966021132251104
leaf_weight=517.27798152714968 2321.2219772189856 1260.4215522184968 251.3899697586894 2850.1411472186446 2043.8631298467517 324.5130575671792 129.20080868154764 746.66750425100327 115.35538929700851 535.76854661107063 126.7859647795558 449.5271170437336 770.09246512502432 1656.3742475435138 123.91370205581188 308.4699951261282 666.86105637997389 460.77448827773333 36.100673161447048 277.41030809283257 136.57027330249548 29.57170907407999 159.1003517434001 508.87781577557325 136.86454094201326 428.06317818164825 799.10888764262199
leaf_count=5661 33788 16944 2909 42891 28764 4113 1273 9759 1350 7272 1591 5778 9545 24180 1647 4051 9392 4524 434 3413 1524 302 1947 5969 1620 4847 10512
internal_value=0 0.00748628 0.00524669 -0.00422514 -0.00198278 0.000535785 0.01812 0.00126758 0.009866 -0.000516404 0.00421308 0.00859364 0.0030681 -0.00776749 0.00920425 0.00244975 -0.00547146 0.0236077 0.0195897 0.00611066 0.0223239 0.0121764 0.00835484 0.0108216 0.0128228 0.0146248 0.00467183
internal_weight=0 6540.05 5403.23 11630.2 7123.72 4135.64 1136.82 2903.97 2499.26 3687.21 1643.55 2211.23 1516.76 4506.52 448.427 1643.35 2988.08 589.975 288.026 1394.92 251.926 546.85 945.388 667.978 816.318 679.453 1107.58
internal_count=246000 79390 67630 166610 99539 56359 11760 37839 29791 50599 20895 26483 19304 67071 5760 21835 43180 5797 3308 17107 2874 5963 11329 7916 9376 7756 14563
is_linear=0
shrinkage=0.0152673


Tree=18
num_leaves=28
num_cat=0
split_feature=21 21 11 21 411 17 411 119 11 390 411 141 1 8 90 135 135 411 143 10 17 1 1 6 390 8 150
split_gain=2410.32 861.867 367.276 351.657 273.315 214.864 156.87 138.076 138.038 114.257 113.102 105.965 94.6609 87.4834 82.1044 79.3226 77.4749 71.3512 70.6602 70.0991 67.7518 67.2374 64.0586 61.0471 59.3167 53.8938 52.1945
threshold=-0.86788298377637296 1.0000000180025095e-35 1.0000000180025095e-35 -1.6426344058948754 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 0.51281287246722307 1.0000000180025095e-35 0.17173031592188973 1.0000000180025095e-35 0.055555555555555559 1.0000000180025095e-35 1.0000000180025095e-35 -1.0000000180025095e-35 0.49605103280680446 0.65036452004860279 1.0000000180025095e-35 2.6111111111111112 0.08165087213294879 -1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 -0.0016541353383458643 0.033716748474408621 0.49263775510204083 0.021739130434782612
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 10 9 5 11 7 15 -3 16 12 14 18 23 -4 24 -1 22 19 -2 -9 -16 -10 -11 -5 -26 -22
right_child=1 8 4 6 -6 -7 -8 20 17 13 -12 -13 -14 -15 21 -17 -18 -19 -20 -21 26 -23 -24 -25 25 -27 -28
leaf_value=0.011451661488460869 -0.0055799475010354415 -0.008493948459828482 0.0011393993813628501 0.00052613445402758142 -0.00336610942622129 0.016095244247987948 0.0011786899032039323 0.0018262266678283335 -0.0047540187749205379 0.025920182050062093 -0.0072741913710360736 0.00043923477204163704 0.0026854570713952565 0.016668496157718034 0.0060297826288855964 0.014390185216035321 0.024696195424665442 -0.0083110976998430133 0.0051879697569995071 0.00061441672026771733 0.011627263114430615 0.013943455605146026 0.0013442681449722332 0.045194872868233184 0.012634055209525315 0.0017569838437207863 0.02029619108880289
leaf_weight=583.35336880385876 1468.4206815958023 4352.6845085099339 385.69025389105082 452.53253906965256 858.24742201715708 454.24857456237078 644.31048849970102 83.21552736312151 943.45237984508276 199.0870189666748 901.77049796283245 885.68843433260918 1022.9549549892545 231.1311672180891 592.67816992849112 238.03275883942842 127.25800940394402 604.236382804811 225.95471826940775 596.09884375333786 294.16227023303509 442.01295662671328 695.49116163700819 50.240694478154182 273.04379712790251 177.2745528370142 383.9135412722826
leaf_count=6177 20476 65779 4919 5577 11706 5276 8071 1040 13767 1950 12897 11462 13687 2416 7582 2769 1321 9011 3107 8001 3475 5360 9949 491 3193 2188 4353
internal_value=0 -0.0028403 0.000582405 0.0109163 0.00415114 0.00649182 0.00770618 0.00991202 -0.00690667 0.0177694 -0.00247908 0.00459494 -0.00117094 0.0235499 0.00717939 0.0065358 0.0138427 -0.00382212 -0.00289733 -0.0037871 0.0149566 0.00942134 -0.00216075 0.0298739 0.00445215 0.00837515 0.0165535
internal_weight=0 14429.6 7833.77 3737.56 3618.57 2760.32 2546.49 1902.17 6595.86 1191.07 4215.2 2306.07 3313.43 480.459 1420.38 1140.88 710.611 2243.18 2290.47 2064.52 761.291 1034.69 1638.94 249.328 902.851 450.318 678.076
internal_count=246000 202979 104473 43021 46305 34599 30666 22595 98506 12355 58168 29323 45271 4857 17861 13727 7498 32727 31584 28477 8868 12942 23716 2441 10958 5381 7828
is_linear=0
shrinkage=0.0152673


Tree=19
num_leaves=28
num_cat=0
split_feature=20 20 19 11 20 11 120 19 19 19 387 19 20 135 135 19 119 155 10 391 111 391 141 90 155 135 164
split_gain=2364.48 655.608 384.462 337.322 300.762 230.437 190.982 155.582 110.086 108.071 107.82 98.7862 95.0865 92.868 90.5101 85.9269 80.2947 71.9044 66.3135 60.9305 72.0048 57.3481 57.1476 66.3751 57.0128 56.7353 54.1364
threshold=-0.34931402032167075 -1.417518363968721 -0.23041488655489625 1.0000000180025095e-35 0.26791529036287415 1.0000000180025095e-35 -1.0000000180025095e-35 1.0000000180025095e-35 -0.23999248241935275 -0.24962301927574029 -0.094444699905398458 -0.36229080842168021 -1.805970119445869 0.49605103280680446 0.47174969623329294 -0.35669443217215241 -0.0080452920143027403 36011.441250000011 0.067367119901112493 0.12650512597654215 1890.5850000000003 1.0000000180025095e-35 0.055555555555555559 -1.0000000180025095e-35 36011.441250000011 0.48754556500607543 172561.78125000003
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 15 9 6 8 -4 11 -1 -3 19 -5 -7 18 22 -2 -10 -6 -11 20 21 -8 23 -13 -14 -12 -15
right_child=2 3 4 7 17 12 10 -9 16 13 25 14 24 26 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.030543383138782056 0.014843920818502958 0.014122585509496632 -0.0058982170996233598 0.024489766236292686 -0.0084333145837702898 0.026353711554056931 0.002428820453975182 -0.0017128144449079924 0.0024181391210720631 -0.0036164676229628653 -0.0038563733672301523 0.003019998635023083 0.014324825316694052 0.0041283759831252965 0.015276334630150932 0.0030794422300260789 0.011967488193803447 -0.002387197084299787 0.0021555827058532041 -0.0013006322135060441 0.019500641930931074 0.014270514994050854 0.003765216773386904 0.012444686726325673 0.029138874588062011 0.0027051319273963914 0.022289381281504796
leaf_weight=54.05702905356884 192.01715132594109 129.33499921113253 2375.9183871150017 104.08717620372772 4453.8422370180488 365.46620035916567 644.79042220115662 304.65911811590195 352.63386010378599 1344.8553498759866 1487.9823910742998 243.33239571750164 487.08622458577156 471.59331455081701 439.99189750105143 599.31573830544949 500.58920292556286 516.17880447953939 705.98570062220097 445.56141832470894 79.592165000736713 112.44947270303965 614.36204919964075 640.11108376085758 71.034697972238064 385.20842049270868 41.828316800296307
leaf_count=562 2343 1569 34598 1140 67087 3446 8518 4002 4235 18221 20872 2937 5110 6148 5072 8023 5521 7604 9124 5983 992 1446 7464 7489 707 5272 515
internal_value=0 0.00705148 -0.00430691 0.00420626 -0.00508068 0.0148777 -0.00262895 0.00843795 0.00939073 0.00051604 -0.000164323 0.009957 0.0202546 -0.000167716 0.00916921 0.0059487 0.008033 -0.00780734 -0.001625 0.00324305 0.00567296 0.0042027 0.00736727 0.00986042 0.0162364 -0.00250201 0.00563389
internal_weight=0 6871.01 11292.9 5040.14 10501.5 1830.87 5531.5 2346.54 907.28 2693.6 3155.58 2041.88 923.587 2564.26 1937.8 791.333 853.223 4970.02 2050.84 1282.39 836.832 757.24 1497.81 883.443 558.121 1873.19 513.422
internal_count=246000 83262 162738 63681 152372 19581 77681 28104 10318 35577 43083 24102 9263 34008 22962 10366 9756 74691 27345 16939 10956 9964 17890 10426 5817 26144 6663
is_linear=0
shrinkage=0.0152673


Tree=20
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 20 21 19 19 10 19 21 135 20 19 19 19 11 155 11 20 19 20 11 47 164
split_gain=2303.2 1488.64 529.515 423.26 353.421 265.643 187.815 181.945 122.356 116.538 130.235 110.004 104.369 88.4115 84.4452 83.5679 74.1156 67.8209 66.8457 66.4586 62.5653 62.2052 62.1495 55.3608 52.9271 52.469 51.4992
threshold=-0.91949617505527348 -0.78572725661621623 -0.67885497766863889 0.053086312512123736 0.1746120078555157 -0.041975004452779345 -1.6973680938911146 -1.8457901202353957 0.066137329671330417 0.026287426246023041 -0.58254360664743843 -0.32383880202376886 -1.3229527277820539 0.51245443499392473 0.12356881070161159 1.0000000180025095e-35 0.031620260851838951 1.0000000180025095e-35 0.19169416941694173 36011.441250000011 0.093784378437843804 0.35009543907003798 0.008026250660473579 -1.805970119445869 1.0000000180025095e-35 1.0000000180025095e-35 168537.81375000003
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 4 12 5 6 15 22 -4 13 10 -8 -7 17 21 -5 20 19 23 -6 24 -3 -9 25 -1 -13 -2 -12
right_child=1 3 7 14 18 11 9 8 -10 -11 26 16 -14 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.03386338738833776 0.021646954852106427 0.00018361572396871482 0.015465993441813175 -0.0064702725971647014 -0.0033097388306259873 0.010013137936134875 -0.00012142277459753816 0.0065489064347564454 -0.0037678283958869122 -0.0033637660516707539 0.01007372266971715 -0.0070956866043767851 0.013448254686314134 0.013310785794215317 -0.010478162983131237 -0.0049267783405011097 -0.0095493084871469801 0.010096594059860053 0.0048215124765590015 0.0021714043187086637 0.0058207149371424247 -0.0012752389915100235 0.00064044094423158749 0.022291619067897273 -0.0026815438216361248 0.007054904517424361 0.024595398532613732
leaf_weight=124.01891893148422 387.92426633834839 986.99696242809296 455.77715441584587 2216.8070080950856 800.75378007441759 107.98050165176392 317.59385902434587 929.67731915414333 326.91147588938475 214.10111694037914 1217.5882167741656 1496.2675703018904 457.62208452820778 345.84677564352751 2794.3138710483909 392.89904986321926 850.84680717438459 89.123737141489983 333.19459988921881 316.45551192015409 863.2852329313755 315.26727200299501 46.143532395362854 529.31407727301121 1112.9734786078334 70.021572262048721 60.666368022561073
leaf_count=980 3869 13367 4879 33335 11086 1345 4104 11252 4344 2788 13991 22152 4738 4114 44229 5573 12741 855 4318 4413 10746 4266 501 4934 15690 705 685
internal_value=0 -0.00270159 0.0109741 -0.00541556 0.00606315 -0.00272194 0.00948492 0.00678827 0.00471967 0.00717957 0.00860006 -0.00513797 0.0192426 0.00646989 -0.00870732 0.00145791 -0.00557411 0.0227971 -0.000911981 -0.00441434 0.00281901 0.00456029 0.0177381 0.0245119 -0.00521669 0.0194398 0.0107738
internal_weight=0 14586.8 3573.56 11138.8 3447.99 6127.71 2314.04 2373.48 1917.7 1809.95 1595.85 3884.52 1200.08 1590.79 5011.12 2243.18 3776.54 742.457 1133.95 2925.7 1850.28 1244.94 504.089 653.333 2609.24 457.946 1278.25
internal_count=246000 205638 40362 163591 42047 86027 26643 28855 23976 21568 18780 56341 11507 19632 77564 29686 54996 6769 15404 42255 24113 15518 5075 5914 37842 4574 14676
is_linear=0
shrinkage=0.0152673


Tree=21
num_leaves=28
num_cat=0
split_feature=21 20 20 21 21 20 1 21 20 90 20 411 1 20 11 118 20 21 149 143 10 6 8 164 20 20 135
split_gain=2221.53 1421.65 541.563 398.928 331.375 246.471 187.307 169.575 125.559 94.2516 93.4387 87.7038 86.2946 83.7554 77.5331 76.636 72.8685 72.1209 69.9018 62.4986 61.8511 58.7157 56.187 54.755 53.0389 52.2268 52.1702
threshold=-0.86788298377637296 -0.78572725661621623 -0.3826500196954733 0.053086312512123736 0.1746120078555157 -0.041975004452779345 1.0000000180025095e-35 -1.4458113164070314 -1.3243683937921145 -1.0000000180025095e-35 -1.6973680938911146 1.0000000180025095e-35 1.0000000180025095e-35 0.12356881070161159 0.18344334433443346 0.43057553956834538 -1.2270637919761371 -1.8821381414301499 -0.44132996434222038 1.166666666666667 0.08165087213294879 -0.4797911445279866 1.0000000180025095e-35 177238.01250000004 0.3451954345106808 -2.0097992159524432 0.39277035236938035
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 4 8 5 6 18 10 15 21 25 26 14 -6 -5 -7 -4 -11 -10 -3 -19 -12 -1 -23 -20 -9 -8 -2
right_child=1 3 7 13 12 11 9 24 17 16 20 -13 -14 -15 -16 -17 -18 19 23 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.013310423839514515 0.008731789814898798 0.0064736090519061772 0.0057017413961144682 -0.0064071953225037946 -0.0038847158000004278 -0.0055603972299217092 0.037134624598224017 0.0037501173091958775 0.022370362643047783 0.022590111860406263 0.00014743361213054895 -0.0089379262306440426 0.005047445289960522 -0.010412878779525415 -0.00013137767742839971 0.014434259686820494 0.011861570754422643 0.0098852191201519272 -0.00071025076618212279 0.020625818276286262 0.0073754610492310566 0.029775447196269081 0.018885401547981445 0.013019421183216627 -0.003049026946562262 0.0052609961485761457 0.022419416290696166
leaf_weight=131.02549477666616 198.89014010131359 474.45817642658949 467.6080854460597 2204.5495872050524 755.35040090978146 1801.1869191266596 12.553011901676653 806.79544345289469 187.45929855108261 351.75859039276838 567.11196910589933 1035.4410539977252 377.70352715998888 2769.0992969274521 934.87180373817682 479.9610718563199 264.2374060228467 709.62016595900059 1647.0976647362113 156.56033635884523 542.22538693994284 265.50823701173067 203.68765265494585 70.392987318336964 398.47394994646311 242.34201598167419 99.423542186617851
leaf_count=1166 2106 6199 5499 33335 10478 26450 114 10198 1711 3505 7223 15522 4926 44229 12987 5387 3010 7718 21908 1637 6339 2312 1833 880 5560 2769 999
internal_value=0 -0.00276155 0.0103574 -0.00544596 0.00584141 -0.00278069 0.00919689 0.00530321 0.0169296 0.0147683 0.00574185 -0.0051473 -0.000898731 -0.00863955 -0.00370887 0.0101367 0.0180082 0.0137273 0.00128725 0.0118414 0.00368932 0.0225293 0.0250774 -0.000140744 0.00149452 0.00689449 0.0133363
internal_weight=0 14348.7 3806.7 10937.1 3411.6 5963.45 2278.54 2152.84 1653.86 870.891 1407.65 3771.5 1133.05 4973.65 2736.06 947.569 615.996 1053.64 2191.95 866.181 1109.34 600.221 469.196 1717.49 1205.27 254.895 298.314
internal_count=246000 202979 43021 161510 41469 83946 26065 26644 16377 9398 16667 54959 15404 77564 39437 10886 6515 11066 28987 9355 13562 5311 4145 22788 15758 2883 3105
is_linear=0
shrinkage=0.0152673


Tree=22
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 19 20 19 10 19 21 155 19 1 20 1 411 167 390 141 19 19 119 11 20
split_gain=2152.02 969.598 923.256 482.834 300.458 280.637 142.923 125.568 124.983 117.118 127.195 115.315 103.694 103.438 90.3763 85.4013 78.5167 74.2948 73.9509 65.5512 65.3999 64.6038 61.9398 61.3673 57.6335 56.3955 54.0143
threshold=-0.34931402032167075 -0.99172777905286968 1.0000000180025095e-35 -1.3229527277820539 0.020441442567955586 -1.3728960730153772 0.41281381511244647 0.036948907581812025 -1.1812398945549447 1.0000000180025095e-35 -0.54216453783820895 0.0028346554504373738 -1.8457901202353957 76523.715000000011 -0.33317285005261182 1.0000000180025095e-35 -1.3243683937921145 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 0.007059712656349003 -0.16666666666666663 -0.32834624111576771 -0.24626255267163494 0.84654350417163304 1.0000000180025095e-35 -2.0097992159524432
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 7 3 16 6 13 11 12 17 10 -7 14 -2 15 -3 -5 -1 -4 21 20 -16 -12 -14 -18 -24 -10 -17
right_child=1 4 8 5 -6 9 -8 -9 25 -11 18 -13 22 -15 19 26 23 -19 -20 -21 -22 -23 24 -25 -26 -27 -28
leaf_value=0.025265578528593586 0.015741039097542184 0.012526352846143635 -0.00016068177898300413 0.0089403788878890007 -0.0091174716142449191 -0.00091471057486169688 -0.0076000470500428496 -0.0021840605335910119 -0.006821937289809777 -0.0024964411122145118 0.013043441137813671 -0.0073380439150047489 0.01972780094350856 0.027723569286794605 -0.0040818002884248561 0.034105557155057441 0.028188635144372535 0.010079601171806916 0.00151220698688731 0.011348576774043261 0.00074706680020883908 0.0067081596215918578 0.0027144550740056126 0.014388888464413274 0.010565588772665663 -0.00038838392055805991 0.015969572404123767
leaf_weight=377.51240537315607 315.82041023671627 117.70738692581654 484.22840196639299 623.78130239993334 4302.1135355196893 439.38792322576046 1486.5060263834894 349.7335888594389 878.00669489055872 398.76674170792103 697.75049015879631 736.72588897868991 70.556028306484222 117.94360277056694 1260.9032007418573 43.890603139996529 89.475633956491947 249.07598235458136 321.60252702981234 94.397237524390221 1351.9805523455143 834.09803321957588 781.67721796780825 542.94685824215412 304.93484726548195 502.43192362040281 376.32700055837631
leaf_count=3097 3339 1410 6462 6659 68334 5725 22477 4495 12862 5281 7920 10899 745 1145 17730 371 848 3063 3946 1232 18645 9855 9777 5409 3655 6951 3668
internal_value=0 -0.00416529 0.00664142 0.0103029 -0.00615149 0.00783553 -0.0036218 0.00601819 -0.00177899 0.00512252 0.00645169 -0.00195855 0.00797191 0.0141103 -0.000551973 0.0125586 0.0197048 0.00330687 0.00820286 -0.00112486 -0.00157984 0.00960116 0.00584125 0.0163641 0.00492768 -0.00448738 0.0179009
internal_weight=0 11173.1 6977.23 4863.48 9350.33 3853.55 5048.22 1822.72 2113.74 2691.61 2292.84 3561.71 1472.99 1161.94 2824.99 1044 1009.93 733.304 1853.45 2707.28 2612.88 1531.85 1157.17 632.422 1086.61 1380.44 420.218
internal_count=246000 162738 83262 53924 140727 44570 72393 22011 29338 32727 27446 49916 17516 11843 39017 10698 9354 9525 21721 37607 36375 17775 14177 6257 13432 19813 4039
is_linear=0
shrinkage=0.0152673


Tree=23
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 21 20 19 10 155 1 414 19 8 389 19 1 20 19 391 391 391 336 11 19
split_gain=2083.22 944.095 884.822 455.399 287.2 266.57 143.45 129.505 121.504 112.74 122.015 96.1573 80.393 76.9366 73.4233 72.8766 72.3997 71.8828 71.2658 66.0505 65.5851 62.8088 102.523 55.5726 56.4201 55.2368 54.3873
threshold=-0.34931402032167075 -0.94860626875739484 1.0000000180025095e-35 -1.3229527277820539 0.093766758909517342 -1.3728960730153772 0.19275266783187991 -1.4458113164070314 -1.1812398945549447 1.0000000180025095e-35 -0.55026782035434685 76523.715000000011 1.0000000180025095e-35 -1.0000000180025095e-35 0.0028346554504373738 0.51063775510204101 0.020544230716258927 0.031620260851838951 1.0000000180025095e-35 -1.805970119445869 -0.2981030959718084 0.12742144408804593 1.0000000180025095e-35 0.049180694651566131 0.3616747555977346 1.0000000180025095e-35 0.068777473923543955
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 7 3 14 6 11 17 15 18 10 -7 12 -5 -12 19 16 -2 -3 -4 -1 -8 22 -15 24 -24 -10 -9
right_child=1 4 8 5 -6 9 20 26 25 -11 13 -13 -14 21 -16 -17 -18 -19 -20 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.030808555152233262 0.018303279428584302 0.00014277757925664262 -0.00015825095054679877 0.0087417528531959186 -0.0092257524745839349 -0.00095608717447637562 0.0065948854617533439 0.003397409622257686 -0.0067572998864092286 -0.0024635096928596815 0.002392778431663935 0.026728537024078042 0.017390272435204888 0.0094581617127176033 0.0082766115491505633 0.0017296371248720491 0.0082396364896581628 -0.0067215723808314691 0.0098437060448993592 0.018925233603577802 -0.0065927719719120507 0.0046651642207866193 0.039878111879505615 0.014996695035851158 0.0082784922479980771 -0.000382582802020558 -0.0059674794894364527
leaf_weight=131.49375855177641 267.40331412106752 2000.6336170881987 484.16340727359056 628.18492700904608 4005.879284683615 433.81298980116844 90.038134343922138 814.08758790791035 872.91351501643658 397.93695311993361 439.19193714857101 120.45422667264938 425.92430721223354 832.93720694631338 130.22731198370457 211.8460270985961 458.99572417885065 431.63498929142952 251.13968665897846 762.99558532983065 2676.822622038424 412.88785304874182 56.624476775527 111.01321279257536 18.322523362934589 502.26753585040569 175.02211876213551
leaf_count=982 2975 27073 6462 6659 64162 5660 1160 10296 12862 5281 5316 1145 4039 9522 1281 2468 5201 6375 3063 7091 40619 4850 631 1261 206 6951 2409
internal_value=0 -0.00411704 0.00650653 0.0100651 -0.00615194 0.0076682 -0.00378158 0.00559649 -0.0017548 0.00502321 0.00631992 0.0137448 0.0122476 0.00801178 0.0191223 0.00966142 0.0119609 -0.00107207 0.00324717 0.0206889 -0.00615987 0.0097284 0.0117699 0.0220538 0.0323173 -0.00443607 0.00173017
internal_weight=0 11132.4 7012.49 4902.01 9205.01 3877.29 5199.13 1927.35 2110.48 2702.73 2304.79 1174.56 1054.11 1870.98 1024.72 938.245 726.399 2432.27 735.303 894.489 2766.86 1431.79 1018.9 185.96 74.947 1375.18 989.11
internal_count=246000 162738 83262 53924 139389 44570 75227 23349 29338 32727 27446 11843 10698 21786 9354 10644 8176 33448 9525 8073 41779 16470 11620 2098 837 19813 12705
is_linear=0
shrinkage=0.0152673


Tree=24
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 20 19 10 19 19 166 19 118 414 20 1 414 166 390 6 391 391 141 19
split_gain=2016.78 919.439 848.258 429.915 253.321 229.461 199.599 118.122 110.257 108.55 117.059 108.457 92.9592 96.608 88.8447 82.7612 73.3928 70.2273 68.3785 65.9379 65.2847 62.8468 60.6731 59.6185 96.0113 58.3588 55.7246
threshold=-0.34931402032167075 -0.55092222074356589 1.0000000180025095e-35 -1.3229527277820539 -1.3728960730153772 -1.4231812591257043 0.093766758909517342 -1.1812398945549447 0.49986052388137286 1.0000000180025095e-35 -0.55026782035434685 0.02880969477686041 0.099674626480683773 31639.657500000005 -0.33317285005261182 0.43057553956834538 -1.0000000180025095e-35 -1.3243683937921145 1.0000000180025095e-35 -1.0000000180025095e-35 35950.713750000003 0.46919999390664485 0.30061403508771939 0.12742144408804593 1.0000000180025095e-35 -0.055555555555555546 -0.24626255267163494
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 17 12 15 8 18 14 10 -6 20 13 21 -3 -2 -12 -1 -4 -16 -7 -5 -23 24 -18 -21 -19
right_child=1 6 7 4 9 11 -8 -9 -10 -11 16 -13 -14 -15 19 -17 23 26 -20 25 -22 22 -24 -25 -26 -27 -28
leaf_value=0.023734295530440895 0.0047778160482944967 0.010889085578026958 -0.00015585655306031294 0.010116445379300879 -0.00094225116876058468 0.0008505713599909812 -0.0091583987590233857 -0.0043851744072407077 -0.0092028869612753497 -0.0024309476852029071 0.002351631078902574 -0.0067452051385709635 -0.0028295902154783928 0.025992561121426123 -0.0069943429310196179 0.013667927824151776 0.0092427371765161116 0.026503474452730755 0.0096153565526541588 0.00045509402199130517 0.010166192026260989 0.023837640981320372 0.0089679156264305358 0.004576521569499197 0.021338906518251214 -0.0044281249936513464 0.013569074706439786
leaf_weight=390.2347567230463 489.76175493746996 102.10231658816338 484.0993964895606 672.03900964558125 433.46825193613768 1336.3733205199242 3973.9781315103173 1369.997939646244 873.66744819283485 397.11943524330854 440.05087380856276 410.82737876474857 76.053905725479126 149.38182038068771 922.2842982634902 495.65082401782274 839.29281198233366 92.705421216785908 253.16749750822783 1065.3751487657428 202.22656194865704 188.6551246792078 100.84087172150612 414.45101974904537 189.24834681302309 1220.0392727218568 556.24189504981041
leaf_count=3097 5685 1230 6462 6807 5660 18073 64162 19813 13458 5281 5316 5951 839 1388 13648 5443 9522 848 3063 15048 2572 1808 1001 4850 2098 17468 5409
internal_value=0 -0.00406915 0.00637522 0.009835 0.0075056 0.00325679 -0.00670598 -0.0017309 -0.00437385 0.00492642 0.00619175 0.000216603 0.0133925 0.0145117 -0.00309591 0.0092606 0.00783875 0.0185665 0.00318872 -0.00354457 0.00208209 0.0127135 0.0186994 0.00950519 0.011481 -0.0021479 0.0154385
internal_weight=0 11092.3 7047.05 4939.78 3900.6 2934.84 8157.45 2107.26 4183.47 2713.63 2316.51 1949.43 1186.97 1110.92 3309.8 985.413 1883.04 1039.18 737.267 3207.7 1538.6 961.535 289.496 1442.99 1028.54 2285.41 648.947
internal_count=246000 162738 83262 53924 44570 37724 125014 29338 60852 32727 27446 26596 11843 11004 47394 11128 21786 9354 9525 46164 20645 9616 2809 16470 11620 32516 6257
is_linear=0
shrinkage=0.0152673


Tree=25
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 19 19 20 387 19 164 19 19 118 164 411 20 20 90 141 90 391 391 141
split_gain=1953.16 879.895 858.045 421.539 256.999 220.301 162.696 122.173 116.923 112.031 100.915 97.8617 88.4522 90.4269 76.8334 75.8612 73.0011 70.0578 64.406 62.7325 61.742 61.3217 59.3461 58.8958 70.0553 68.6798 59.7969
threshold=-0.28709838983579977 -0.4706364644200467 1.0000000180025095e-35 -1.3229527277820539 -1.3728960730153772 -1.4458113164070314 0.093766758909517342 -1.1812398945549447 0.02880969477686041 1.0000000180025095e-35 0.49986052388137286 -0.037632662431008129 0.099674626480683773 31510.372500000001 0.0028346554504373738 -0.33317285005261182 0.43057553956834538 36029.92500000001 1.0000000180025095e-35 -1.0752515050792439 -2.0097992159524432 -1.0000000180025095e-35 0.092592592592592601 -1.0000000180025095e-35 0.12742144408804593 -0.66068996828538784 -0.27777777777777773
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 14 12 16 10 -4 17 11 15 23 13 20 19 -3 -2 -7 -17 -1 -5 -22 -23 -6 25 -25 -27
right_child=1 6 7 4 9 8 -8 -9 -10 -11 -12 -13 -14 -15 -16 18 -18 -19 -20 -21 21 22 -24 24 -26 26 -28
leaf_value=0.023211539091231526 0.0046033890442641672 0.010373845855411885 0.0031314969733843129 0.023811231855895825 0.002967925153960087 0.00067729902762271317 -0.0092272347864680963 -0.0044403852534848597 -0.0068466577628365508 -0.002455842204631764 -0.009493069435875379 0.0030007434548301481 -0.0027928167805379828 0.025150293106624356 0.0069919854224503456 -0.0025785582449049599 0.0133057870624611 0.0099290668072421814 -0.0079446752724188982 0.015322754962438742 0.0043788645539356089 0.017188365919109862 0.0074470012092765136 0.0037453755330721411 0.0044259131785299236 0.022187061295925486 0.011554173261201532
leaf_weight=478.02725556492805 448.13091234862804 89.397583372890949 739.19647591561079 100.38524846732616 287.91907586157322 1449.4646333456039 3810.5850081406534 1507.3706842623651 452.22029289230704 437.04307232797146 821.16837712749839 1309.3028629794717 75.882850863039494 151.77614095062017 139.46243667602539 2187.4743856303394 459.95005667954683 220.04182194918394 688.69259849190712 488.93878348171711 237.06752145290375 395.9952369555831 238.02944888174534 131.5137899145484 275.12662069499493 223.82868253439665 289.70203727483749
leaf_count=3856 5181 1070 9525 898 3353 19732 62083 22055 6621 5870 12754 16254 839 1383 1360 31266 4999 2796 10358 4703 2459 3841 2423 1478 3178 2427 3238
internal_value=0 -0.0042229 0.00594989 0.00932346 0.00708847 0.00273132 -0.00699745 -0.00194485 3.35004e-05 0.00466367 -0.00475083 0.00590342 0.0130533 0.0141323 0.0177026 -0.00343406 0.00902327 0.00190322 -0.00386711 0.0192361 0.0123967 0.0110655 0.0135491 0.00904068 0.0109298 0.0136875 0.0162133
internal_weight=0 10627.1 7506.57 5260 4153.57 3029.81 7597.32 2246.57 2121.73 2954.44 3786.73 2517.39 1199.14 1123.25 1106.43 2965.56 908.081 1669.51 2876.17 966.966 971.477 871.092 634.025 1208.09 920.171 645.045 513.531
internal_count=246000 156860 89140 57560 47641 39329 117531 31580 29149 35798 55448 29928 11843 11004 9919 42694 10180 22528 41624 8559 9621 8723 6264 13674 10321 7143 5665
is_linear=0
shrinkage=0.0152673


Tree=26
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 19 19 10 20 19 164 391 6 19 19 155 10 141 411 20 20 389 11 19
split_gain=1891.98 859.552 823.579 398.847 244.597 211.615 160.706 118.807 113.867 107.936 117.176 99.3748 84.4856 86.961 74.514 109.393 73.3909 72.1364 68.8441 65.4803 63.956 63.2371 62.1466 59.8598 55.9236 55.7058 51.3528
threshold=-0.28709838983579977 -0.4706364644200467 1.0000000180025095e-35 -1.3229527277820539 -1.3728960730153772 -1.4458113164070314 0.093766758909517342 -1.1812398945549447 0.02880969477686041 1.0000000180025095e-35 -0.56647438538662265 0.49986052388137286 0.044598349626972018 31510.372500000001 0.12742144408804593 -0.3717000835421887 -0.33317285005261182 0.0028346554504373738 115710.60375000002 -0.55809641532756482 0.16666666666666669 1.0000000180025095e-35 0.24707661030359654 -1.805970119445869 -0.030091581044407963 1.0000000180025095e-35 -0.070103378060431251
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 17 12 22 11 19 18 10 -6 16 13 20 15 -12 -3 23 -7 -4 24 -18 -2 -1 -5 -9 -8
right_child=1 6 7 4 9 8 26 25 -10 -11 14 -13 -14 -15 -16 -17 21 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.028094833851353099 0.012321943533670372 0.010129439482764725 -0.0037471984790257442 0.019309092351585715 -0.0011907571069427955 0.00091684014176224705 -0.0043966817099808583 -0.0066238918063977166 -0.006781909505463121 -0.0024233770433152216 0.0048927233412754557 -0.0094255598443168838 -0.00057242780527535706 0.024782658115673279 0.0028330408941987175 0.013281836883433566 -0.0025447934031079282 0.0068486356404120433 0.012000799762978435 0.006088138321228306 0.0065237590192861955 -0.0078772444046552974 0.0042471639389620687 0.017112427617161148 0.010200940877241967 -0.00050071649109222484 -0.0098325266471327704
leaf_weight=138.51046437770128 516.81799307465553 90.155710734426975 226.05130364000797 337.72358381003141 457.37072134763002 1529.1836332753301 469.49244629219174 952.07116298377514 449.58983686566353 436.14576061815023 710.78603062033653 814.47603201121092 100.73359493166208 150.70846255123615 611.53854819387197 749.64053884148598 2182.6979326456785 140.20615712553263 142.95432713627815 515.06428978592157 314.60594645887613 684.02118535712361 397.79514897614717 842.02167873829603 307.23297910392284 549.60699872300029 3310.6571234948933
leaf_count=982 5440 1070 3040 3248 5993 20732 7586 14311 6621 5870 8164 12754 1101 1345 7263 8508 31266 1360 1796 6485 3185 10358 4740 7577 2964 7744 54497
internal_value=0 -0.00417421 0.00583266 0.00911608 0.00694166 0.00268367 -0.00693287 -0.00191842 3.28629e-05 0.00457524 0.00578577 -0.00469767 0.0127272 0.013942 0.00733017 0.00920638 -0.00339171 0.0172083 0.00187123 0.00307566 0.012225 -0.00382081 0.00882167 0.0186786 0.014989 -0.0043893 -0.00916009
internal_weight=0 10587.8 7540.02 5297.22 4176.49 3036.34 7551.5 2242.79 2121.73 2965.48 2529.34 3771.35 1211 1110.27 2071.97 1460.43 2956.87 1120.74 1672.14 741.116 959.563 2866.72 914.613 980.532 644.957 1501.68 3780.15
internal_count=246000 156860 89140 57560 47641 39329 117531 31580 29149 35798 29928 55448 11843 10742 23935 16672 42694 9919 22528 9525 9397 41624 10180 8559 6212 22055 62083
is_linear=0
shrinkage=0.0152673


Tree=27
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 135 20 19 10 20 19 1 19 10 411 392 90 391 6 411 391 143 414 10
split_gain=1832.79 839.645 790.704 377.704 232.902 204.566 158.722 115.577 106.812 97.8461 89.3143 98.3367 88.0179 85.9818 81.6332 71.0108 70.4198 70.0932 64.9678 64.7641 86.3828 63.2792 62.0825 61.9374 56.2515 54.3188 59.401
threshold=-0.28709838983579977 -0.4706364644200467 1.0000000180025095e-35 -1.3229527277820539 -1.3728960730153772 -1.2483043297940404 0.093766758909517342 -1.1460985906832077 0.47174969623329294 0.49986052388137286 1.0000000180025095e-35 -0.5103007828594972 0.24707661030359654 0.023652303677922096 1.0000000180025095e-35 -0.33317285005261182 0.1604861969509683 1.0000000180025095e-35 0.079271436097884992 -1.0000000180025095e-35 0.12742144408804593 -0.4797911445279866 1.0000000180025095e-35 -0.81178185562575544 1.5000000000000002 -1.0000000180025095e-35 -0.5021975003433593
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 17 14 12 9 16 10 15 11 -6 -2 25 24 -3 -4 18 -1 -13 23 -20 -17 -21 -5 -7 -27
right_child=1 6 7 4 8 13 -8 -9 -10 -11 -12 19 -14 -15 -16 22 -18 -19 21 20 -22 -23 -24 -25 -26 26 -28
leaf_value=0.013406887076959851 0.010909502726074062 0.0098929406105140207 -0.00075847721122367562 0.0073162620274822773 -0.0028538594868174881 -0.003473779806948967 -0.0090930374471367929 -0.0044616069888161192 0.0097581070680390295 -0.0093580893264741255 -0.0043602623436176258 0.00024653009018455238 0.0027700546168006571 -0.007089745244513437 0.017227248350858912 -0.0025114005798951488 0.0086027834289378081 0.0090774454715672817 0.013792096011015506 0.00079788746940984926 0.001554781422607726 0.025266918754737397 -0.0078099963842341146 0.012225054308090172 0.019229776571598158 -0.0035544552013813879 0.0052225835898597516
leaf_weight=349.58078323304653 707.38595281541348 90.900584325194359 491.3116459697485 618.75061086565256 375.55464071035385 425.56900806725025 3750.144293859601 1446.7837721444666 690.01637409627438 807.87604295089841 336.08649084717035 373.51496987789869 557.43488462269306 384.51505983993411 493.75808333605528 2177.9922621585429 300.95750565826893 227.99720901250839 163.88307002186775 134.02645446360111 384.48056342452765 393.27590543031693 679.41509870067239 682.69583957642317 110.1812302172184 236.87310203164816 730.95401668548584
leaf_count=3119 7594 1070 6497 6270 4934 5991 62083 21356 8109 12754 4555 4413 6799 5794 4461 31266 3727 2053 1415 1549 4571 3332 10358 7667 1112 3338 9813
internal_value=0 -0.00412596 0.00571819 0.00891473 0.00679849 0.002637 -0.00686859 -0.00189254 0.00448859 -0.00464491 0.00289355 0.0041486 0.00733051 -0.000697298 0.0124123 -0.00334978 0.00278728 0.0167352 0.0186482 0.00582459 0.00755113 0.0219143 -0.00377493 0.0103617 0.00913439 0.00106092 0.00306467
internal_weight=0 10549.1 7572.86 5333.8 4199.07 3042.73 7506.33 2239.05 2976.38 3756.18 2286.36 1950.27 1264.82 1777.91 1222.69 2948.31 792.269 1134.74 906.74 1574.72 1201.2 557.159 2857.41 816.722 728.932 1393.4 967.827
internal_count=246000 156860 89140 57560 47641 39329 117531 31580 35798 55448 27689 23134 14393 24936 11843 42694 10224 9919 7866 18200 13787 4747 41624 9216 7382 19142 13151
is_linear=0
shrinkage=0.0152673


Tree=28
num_leaves=28
num_cat=0
split_feature=20 21 21 21 21 20 20 21 20 10 411 119 141 391 391 10 90 411 390 20 143 390 20 167 47 11 130
split_gain=1775.95 871.689 687.543 327.838 290.548 196.404 144.983 107.987 99.2217 94.91 101.698 75.4487 69.8948 64.6998 115.128 61.9942 61.7487 58.271 57.3542 57.3138 53.368 51.487 50.838 50.5089 49.3602 46.9095 46.52
threshold=-0.39425883824369934 -0.99172777905286968 1.0000000180025095e-35 -1.3229527277820539 0.093766758909517342 -1.4667066540297049 0.19275266783187991 -1.811377762099047 -1.1812398945549447 -0.56647438538662265 1.0000000180025095e-35 0.77145411203814074 0.092592592592592601 0.12742144408804593 1.0000000180025095e-35 -0.55809641532756482 -1.0000000180025095e-35 1.0000000180025095e-35 0.020474901307288299 -1.3243683937921145 1.7222222222222225 -0.40394244617340014 0.29395812920568981 1.0000000180025095e-35 1.0000000180025095e-35 0.18344334433443346 0.62500000000000011
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 7 3 19 6 12 18 26 15 -7 13 -9 16 14 -11 -4 -5 25 23 -1 -14 -21 -6 -3 -18 -8 -2
right_child=1 4 8 5 22 9 17 11 -10 10 -12 -13 20 -15 -16 -17 24 -19 -20 21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.021213649697166225 0.009039587293336513 -0.0037461139708389623 -0.0036924908478113689 0.0078107216828974041 -0.0072182206030613205 -0.00086579043136311663 -0.0060336942538752516 0.00127923448139449 -0.0040559197180349022 0.0075818845700305485 -0.00040192294543667088 0.0088294702751287417 0.0052449225170946093 0.0033874499518432612 0.019424809935385555 0.0058771634756145602 0.020818687225588106 -0.0092617621683563894 0.0013984278076242891 0.0070440370198966498 0.020600205999421108 0.016642999825515196 -0.010723512155572908 0.01220996243115661 0.0069716235422008516 -0.00096841727296184611 0.02011830146219629
leaf_weight=412.8700425773859 333.79360892623663 1211.9526212103665 225.20011890679598 167.6212470754981 2110.8892181813717 522.99213785678148 1307.1478559523821 1030.4358539506793 1257.9484361484647 1071.898751154542 422.31937311589718 442.51079086959362 337.52635940164328 535.6895640194416 234.77872468531132 519.50555376708508 402.44271846115589 812.85320629179478 1343.5591557733715 189.29443375021219 63.236930720508099 450.54229315370321 1824.9860273450613 47.640830896794796 73.301915265619755 639.29943062737584 123.71257908642292
leaf_count=3097 3410 17035 3040 1612 34547 6820 20189 12766 18374 11990 5151 5205 3266 6258 2526 6485 3630 12917 18306 1771 613 4079 30946 609 678 9409 1271
internal_value=0 -0.00375613 0.00609113 0.00918004 -0.00569483 0.00710206 -0.00337976 0.00557681 -0.00143837 0.00498065 0.00633479 0.00355463 0.0127551 0.00788387 0.00971943 0.00297077 0.0158866 -0.00581847 -0.000791002 0.0167323 0.00769976 0.0138206 -0.00884634 -0.0031335 0.0187082 -0.00437501 0.0120628
internal_weight=0 11228.8 6887.17 4884.51 9298.33 3831.81 5362.45 1930.45 2002.65 2787.68 2264.69 1472.95 1044.13 1842.37 1306.68 744.706 643.366 2759.3 2603.15 1052.71 400.763 639.837 3935.88 1259.59 475.745 1946.45 457.506
internal_count=246000 166610 79390 51491 143958 42544 78465 22652 27899 32745 25925 17971 9799 20774 14516 9525 5920 42515 35950 8947 3879 5850 65493 17644 4308 29598 4681
is_linear=0
shrinkage=0.0152673


Tree=29
num_leaves=28
num_cat=0
split_feature=21 21 11 411 21 16 411 119 11 411 1 141 143 90 135 10 118 2 1 2 70 126 52 409 137 10 389
split_gain=1703.63 675.142 332.39 238.971 224.41 177.152 146.035 120.029 109.282 107.412 91.2386 91.0056 75.4447 70.4487 68.5544 68.1764 65.6308 63.0886 60.4846 77.3359 59.182 52.4702 51.4988 51.2022 62.3664 51.0238 49.8557
threshold=-0.86788298377637296 0.15850492709346628 1.0000000180025095e-35 1.0000000180025095e-35 -1.7794007366397382 1.0000000180025095e-35 1.0000000180025095e-35 0.56168057210965439 0.037128712871287134 1.0000000180025095e-35 1.0000000180025095e-35 0.055555555555555559 2.6111111111111112 -1.0000000180025095e-35 1.031895504252734 0.23616261502540861 0.46726618705035977 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 0.58494208494208511 -0.59269015967373073 3.5000000000003335 -1.0000000180025095e-35 0.2142857142857143 0.052808680126356276 0.48048471629757566
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 9 5 16 11 7 14 -3 10 12 13 15 -4 25 -2 -1 -12 -15 -20 -10 -7 -18 -9 -25 -6 -23
right_child=1 8 3 -5 6 21 -8 23 20 -11 17 -13 -14 18 -16 -17 22 -19 19 -21 -22 26 -24 24 -26 -27 -28
leaf_value=0.010639542141662855 -0.0053095138053280005 -0.0082388922996643136 0.00051242373764786426 -0.0034230931710419296 0.0014399453991416446 0.025040668619795738 0.00088043855223448242 0.0084755427685958059 -0.0047210095668724899 -0.0071173060718167499 0.005999395356572847 -8.2481419697008011e-06 0.0048646621725828539 0.0048264481735373838 0.01652403406357902 0.0010674704104092819 0.021012123048840828 -0.0011990428327027171 0.017403523165778669 0.0050853611414397515 0.0033807942924067268 0.014063775359902664 0.0088679587416254872 0.01993553124824924 0.008749525580908496 0.0075736136420738037 0.0027436890438388324
leaf_weight=430.45754757523537 1790.158689044416 3661.2852060236037 409.31159413233399 927.19345408678055 583.29323655366898 75.72622923925519 755.79851397499442 347.18619490414858 1531.0010619163513 984.23246532306075 531.08769853785634 963.49259328097105 252.03161530196667 643.01172085851431 128.54431140422821 496.91915729269385 438.50432640314102 605.57025099173188 272.79892443865538 215.30713914334774 242.09353904053569 369.3748689815402 103.98153860121965 345.65403568744659 181.10683324933052 701.4931813031435 123.16344696655869
leaf_count=4039 25579 59245 5188 12954 6893 828 9020 3817 23737 14742 6990 12468 3500 8112 1346 6625 3801 8268 3115 2574 3563 4094 940 3600 1932 7633 1397
internal_value=0 -0.00251228 0.000133854 0.00336356 0.00875933 0.00541486 0.00671248 0.00863534 -0.00673028 -0.00263605 -0.00143333 0.00366265 -0.00304411 0.00596433 0.005872 -0.00391999 0.0151492 0.00215673 0.00792865 0.011993 -0.00360939 0.0131154 0.0187054 0.0130913 0.0161118 0.00479671 0.0112539
internal_weight=0 14093.8 8659.38 3999.38 4016.02 3072.19 3043.08 2287.28 5434.38 4660 3675.77 2503.92 2539.11 1540.43 1413.33 2287.08 972.943 1136.66 1131.12 488.106 1773.09 568.265 542.486 873.947 526.761 1284.79 492.538
internal_count=246000 202979 116434 50730 43021 37776 34241 25221 86545 65704 50962 31457 35704 18989 15872 32204 8780 15258 13801 5689 27300 6319 4741 9349 5532 14526 5491
is_linear=0
shrinkage=0.0152673


Tree=30
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 19 20 387 19 20 19 155 19 19 11 411 20 149 155 20 19 387 11 21
split_gain=1708.16 784.905 704.43 324.471 210.464 182.796 150.614 109.746 98.5694 95.2728 85.6048 83.0641 82.5923 77.8015 77.0782 67.9253 64.3574 62.544 58.8836 55.5754 54.3599 53.3137 52.8436 51.753 49.3487 49.2417 46.2142
threshold=-0.28709838983579977 -0.4706364644200467 1.0000000180025095e-35 -1.3229527277820539 -1.3728960730153772 -1.2483043297940404 0.093766758909517342 -1.1460985906832077 1.0000000180025095e-35 0.49986052388137286 -0.037632662431008129 0.023652303677922096 0.24707661030359654 0.099674626480683773 76523.715000000011 -0.33317285005261182 0.0028346554504373738 1.0000000180025095e-35 1.0000000180025095e-35 -2.0097992159524432 -0.28080173592252383 116907.93000000001 -1.6199246107459455 -0.070103378060431251 -1.0000000180025095e-35 1.0000000180025095e-35 -0.02046850463287465
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 16 13 12 9 17 10 15 20 21 -2 14 19 -3 22 -4 -17 -5 26 -7 -1 -8 -21 -9 -6
right_child=1 6 7 4 8 11 23 25 -10 -11 -12 -13 -14 -15 -16 18 -18 -19 -20 24 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.02347593870067315 0.010278034350480404 0.0096180919176760103 -0.00052531300418782675 0.021790757789842841 0.008301085410132223 0.00011827635604078449 -0.0040730489308559046 -0.006458990608261485 -0.0024154871810057243 -0.0092351056710885775 0.0027158711207337983 -0.0070088680808540636 0.0024613897269199375 -0.0030189692638819868 0.024154451499976932 -0.0024614310296845548 0.0059371798642841979 0.0083140782826938413 -0.0076547920979111311 0.013580134653563024 0.0059525569678984718 0.01092508604663955 0.015022069875077076 -0.0095971834215799242 0.0065145376768581519 -0.00056358233558738966 0.018521166676956465
leaf_weight=228.06304808706045 722.34242637455463 91.777083344757557 494.47626386582851 108.19749007374048 246.40455941110849 1279.7894221618772 458.22300961986184 902.23314014077187 435.88340107351542 796.02216506004333 1326.4964570552111 381.59067075327039 565.50622849166393 76.928678944706917 124.39873151481152 2170.8437641747296 145.06253194063902 297.73754400014877 668.94004456326365 480.00812379270792 808.97342648357153 116.04673088341951 797.59623978286982 3212.0986001826823 458.26115766912699 526.54888658970594 184.68821574002504
leaf_count=1576 7594 1070 6637 922 2655 17671 7586 13849 5870 12754 16254 5794 6799 839 1066 31266 1360 3587 10358 4371 9015 1471 6983 54497 4645 7507 2004
internal_value=0 -0.00402036 0.00547448 0.00844166 0.00647708 0.00247353 -0.00671229 -0.00176374 0.00428162 -0.00454525 0.00542267 -0.000695422 0.0068537 0.0117509 0.0127295 -0.00326812 0.0155638 0.00278649 -0.00368846 0.0113583 0.00830983 0.00102473 0.016915 -0.00891028 0.0101411 -0.00429315 0.0127074
internal_weight=0 10463.2 7641.96 5420.96 4250.24 3065.28 7397.9 2221 3002.45 3727.58 2566.56 1777.43 1287.85 1247.79 1170.87 2931.56 1170.72 792.214 2839.78 1046.47 1240.07 1395.84 1025.66 3670.32 938.269 1428.78 431.093
internal_count=246000 156860 89140 57560 47641 39329 117531 31580 35798 55448 29928 24936 14393 11843 11004 42694 9919 10224 41624 9938 13674 19142 8559 62083 9016 21356 4659
is_linear=0
shrinkage=0.0152673


Tree=31
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 21 21 20 1 20 11 414 1 20 118 11 109 414 391 51 161 20 1 130 155 391 391
split_gain=1655.76 723.627 709.634 323.981 215.682 174.178 138.908 113.151 102.951 88.5095 73.3451 70.1939 67.1475 63.3187 62.2805 62.0971 60.0643 53.9971 53.9909 56.2367 57.1122 53.7371 48.0964 47.0091 43.9717 45.789 54.0688
threshold=-0.23944851334767706 -0.4706364644200467 1.0000000180025095e-35 -1.3471229168525309 -1.1194625484164258 -1.4458113164070314 0.14236527037091054 -1.1460985906832077 1.0000000180025095e-35 0.49986052388137286 1.0000000180025095e-35 -1.0000000180025095e-35 1.0000000180025095e-35 -0.99722827966603267 0.43057553956834538 0.34185918591859193 -0.58333333333333315 -1.0000000180025095e-35 -0.81178185562575544 0.009250000000000003 6791.5350000000008 -2.0097992159524432 1.0000000180025095e-35 0.12500000000000003 295882.22250000009 0.1379033485638034 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 5 3 13 8 14 9 12 18 16 23 -7 -4 -1 -2 -13 -3 -12 -5 20 -20 -10 -9 -6 25 26 -19
right_child=1 6 7 4 10 11 -8 22 21 -11 17 15 -14 -15 -16 -17 -18 24 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.018619916716265183 0.0036729480793781721 -0.00052653849485962919 -0.00047037890176695964 -0.0038660741868067968 -0.0011111970452767378 -0.0041890376088557224 -0.0089975339346533099 -0.0062877044279305129 0.029238233332720465 -0.0091481839622041747 0.00084201805729132006 -0.00026670677749959402 0.0088503374166978531 0.011500850654450202 0.011721962607715254 0.0069800698888458964 -0.0051156351260965615 0.0072429173783870584 0.0085889485511127846 -0.0012792921425959954 0.024324749607962472 0.013470714930157199 -0.00055044852079826978 0.0051358372852585441 0.030677101766205798 0.0016483277170419187 0.018162907504886593
leaf_weight=609.68786499649286 443.95667123794556 1046.4478936307132 519.89045808464289 91.792829714715481 900.6173837184906 695.99198833107948 3407.5030678771436 1016.0987657383084 55.733871519565582 821.80856593325734 364.52121389657259 973.59278251975775 274.12846737354994 580.98525003343821 461.8422065526247 383.03941998630762 1845.6045779101551 592.76980033516884 830.00467678159475 123.87916829437017 58.18561128526926 672.08530429005623 517.82064598426223 406.90376728400588 19.169324569404125 253.81024490296841 130.728909984231
leaf_count=4651 4982 15032 6943 981 11521 9873 58162 15567 419 13310 4445 13388 3281 5379 4811 4940 27533 6563 8667 1311 557 6350 7597 5218 202 2944 1373
internal_value=0 -0.00413159 0.00516445 0.0080695 0.00619181 0.00221263 -0.00676844 -0.0019334 0.0102284 -0.00472038 0.00341712 -0.00024408 0.00273741 0.0151564 0.00778871 0.00177337 -0.00345845 0.00589885 0.00727065 0.00829035 0.00963536 0.0146984 -0.00435722 0.000826379 0.00773896 0.00727348 0.00923318
internal_weight=0 10079.8 8018.81 5690.88 4500.2 2958.42 7121.36 2327.94 1831.68 3713.86 2668.52 2052.62 794.019 1190.67 905.799 1356.63 2892.05 1361 1103.86 1012.07 888.19 727.819 1533.92 1307.52 996.478 977.309 723.499
internal_count=246000 152031 93969 60581 50551 37994 114037 33388 18285 55875 32266 28201 10224 10030 9793 18328 42565 15527 11516 10535 9224 6769 23164 16739 11082 10880 7936
is_linear=0
shrinkage=0.0152673


Tree=32
num_leaves=28
num_cat=0
split_feature=21 21 19 11 19 17 21 135 19 90 155 141 19 11 2 1 390 6 8 8 6 70 390 6 8 19 161
split_gain=1543.73 630.023 395.617 284.182 251.362 157.547 156.984 115.125 107.539 96.262 95.6764 93.5008 83.8264 75.154 68.4604 88.4795 67.0467 64.4635 88.4699 64.4622 86.95 63.8471 63.0209 60.5275 59.4995 59.2224 54.1615
threshold=-0.86788298377637296 0.15850492709346628 1.0000000180025095e-35 1.0000000180025095e-35 0.0028346554504373738 1.0000000180025095e-35 -1.7794007366397382 0.43772782503037672 -0.20494525875886938 -1.0000000180025095e-35 78807.645000000004 0.055555555555555559 -0.29070757998552249 0.037128712871287134 1.0000000180025095e-35 1.0000000180025095e-35 -0.11176200057445475 -0.49285714285714283 1.0000000180025095e-35 1.0000000180025095e-35 -0.017790309106098575 0.58494208494208511 -0.16857635277102093 -0.02353383458646616 1.0000000180025095e-35 -0.2836795503754817 2261.2387500000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 10 6 9 22 17 -3 -5 12 14 -2 -10 15 -11 -14 -8 23 20 -18 -15 -1 -19 -24 -9 -27
right_child=1 8 -4 5 -6 -7 7 25 13 11 -12 -13 16 21 -16 -17 19 18 -20 -21 -22 -23 24 -25 -26 26 -28
leaf_value=0.010345253412324635 0.010150845641249856 0.0018236512841553008 -0.0066928236295219091 -0.0013294310787513482 0 0.012076593749688879 0.00013382464021066446 0.026847570182509203 -0.0083707915148971829 0.0063828335889859148 0.0066880517280293716 0.0009523258259700961 -0.0048297991306482935 -0.0055540258028612781 0.0022996790008393167 0.016583083474513056 0.0009201368363965616 0.0090168606020145422 0.0039014493288446182 -0.0027757760818031114 0.016274647346979493 0.0033683987908085891 0.023437298829978789 0.019999641985951971 0.012858667804409021 0.0090908775976866578 0.01950014771362352
leaf_weight=327.91676530987024 126.0497694760561 333.69276016205549 1615.5329833105206 746.35431316494942 711.39092663675547 585.19630270823836 348.26007355004549 70.058166645467281 3440.2612557634711 562.54183604195714 320.55743478238583 797.02998046949506 1531.2960628941655 1353.3987379670143 390.63055932894349 310.49442961812019 542.04717726632953 564.12586487084627 787.20004981011152 1031.1405384913087 102.3446498401463 215.41686098650098 301.07760670781136 150.43768040090799 221.38351855427027 444.51521196216345 161.87107738107443
leaf_count=2925 1495 5102 24291 9644 8494 6369 3780 631 56868 6977 4133 10157 21862 21383 4811 3521 7307 6022 8936 14526 1341 3192 2444 1554 1942 4703 1590
internal_value=0 -0.00242261 0.000119739 0.00168326 0.00824065 0.00486573 0.00997813 0.00805973 -0.0065456 0.00335844 -0.00126928 0.00506073 -0.00203773 -0.00710502 0.00764421 0.010024 -0.00252028 0.00607887 0.00745123 -0.000403782 0.0033773 -0.00432276 0.0156637 0.0113468 0.018979 0.0134603 0.0118902
internal_weight=0 14004 8661.22 7045.68 4088.24 3392.25 3376.85 2526.47 5342.77 2807.05 3653.44 2060.7 3332.88 5009.08 1263.67 873.036 3206.83 1850.02 1501.76 1675.53 644.392 1568.82 850.378 714.564 522.461 676.444 606.386
internal_count=246000 202979 116434 92143 43021 41479 34527 27216 86545 35110 50664 25466 46531 81443 15309 10498 45036 20292 16512 23174 8648 24575 7311 7576 4386 6924 6293
is_linear=0
shrinkage=0.0152673


Tree=33
num_leaves=28
num_cat=0
split_feature=21 21 19 11 19 414 21 17 11 19 155 143 141 19 19 11 2 130 1 1 2 155 70 388 8 164 57
split_gain=1490.58 615.649 385.265 274.405 240.442 175.253 148.733 112.431 105.686 104.628 92.5216 90.3102 82.8542 80.9245 71.7854 70.0617 68.6752 53.0961 51.6642 49.508 50.7262 47.8794 52.7724 47.5028 77.4197 47.4294 45.6027
threshold=-0.86788298377637296 0.15850492709346628 1.0000000180025095e-35 1.0000000180025095e-35 0.0028346554504373738 -1.0000000180025095e-35 -1.7794007366397382 1.0000000180025095e-35 0.037128712871287134 -0.31528071226839544 78807.645000000004 1.3888888888888891 0.055555555555555559 -0.29070757998552249 0.049783175800385444 0.010176017601760177 1.0000000180025095e-35 2.0416666666666674 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 33998.602500000008 0.58494208494208511 0.45678925033826762 1.0000000180025095e-35 146517.12000000002 0.031200000000000023
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 10 6 -5 23 12 -3 -8 13 15 16 -2 21 -11 18 19 -7 -15 -21 22 -10 24 -1 -14 -17
right_child=1 8 -4 5 -6 7 9 -9 14 11 -12 -13 25 17 -16 26 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.024008540642058571 0.0099140103678295247 -0.0079914922080237451 -0.0066287465547737439 -0.0009534959774426038 0 0.0071896670609326186 0.018293226630309606 0.013842048476866141 -0.0040819870078836465 0.0026109593339123495 0.0065496279116964689 0.01401557054005315 0.00036064713446985687 -0.0044895728254129271 -0.0099449672648744131 0.0098389231274176748 0.0025719364905838469 0.0040137001060781587 0.014920188516137758 0.0034951555305863602 -0.0034683347084252078 0.0073232052655367872 0.0044028810406666679 0.010413179770732793 0.012402116354192217 0.015205749200957693 0.0012906961595490147
leaf_weight=262.51438225805759 127.08723223209381 3566.243721909821 1606.3193655572832 910.02267771214247 711.39092663675547 529.84772335737944 207.76419850438833 444.03086068853736 1107.2134802043438 932.49704880267382 322.32526935636997 359.04361797869205 723.24089397490025 1951.2201981246471 319.23559454455972 864.90402509272099 410.35721618309617 267.01148819178343 334.03460486978292 448.75994735211134 532.99668137356639 118.91851009055972 200.87409751117229 311.78024772554636 285.59692407399416 53.839600440114737 177.99717765301466
leaf_count=2105 1495 59245 24291 12023 8494 6382 1929 4639 17311 10593 4133 3787 9117 27786 5256 8960 4942 3752 3728 6026 7472 1802 2931 2701 2505 648 1947
internal_value=0 -0.00239104 0.000117732 0.0016553 0.00806472 0.00477278 0.00975252 0.00686467 -0.00648275 0.00788737 -0.00125132 0.00695585 0.00534867 -0.00201018 -0.00339572 0.00566676 0.00774612 -0.0024872 0.0101922 -0.00308238 -0.000275938 -0.00192298 -0.00277155 0.0152529 0.0179844 0.00140462 0.00838926
internal_weight=0 13973.6 8661.09 7054.77 4113.49 3405.37 3402.1 2495.35 5312.49 2542.21 3649.4 2334.44 2051.32 3327.08 1746.24 1975.4 1274.24 3199.99 863.882 2932.98 981.757 1427.01 1308.09 859.892 548.111 777.08 1042.9
internal_count=246000 202979 116434 92143 43021 41479 34527 29456 86545 27216 50664 25287 24817 46531 27300 21500 15052 45036 10110 41284 13498 22044 20242 7311 4610 9765 10907
is_linear=0
shrinkage=0.0152673


Tree=34
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 20 21 135 21 387 411 391 6 8 6 155 387 149 10 20 391 392 11 20 411 10 391
split_gain=1579.54 756.111 530.799 361.506 261.607 132.213 121.66 99.1021 97.7802 83.2857 78.6862 72.9099 114.38 91.0391 90.3629 71.9372 69.1609 66.4762 63.5173 62.3369 48.0894 48.6062 48.0191 47.519 47.3701 44.5543 43.8937
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.4706364644200467 -1.2291473454499886 -1.126355914706455 -1.1460985906832077 -1.6426344058948754 0.50455650060753354 0.19068494058228019 -1.0000000180025095e-35 1.0000000180025095e-35 0.12742144408804593 -0.38559732664995816 1.0000000180025095e-35 -0.017790309106098575 295882.22250000009 -0.028394675390716356 -0.27498209239536847 0.1604861969509683 0.49986052388137286 -0.80185022711144738 0.16260453131065719 0.05528052805280529 -1.805970119445869 1.0000000180025095e-35 -0.07382227715973079 0.12650512597654215
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 10 9 18 -2 11 19 23 16 12 25 14 -14 -9 -1 26 -3 24 -11 -22 -7 -5 -4 -6 -8
right_child=2 5 8 4 7 22 17 15 -10 20 -12 -13 13 -15 -16 -17 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.018253694427837353 0.0077187408398185827 -0.00054510069703188932 -0.0029474221745093032 0.019187296986413072 -0.0061699797782757979 -0.0062097445763839194 0.0068857957795935947 0.0065340878838930127 -0.0093927120400119166 -0.0043577989619256133 0.0066698706431345253 -0.0022863171993057554 0.0070915628717757064 0.0010681579633413827 0.021615920210196819 0.031522367924908735 0.01119727236806353 -0.0025558738814179024 0.0083384023504421458 -0.0090351857201709986 0.0046185201268253281 0.012562641107660664 -0.0012647205545334493 0.010972299064975375 -0.0080014867418305158 0.0013412821432918578 -0.0012759447822401956
leaf_weight=681.74894766509533 515.32357002049685 485.28813661634922 1784.7683897204697 228.24895323067904 269.12575728073716 1324.1747360937297 366.15854454785585 693.8082606382668 2775.1704131327569 85.783336319029331 352.49587184935808 936.31632994487882 386.67919825389981 381.94653299823403 136.30326409265399 27.992961443960667 639.59567834436893 1327.0956772305071 303.84991413354874 844.38978463411331 483.90460593253374 291.23204923421144 707.53956971690059 637.66375496983528 575.66615650057793 577.98438620939851 261.5419899225235
leaf_count=5676 5370 6497 26378 1859 3591 21261 4825 8392 48587 921 3209 12167 4660 4772 1580 311 5643 18128 3727 13868 5279 2855 10545 6162 9190 6947 3600
internal_value=0 0.00421341 -0.0048306 0.00696662 0.0049556 -0.00243088 0.00111983 0.00250001 -0.00729 0.00979876 0.0131316 0.00114715 0.00298733 0.00676228 0.0109013 0.00752434 0.0148472 -0.000615704 0.00286505 -0.00546585 0.00641293 0.00761755 -0.00449245 0.0131522 -0.00418447 -0.00103512 0.00347116
internal_weight=0 9631.68 8450.11 6810.83 5136.99 2820.85 2470.12 3410.16 5979.99 1726.83 1673.84 2688.36 1752.04 904.929 522.982 721.801 1321.34 1954.8 789.138 3204.82 860.92 775.137 2031.71 865.913 2360.43 847.11 627.701
internal_count=246000 116054 129946 74024 59496 42030 31923 42420 98023 17076 14528 33717 21550 11012 6240 8703 11319 26553 10224 49436 9055 8134 31806 8021 35568 10538 8425
is_linear=0
shrinkage=0.0152673


Tree=35
num_leaves=28
num_cat=0
split_feature=11 411 120 120 391 6 8 135 6 411 10 157 17 135 10 155 164 144 392 14 391 391 143 17 130 391 111
split_gain=809.354 387.379 255.072 240.043 178.254 213.301 191.166 156.897 137.488 118.274 122.56 81.8747 71.9147 71.0284 70.553 70.3672 66.5804 60.9808 60.604 51.9544 51.269 112.702 50.5921 49.6051 44.6843 43.1817 42.147
threshold=1.0000000180025095e-35 1.0000000180025095e-35 -1.0000000180025095e-35 -0.038848263254113342 0.12742144408804593 -0.42439431913116116 1.0000000180025095e-35 0.52035236938031604 -0.028517126148705094 1.0000000180025095e-35 0.27132262051915951 281.25000000000006 1.0000000180025095e-35 0.52035236938031604 0.20237604724625741 63.202500000000008 33462.978750000002 0.33035714285714296 -0.15385759837996296 -1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 2.1666666666666674 -1.0000000180025095e-35 0.54166666666666685 -0.82711714898909583 842.67000000000019
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 14 15 5 13 8 9 12 10 20 18 -7 -4 -2 24 -6 -18 -9 -12 -5 -22 26 -10 -1 -20 -3
right_child=1 22 4 7 16 6 -8 11 23 -11 19 -13 -14 -15 -16 -17 17 -19 25 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=-0.0072600804619930535 -0.0017877564170024542 -0.0039828699034161457 0.0030868925466589186 -0.0086720798888336292 0.00096466564378693421 0.011355369269984209 0.005380536277917361 -0.00034921627466655546 0.0065247054973431159 -0.0067541334598198678 -0.0043608029397829845 0.017265083914084076 0.02262515824105199 0.011827028537988699 0.0039687939298494396 -0.0003279986492825119 0.0055956106085147663 0.026190434536301523 -0.0050191782534636156 0.0057571737843611316 0.014916742764074403 -0.0023793258278293132 0.0061127343067253299 0.02765993815349669 -0.0033970887259525255 0.0087687748757973947 0.0027818039345732827
leaf_weight=2893.5187245160341 1022.460343349725 1547.0432345941663 1013.6424994729459 276.28810454532504 967.82979589700699 698.16320561245084 505.32049052044749 587.89001429826021 30.066546835005283 1000.6160666979849 139.65552837774158 101.64909991249442 165.95378442108631 277.49415135011077 961.86724135652184 522.45011828094721 123.75088295340538 46.764904152601957 59.777381584048271 738.22575472667813 91.002829387784004 2290.1339278370142 151.79754829779267 270.7269355468452 934.07665921747684 409.713588103652 247.48061062768102
leaf_count=44598 14406 21377 11711 4028 12007 7822 6000 8185 362 14804 1831 1216 1616 2993 12394 7577 1457 501 825 9282 1172 32368 2044 2804 14225 5202 3193
internal_value=0 0.00359991 0.0054969 -0.00290179 0.00767199 0.00964678 0.0132525 -0.000837152 0.0166578 -0.00211947 -0.000804797 0.00417286 0.0135351 0.00497398 0.000998131 -0.00560249 0.00252582 0.0113216 0.00290258 0.00413652 -0.0024408 -0.00171326 -0.00232519 0.0255835 -0.00631999 0.00699235 -0.00304465
internal_weight=0 8030.36 6084.04 10045 4099.71 2961.37 1670.23 5694.95 1164.91 4535.92 3535.31 1159.03 864.117 1291.14 1984.33 4350.05 1138.35 170.516 1057.38 877.881 2657.42 2381.14 1946.32 300.793 3827.6 469.491 1794.52
internal_count=246000 100687 74073 145313 47273 33308 18604 78913 12604 63485 48681 15428 9438 14704 26800 66400 13965 1958 14212 11113 37568 33540 26614 3166 58823 6027 24570
is_linear=0
shrinkage=0.0152673


Tree=36
num_leaves=28
num_cat=0
split_feature=21 21 411 11 411 17 21 119 11 135 126 10 9 135 70 70 120 118 10 389 130 8 17 21 411 10 135
split_gain=1383.98 581.365 287.822 283.032 177.753 146.461 140.292 105.275 97.742 81.5205 72.1472 66.8866 66.1155 59.5243 56.6227 53.8223 45.0368 44.6657 44.2367 42.5945 41.2039 41.0066 39.9052 39.8642 39.5672 44.7091 39.5362
threshold=-0.86788298377637296 0.1746120078555157 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 -1.7794007366397382 0.56168057210965439 0.12953795379537955 0.57624544349939255 -0.28167179006942039 0.15293228952067026 0.70188133140376296 1.031895504252734 -0.30540540540540534 0.58494208494208511 -1.0000000180025095e-35 0.3140287769784173 -0.58254360664743843 0.068263792211535682 2.8750000000000004 1.0000000180025095e-35 1.0000000180025095e-35 -2.0089485232886477 1.0000000180025095e-35 -0.2754429336629583 0.3976306196840827
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 9 6 10 17 13 24 11 14 -2 26 18 -5 -10 -12 -1 -8 21 -18 -20 -4 -6 25 -3 -9
right_child=1 8 22 5 23 -7 7 12 15 -11 16 -13 -14 -15 -16 -17 20 -19 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.010067964086522083 -0.0038681214789891383 -0.0086145814531165196 -0.0061106491200454086 0.00057113558386943811 0.010559739193503677 0.012082893945133871 -0.0019381879577286085 0.010747736458799244 -0.0043210740879745862 0.0035861471146402227 -0.0028764160490674737 0.0010760509755030113 0.00088521311220546403 0.014764007366363919 0.0090501445580450455 0.0038014752155875508 0.0022193806379565474 0.017848808661124701 0.013020314411126705 0.0022994184428349728 0.014076076603024032 0.0045805852009404647 9.749620967804621e-05 0.0010509354250490489 -0.010742754271193587 -0.0047177944889930179 0.017992859551122876
leaf_weight=272.80925165116787 2126.2863565795124 1562.8069125115871 1613.4641712605953 253.94256414473057 116.352923437953 546.90819269046187 231.67600829154253 517.14313342422247 1333.1641494110227 644.93550122901797 415.1311480589211 907.27438910678029 116.32241785526276 134.98133840411901 685.64197101816535 220.42704567313194 1180.949978068471 505.55580280721188 246.2639581002295 538.52372363954782 72.753473199903965 305.91522022336721 280.37080574780703 901.51572160795331 811.57738779112697 1251.9798936732113 277.89870783686638
leaf_count=2412 30662 26380 24185 3348 1029 5778 2723 5343 21171 8765 5447 12054 1323 1346 8045 3239 14479 4106 2505 5857 912 3441 3765 10253 13950 20799 2683
internal_value=0 -0.00232535 7.84175e-05 0.00153901 0.00770684 0.00489424 0.00950135 0.00764456 -0.00637704 -0.00133665 0.00338267 -0.00238643 0.0117222 0.00508706 0.00676887 -0.00316239 0.0014701 0.0151368 0.00409028 0.0053793 0.00291688 0.00836452 -0.00518682 0.00214875 -0.00775148 -0.00688505 0.0132956
internal_weight=0 13907.6 8727.66 6833.82 4164.96 3155.33 3147.09 2368.72 5179.96 3678.5 2608.42 3033.56 911.364 1457.36 939.585 1553.59 1668.83 778.365 1322.38 1090.7 1253.7 552.179 1893.83 1017.87 3626.36 2814.79 795.042
internal_count=246000 202979 117440 89490 43021 38009 31739 25221 85539 51481 32231 42716 9349 15872 11393 24410 20838 6518 14526 11803 15391 5946 27950 11282 61129 47179 8026
is_linear=0
shrinkage=0.0152673


Tree=37
num_leaves=28
num_cat=0
split_feature=20 20 19 120 10 19 11 135 135 19 19 19 7 8 6 391 6 155 149 20 118 157 10 155 10 120 19
split_gain=1510.78 514.167 235.565 227.917 182.374 157.155 146.774 134.984 105.624 97.2508 96.9188 96.2038 91.8293 131.947 104.715 85.0329 151.446 79.5125 74.495 72.6669 66.8635 63.9764 62.9284 51.9856 49.187 45.7837 45.0833
threshold=-0.049110989848547566 -1.126355914706455 -0.23041488655489625 -0.014168190127970747 -0.58254360664743843 1.0000000180025095e-35 0.093784378437843804 0.49605103280680446 0.86482381530984209 0.12336000311721791 0.084187341036184873 -0.31528071226839544 -0.44772034583566583 1.0000000180025095e-35 -0.14897243107769423 0.1379033485638034 -0.37970342522974093 33998.602500000008 -0.26242184281714837 0.3451954345106808 -0.085251798561151074 191.25000000000003 -0.14716385111935171 186312.20625000002 -0.16446916632330721 0.46389396709323588 -0.35669443217215241
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 26 11 -1 8 19 9 12 15 17 -3 -6 14 -14 16 24 25 -18 20 -4 -22 -13 -9 -5 -8 -2
right_child=2 3 6 7 5 -7 10 23 -10 -11 -12 22 13 -15 -16 -17 18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.0016988726784945315 0.012247170759435839 0.014090903811147859 -0.0079433226645095993 -0.0053136105602229356 0.0058484657650677199 0 -0.0037450681573616522 0.0079293191007792224 0.021149332388989618 -0.0065105775944209352 -0.0087595230406069466 -0.005474120971291685 0.012427377655524898 0.0083296954664648388 0.024139122341235414 -0.00066812073197651317 0.015038413560708558 0.006821873454854706 0.0061652604359006373 -0.0088323608480848272 -0.003552704030268737 0.014737687105403772 -0.00043054408480202607 0.021272708780907573 0.0026192022700348579 0.0013324122422834058 0.0022329435540392756
leaf_weight=623.06985118240118 139.72305535152555 82.714167300611734 1130.7132242321968 245.1193514354527 579.22885079681873 273.15709055587649 1427.7707300037146 829.39031665399671 274.82735069096088 263.48274270445108 489.11455460265279 1023.5342694558203 407.74398134276271 701.8670668490231 324.36205563694239 915.46298883110285 329.38429436087608 251.56894068792462 687.99763651564717 2514.4445205852389 1384.9344379901886 45.690220832824707 1330.3233398348093 75.15488064661622 705.28061348199844 579.59375051781535 431.74915431067348
leaf_count=7372 1635 980 18390 3292 5638 3091 21586 9735 2424 3757 7790 15137 3799 7026 2893 11789 3748 3399 8106 41958 20797 598 18204 812 8251 7908 5885
internal_value=0 0.00409978 -0.00475192 0.00163187 0.00912479 0.0109275 -0.00544364 0.00385177 0.0122341 0.00235339 -0.00259612 -0.00205541 0.0110105 0.0130881 0.017634 0.00316699 0.00495572 -0.00125688 0.0090494 -0.00698333 -0.00516403 -0.00296018 -0.00262783 0.00905255 0.000562912 -0.00227448 0.00470084
internal_weight=0 9672.1 8395.3 6487.84 3184.26 2561.19 7823.83 4051.27 2288.03 3146.73 2748.05 2436.57 2013.2 1433.97 732.106 2883.24 1967.78 2258.93 1017.38 5075.78 2561.34 1430.62 2353.86 904.545 950.4 2007.36 571.472
internal_count=246000 116054 129946 83811 32243 24871 122426 49490 21780 38943 40683 34321 19356 13718 6692 35186 23397 32893 11854 81743 39785 21395 33341 10547 11543 29494 7520
is_linear=0
shrinkage=0.0152673


Tree=38
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 20 21 21 1 135 20 391 90 391 155 155 1 20 141 1 149 135 86 7 90 141 167
split_gain=1466.2 683.624 505.214 324.888 236.334 124.768 113.934 91.9647 88.6689 88.0922 67.3128 66.5644 98.2821 95.0855 64.7416 62.7717 62.2767 61.4035 60.6761 60.1858 51.6843 50.7886 45.8242 45.6 45.5665 44.941 44.4217
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.2291473454499886 -1.126355914706455 -1.1460985906832077 -1.6426344058948754 0.19068494058228019 1.0000000180025095e-35 0.50455650060753354 -1.0967390244420938 0.12742144408804593 -1.0000000180025095e-35 -0.80185022711144738 295882.22250000009 38778.806250000009 1.0000000180025095e-35 0.49986052388137286 -0.12962962962962959 1.0000000180025095e-35 -0.57728082535034619 0.5871810449574727 1.0000000180025095e-35 -0.44772034583566583 -1.0000000180025095e-35 1.0000000180025095e-35 1.7500000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 10 8 16 -2 17 21 11 -1 12 -6 -14 -11 20 -3 -4 23 26 -8 22 -5 -15 -10 -12 -7
right_child=2 5 7 4 9 19 15 -9 24 14 25 -13 13 18 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.016184667504947892 0.0073847714718250071 -0.00032311674233359219 -0.0040871421153725815 0.003502881255384217 -0.0026323455714916629 -0.0064614585502166463 0.0050437705806880657 -0.0092165926404924881 0.0071478759636112521 0.0061093237818387307 0.012758727584501268 -0.0022104153893035493 -0.0038093612659009552 0.0030741592369690918 0.029311567773892131 0.0061409701241289926 0.0086438387785271048 -0.0089583649384211671 0.0038687295093479566 -0.00064243975708073531 -0.0027653738411605473 0.013010413028863551 0.015691547828244157 0.014369923232022663 0.01588211625543998 0.0063118228998248118 0.029948295099861452
leaf_weight=668.71979819983244 521.61550275981426 515.47975423932076 2317.4995717331767 752.99536672979593 533.28992601856589 1323.5958049409091 227.04725602641702 2714.9542118124664 198.52856708317995 705.50591427460313 582.65414080023766 931.79058546945453 222.11330126598477 114.96029879897833 29.271236434578896 274.21516986936331 276.12199664115906 823.20305439457297 567.37284287437797 679.40269216522574 1482.1652042232454 217.73092324286699 80.025898471474648 326.55178878456354 508.80402407050133 459.12565459311008 7.5755602680146685
leaf_count=4896 5370 6943 35202 7886 6790 21257 3090 48587 1905 8392 5314 12167 2776 1359 311 3479 3281 13744 6882 10432 20474 2081 776 3743 4428 4318 117
internal_value=0 0.0040246 -0.00469902 0.00660768 0.00470237 -0.00233214 0.00103571 -0.00715385 0.00925549 0.00236613 0.012381 0.00108474 0.00283028 0.00520427 0.00705382 -0.000629964 0.00279451 -0.00536733 0.00719813 -0.00435523 -0.0017222 0.00642362 0.00468829 0.0114522 0.0134463 0.00992804 -0.00624291
internal_weight=0 9701.62 8360.7 6899.44 5188.94 2802.18 2505.04 5855.66 1758.08 3430.86 1710.5 2696.08 1764.29 1231 734.777 1983.43 791.602 3140.7 1008.88 2010.57 1709.21 1050.75 833.021 441.512 707.333 1041.78 1331.17
internal_count=246000 116054 129946 74024 59496 42030 32413 97533 17076 42420 14528 33717 21550 14760 8703 27043 10224 48946 11984 31806 23564 10743 8662 5102 6333 9632 21374
is_linear=0
shrinkage=0.0152673


Tree=39
num_leaves=28
num_cat=0
split_feature=20 20 11 11 10 411 143 20 155 149 20 10 118 164 141 411 157 389 141 144 1 119 387 90 2 10 11
split_gain=1423.12 473.252 239.784 186.528 158.94 109.239 107.464 104.178 87.8589 86.2728 86.1853 84.3632 79.6384 78.0649 76.8693 61.655 59.1715 57.3754 57.6422 56.1493 54.5501 54.2543 51.8051 49.4743 48.9555 47.9586 44.2694
threshold=-0.049110989848547566 -1.1812398945549447 1.0000000180025095e-35 0.093784378437843804 -0.58254360664743843 1.0000000180025095e-35 2.6111111111111112 -1.8843834570786695 36011.441250000011 -0.072050230503013499 0.3451954345106808 -0.07382227715973079 -0.085251798561151074 31510.372500000001 0.055555555555555559 1.0000000180025095e-35 191.25000000000003 0.29204001360924364 -0.2407407407407407 0.61607142857142871 1.0000000180025095e-35 0.72377830750893934 0.77127500994991716 -1.0000000180025095e-35 1.0000000180025095e-35 -0.28409559126493605 -0.96287128712871273
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 6 10 -1 13 11 22 15 17 12 20 -2 14 23 21 -14 18 -9 -10 -3 -5 -6 -4 26 -25 -13
right_child=3 2 5 8 7 -7 -8 9 19 -11 -12 24 16 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 25 -26 -27 -28
leaf_value=0.0017978874744019276 -0.0074690558650306639 -0.0056264403397227464 0.0024996548091920255 -0.0023892713840423926 0.019313148466396268 -0.00067820779238987909 0.0076033092489021323 0.020504403064736342 0.0042839244031764468 0.0059127306138689146 -0.0083971690928732589 -0.001677498888920901 -0.0027189071909258927 0.013457418905888974 0.0015483777436229333 -0.0060382368939123675 0.014009415552280106 0.0069935352525249649 0.01109857501107309 0.034989971016958582 0.00054513304915658142 0.0039189930944659333 0.0055167661109507037 0.00098846297574882902 -0.0026044036538861934 0.010501229648771515 0.0054883898658557185
leaf_weight=575.28768982738256 1168.5979373715818 1328.3828416280448 357.12202478200197 1496.8929727971554 405.1503674685955 678.58004524931312 307.60362745076418 267.23214082419872 328.02846295014024 966.47383262962103 2570.7940728627145 299.63671538606286 1461.771262191236 305.91056888923049 839.15848933905363 832.52015720307827 50.659061010926962 312.19102036207914 371.30708269774914 14.420076899230478 442.32290586456656 402.45384261384606 77.772617489099503 146.46326733008027 576.65029442310333 872.69413319975138 599.39689072594047
leaf_count=6681 19122 19261 4165 21980 3223 8643 4103 2445 4471 9591 43238 4075 21890 3252 10205 12976 647 2986 3713 183 6154 5439 703 1796 7659 9639 7760
internal_value=0 0.00395161 0.00171491 -0.0046468 0.0090252 0.00474695 -0.0010126 0.0107534 -0.00165592 0.00914498 -0.00639573 -0.00183222 -0.00447268 0.00621061 0.0052047 -0.00257209 -0.00215076 0.0124192 0.0150545 0.00562332 -0.00407972 -0.00104751 0.0171135 0.00742687 0.000858586 0.0091436 0.00309006
internal_weight=0 9729.34 6753.92 8326.14 2975.41 3199.93 3553.99 2400.13 3074.32 1917.2 5251.82 3246.39 2681.03 2521.35 2215.44 2731.87 1512.43 950.73 638.539 342.449 1770.71 1899.35 482.923 1376.28 1475.68 1019.16 899.034
internal_count=246000 116054 86712 129946 29342 37700 49012 22661 45049 18735 84897 44909 41659 29057 25805 40395 22537 9144 6158 4654 25415 27419 3926 15600 19494 11435 11835
is_linear=0
shrinkage=0.0152673


Tree=40
num_leaves=28
num_cat=0
split_feature=21 21 19 11 19 414 21 19 135 141 155 90 390 1 8 6 6 8 14 165 149 390 19 129 161 109 165
split_gain=1275.02 544.06 360.618 230.097 209.74 152.973 121.492 102.597 93.8916 89.6688 85.9324 79.687 75.8241 70.3265 68.7943 81.5385 60.286 101.153 60.2493 59.5456 54.0063 52.79 48.4294 45.5988 45.1487 44.3362 42.4478
threshold=-0.86788298377637296 0.1746120078555157 1.0000000180025095e-35 1.0000000180025095e-35 0.0028346554504373738 -1.0000000180025095e-35 -1.7794007366397382 -0.20494525875886938 0.43772782503037672 0.092592592592592601 78807.645000000004 -1.0000000180025095e-35 -0.11944027006271453 1.0000000180025095e-35 1.0000000180025095e-35 -0.017790309106098575 -0.42439431913116116 1.0000000180025095e-35 -1.0000000180025095e-35 149046.50250000003 -0.28080173592252383 -0.5721489234245084 -0.2836795503754817 -0.70393326873164808 2261.2387500000004 -0.58333333333333315 29245.050000000003
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 10 6 -5 21 -3 16 11 12 -7 -2 -9 15 23 -8 20 -15 -11 -18 -1 -10 -14 -24 -13 -20
right_child=1 7 -4 5 -6 9 8 13 22 19 -12 25 14 18 -16 -17 17 -19 26 -21 -22 -23 24 -25 -26 -27 -28
leaf_value=0.0070142306822373011 -0.0043627678904387861 0.0020433205154637701 -0.0064994756560898155 -0.0010170762721702089 -0.00017313701877852585 0.0024546807197791619 0.00087339091022399496 -0.008041107369642116 0.023645762041133719 0.0012564591750101764 0.006308264545502114 0.0138589804156694 0.02575314311980751 -0.0090857742252547762 -0.0021619503641307179 0.015834043356949306 0.01826124106226289 0.0034992417668942874 -0.0031022200277638821 0.016147000397427769 0.0084621228485037402 0.015817024598755381 0.0080186482381821248 0.00091055025260214958 0.017287276255541002 0.0079217348568245312 0.0075718676831198961
leaf_weight=213.06005252152681 1542.802008472383 326.49763775989413 1595.726749651134 914.65977241098881 717.46531734243035 406.55000608786941 504.10028040781617 3269.60232212767 75.037196151912212 841.82977601513267 327.19785022735596 492.95323878899217 17.610234681516886 404.37309243530035 1077.0499284937978 113.33747069165111 203.2649868875742 800.3907195776701 1008.4632404148579 67.658876411616802 389.27778942883015 682.98875539004803 461.19012413546443 571.8129853233695 171.26138133555651 759.88684408739209 94.41017410159111
leaf_count=1828 22359 5040 24554 12103 8494 4817 5352 55692 631 10232 4161 5199 226 6831 15295 1445 2039 8936 16473 763 3965 5483 4703 7663 1590 8623 1503
internal_value=0 -0.00225419 5.99454e-05 0.00152871 0.00733431 0.00433584 0.00887555 -0.00621408 0.00719888 0.00624527 -0.00114812 0.00835903 -0.00188549 -0.00678046 0.000257006 0.00397689 0.0054188 0.00705684 -0.004039 0.00237758 0.0118441 0.0137362 0.0119561 0.00167679 0.0105476 0.010267 -0.00217897
internal_weight=0 13832.4 8729.08 7133.35 4218.04 3483.54 3500.57 5103.35 2604.52 2568.88 3649.81 1659.39 3322.61 4776.85 1779.81 702.761 1897.03 1392.93 1507.25 909.489 592.543 896.049 707.489 589.423 632.452 1252.84 1102.87
internal_count=246000 202979 117440 92886 43021 41737 34527 85539 27216 29634 51149 18639 46988 80499 24629 9334 20292 14940 24807 10995 6004 7311 6924 7889 6293 13822 17976
is_linear=0
shrinkage=0.0152673


Tree=41
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 20 21 20 135 1 21 164 411 7 390 1 1 392 149 135 118 411 1 390 20 90 248
split_gain=1370.64 629.614 483.886 296.007 220.17 118.162 106.954 89.5209 88.7447 81.1934 78.3869 63.5793 60.6847 59.2449 58.5826 57.4667 57.0703 56.5726 53.3639 51.532 49.8471 47.691 47.6477 46.256 45.2629 49.9303 45.0307
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3471229168525309 -1.1194625484164258 -1.1460985906832077 -1.2984245574534903 0.49986052388137286 0.50455650060753354 1.0000000180025095e-35 0.34138289464776045 177238.01250000004 1.0000000180025095e-35 -0.55072463768115931 -0.014720089120354104 1.0000000180025095e-35 1.0000000180025095e-35 -0.1376897149185837 -0.23678707398923718 0.52035236938031604 0.43057553956834538 1.0000000180025095e-35 1.0000000180025095e-35 0.63055644493287011 -2.0097992159524432 -1.0000000180025095e-35 1.1388888888888891
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 12 9 14 20 10 16 19 21 -10 13 -1 -3 -7 23 -15 -8 -5 -2 22 -4 -6 -11 -26 -19
right_child=2 5 7 4 8 15 18 -9 11 24 -12 -13 -14 17 -16 -17 -18 26 -20 -21 -22 -23 -24 -25 25 -27 -28
leaf_value=0.0075628117741732793 0.0015213959448718919 -0.0016892190952459121 -0.00475195016652192 0.0044166089707529015 -0.0015818949163139554 -0.006112121033165753 0.0023884705598590625 -0.010095189057119631 0.0056041669840814603 0.025559109465831127 -0.0084798210856772277 0.020793191294331628 0.0062707616425609833 0.010117310302390546 0.0066002215794868585 -0.00062687294319265158 0.0039532856223851555 0.020972752581631192 -0.0035673378168751203 0.012022484113939337 0.0084777846499396233 -0.0078486960970764724 0.0002323944527777716 0.0053835180812259907 0.0049776485835683025 0.014108282472685987 0.011571754527344952
leaf_weight=266.6596127897501 486.17538929730654 372.42744629830122 1256.4317444674671 869.32196751236916 1477.1248864680529 1315.9440858922899 537.71603132039309 1597.2183043695986 700.5430559143424 59.948915660381317 1609.1543872654438 71.246681652963161 306.80269967764616 285.05529656261206 422.38699263334274 678.75556541979313 1065.8309434056282 452.76819058507681 1000.948601808399 276.23621875047684 481.82088443636894 624.5512353554368 688.57801701873541 261.09818341955543 196.87903437018394 513.93988388031721 169.31235110759735
leaf_count=2169 5533 4904 19459 8922 18977 21374 7502 28300 8219 419 29179 746 2651 2407 5320 10432 12592 3467 14354 2594 5024 10399 10196 3146 1901 4449 1365
internal_value=0 0.0038622 -0.00458159 0.00631486 0.0046786 -0.00226528 0.00101679 -0.00701273 0.00243707 0.00885582 -0.00583191 0.00702321 0.0123768 0.0139636 0.00270506 -0.00425044 0.0011711 0.015833 -0.00147997 0.00626044 0.00499444 -0.0041696 -0.00298283 -0.000529853 0.0126987 0.0115943 0.0184333
internal_weight=0 9762.28 8282.59 6972.77 5492.17 2789.51 2506.66 5775.93 3575.84 1916.33 4178.72 771.79 1480.6 1173.8 794.814 1994.7 2804.05 907.136 1538.66 1145.56 967.996 2569.56 1945.01 1738.22 770.768 710.819 622.081
internal_count=246000 116054 129946 74024 61965 42030 32413 97533 43680 18285 69233 8965 12059 9408 10224 31806 34715 7239 21856 11516 10557 40054 29655 22123 6769 6350 4832
is_linear=0
shrinkage=0.0152673


Tree=42
num_leaves=28
num_cat=0
split_feature=20 20 19 11 11 19 155 11 19 143 19 20 7 8 6 19 7 131 155 155 164 20 7 118 20 118 389
split_gain=1330.46 435.34 224.207 204.612 155.622 140.341 141.523 114.156 111.691 101.874 90.1167 81.5527 80.8875 138.262 72.6018 70.1238 66.0721 64.9657 60.0302 56.4 51.7303 51.0438 50.2918 48.936 47.5867 47.0785 43.0176
threshold=-0.049110989848547566 -1.126355914706455 -0.23041488655489625 1.0000000180025095e-35 0.010176017601760177 0.066137329671330417 36011.441250000011 1.0000000180025095e-35 1.0000000180025095e-35 2.6111111111111112 -0.24962301927574029 -1.805970119445869 -0.55072463768115931 1.0000000180025095e-35 -0.017790309106098575 -0.15564040707434401 -0.078497232070659936 0.10252263906856406 1567.9800000000002 151938.09000000003 14826.015000000001 0.5674867089269362 -0.46140449088760332 -0.049999999999999996 0.45114359061287296 -0.12050359712230214 -0.35684334840942428
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 -2 9 10 6 7 24 12 15 -1 26 -5 14 -14 -3 -16 -8 25 22 -13 -9 -12 -24 -4 -17 -6
right_child=2 3 5 8 11 -7 17 21 -10 -11 19 20 13 -15 16 18 -18 -19 -20 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.019732775445682325 0.0046848564138041509 0.0048485091105046375 -0.0054228752758920659 0.00079459861116258916 0.024748557253371394 -0.0091946157832970173 -0.0021399570177662404 -0.0011660181149190029 -0.0029027848310881187 0.0074575989114693021 -0.0011181463733853187 0.0082791837354336366 0.0088042529803785755 0.0028389111004546645 -0.0059412584819458318 -0.0060743569968735927 0.021758594018786031 0.0074417050372550236 0.0033921640720933279 0.01647457261812104 0.017537743949371087 -0.0076330179635138457 0.00087213778855605459 0.0077970858971807642 -0.009342191472674722 -0.0017529566770210043 0.014115930103024726
leaf_weight=90.650142982602119 571.57044704258442 322.53297759220004 2153.0463721528649 648.27830252051353 129.18309347331524 1632.2422405779362 335.98217919096351 1789.1401651613414 425.27011824771762 297.90916692093015 416.26105961948633 1051.4401629194617 844.91773049533367 972.73359417915344 21.793658338487148 985.24906262010336 189.99756569415331 321.71580471843481 334.64687466993928 80.695022895932198 165.19194167852402 339.46318136155605 387.75514588132501 628.70438405871391 1105.912060584873 1477.3512524962425 318.26075730472803
leaf_count=829 7520 3975 34695 7493 994 27512 5003 26202 5873 3960 4716 9909 9299 11562 261 14909 1957 4417 4316 762 1416 5457 4612 6577 19140 20206 2428
internal_value=0 0.00379276 -0.0045303 0.00151157 0.00834106 -0.00521764 -0.00414206 -0.0049588 0.00435031 -0.00106321 0.00493688 0.011616 0.00550579 0.00700597 0.010832 -0.00188022 0.0188621 0.00253387 -0.00265964 0.0040421 0.0095465 -0.00220228 0.00333327 0.00516508 -0.00675618 -0.00348596 0.0172159
internal_weight=0 9788.82 8249.07 6520.68 3268.14 7677.5 6045.26 5387.56 3102.99 3417.69 1604.07 1664.08 2677.72 2029.44 1056.71 3119.78 211.791 657.698 2797.25 1513.42 1216.63 2128.6 1432.72 1016.46 3258.96 2462.6 447.444
internal_count=246000 116054 129946 83811 32243 122426 94914 85494 36445 47366 17496 14747 30572 23079 11517 43406 2218 9420 39431 16667 11325 31659 15905 11189 53835 35115 3422
is_linear=0
shrinkage=0.0152673


Tree=43
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 20 21 21 391 391 391 391 391 411 391 90 8 411 10 20 7 390 391 391 128 387 167
split_gain=1291.37 598.994 473.724 281.135 198.167 111.766 103.912 88.1658 73.6255 101.641 68.6964 89.9943 61.011 60.3251 60.2347 61.0512 62.6249 58.6944 70.7412 58.3071 56.3761 55.4683 55.0982 55.0362 56.6004 53.845 46.9349
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.2291473454499886 -1.1812398945549447 -1.1460985906832077 -1.7460870472760039 0.19068494058228019 0.12742144408804593 1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 0.049180694651566131 1.0000000180025095e-35 -0.80185022711144738 -1.0000000180025095e-35 0.51063775510204101 1.0000000180025095e-35 -0.5103007828594972 0.49986052388137286 -0.55072463768115931 -0.014720089120354104 -0.035868283237475519 0.12650512597654215 0.088389655172413803 -0.028394675390716356 1.7500000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 13 14 21 -2 19 9 10 -6 -12 -11 20 -5 -16 -17 18 -8 -4 -1 -3 -13 24 -20 -22 -7
right_child=2 5 7 4 8 26 17 -9 -10 12 11 22 -14 -15 15 16 -18 -19 23 -21 25 -23 -24 -25 -26 -27 -28
leaf_value=0.007157233428192058 0.007997708503971494 -0.0017319176448481026 -0.0038956472991663093 -0.00012119540413847175 -0.0034860822280406325 -0.0043906310043881104 -0.0048159037938190763 -0.0089615588262467061 -0.00069687217469296503 0.019095751681663845 0.012588244588782618 0.0041857792405926653 0.0063966051491726253 0.0057948436054217067 0.0044061377559225477 0.013187238594639723 0.0037915548435937664 -0.0043186866165531657 0.0093408520910474718 -0.0087036237991997799 0.017836691824399582 0.0063070109353670122 -0.0027179964389997752 -0.0012462354496451397 0.00061268754452302899 0.010919193134709359 0.025516348424355871
leaf_weight=321.41715570539236 418.81321959197521 373.35358962416649 2285.1092119812965 161.50811407715082 364.29871208593249 1975.4472611546516 337.09589804336429 2631.6416729949415 1238.3686347790062 140.92127691954374 234.61173239350319 1009.9404242895544 245.14104826003313 363.73637956380844 391.52400505542755 908.71405009180307 205.93652526289225 609.55305180326104 417.71634882315993 799.1856198348105 557.69734116643667 427.3310489282012 365.64968536794186 417.70297450199723 299.79750499501824 518.22605170309544 12.024348039180039
leaf_count=2659 4151 4904 35202 1533 4524 31626 4746 48587 15863 1525 2672 11989 2803 3209 3884 8167 1967 8722 5297 13744 4314 5320 4569 5609 3888 4346 180
internal_value=0 0.00372439 -0.0044791 0.00610023 0.00433135 -0.00226075 0.00106001 -0.00690397 0.00231169 0.00389381 0.00248639 0.00384358 0.0110633 0.0113839 0.00868358 0.0096337 0.0114606 -0.000331893 0.00131282 -0.00514492 0.0128311 0.00254758 0.00234388 0.00314131 0.00570793 0.014516 -0.00420253
internal_weight=0 9815.85 8216.62 7027.69 5266.61 2788.16 2500.68 5715.94 3598.93 2360.56 1974.5 1610.2 386.062 1761.08 1667.68 1506.17 1114.65 2081.87 1472.31 3084.29 1397.34 800.685 1375.59 1135.22 717.514 1075.92 1987.47
internal_count=246000 116054 129946 74024 59496 42030 32413 97533 43945 28082 23754 19230 4328 14528 15551 14018 10134 28262 19540 48946 11319 10224 16558 14794 9185 8660 31806
is_linear=0
shrinkage=0.0152673


Tree=44
num_leaves=28
num_cat=0
split_feature=19 10 411 118 1 90 8 6 118 19 158 130 19 130 70 149 70 19 19 19 130 387 2 164 149 390 16
split_gain=697.526 545.084 383.268 237.567 204.388 132.255 147.825 118.422 101.42 91.411 90.9795 82.9727 82.5694 77.1356 76.8168 74.2548 66.2009 61.5066 54.8985 52.5055 51.7005 48.4999 46.6691 44.2146 44.1541 54.6109 42.9043
threshold=1.0000000180025095e-35 -0.2233896442796319 1.0000000180025095e-35 -0.041366906474820143 1.0000000180025095e-35 -1.0000000180025095e-35 0.51063775510204101 -0.59555973266499573 0.48669064748201446 -0.31528071226839544 178.65000000000003 2.0416666666666674 0.19388630579008007 0.95833333333333337 -0.30540540540540534 -0.45394006659267488 -0.46911196911196906 -0.23041488655489625 -0.19259792775987011 -0.33317285005261182 2.7083333333333335 -0.0098228363625392414 1.0000000180025095e-35 36029.92500000001 -0.26860095034936238 0.2316748759960926 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 3 16 10 -5 7 -7 21 -4 11 18 13 23 17 -16 -3 -9 -1 -18 -10 -6 24 -2 25 -21 -17
right_child=12 2 9 5 8 6 -8 14 20 -11 -12 -13 -14 -15 15 26 19 -19 -20 22 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.014864161577738294 -0.0067066350792207982 -0.0022468038171361638 0.0097351921895358681 0.0024830179377720672 0.0037160458800217892 0.0023474399822837385 0.0020469983141623641 0.016262075728764955 0.0071398713323358219 -0.0029775802660612877 0.006018876973628612 0.0015685193641188013 -0.0089917463645285099 0.0013450110639356002 0.017530043642923359 0.0093967714259913238 0.015590625256538503 0.0044141522630145357 -0.0062850492361443957 0.0030265495335276213 0.026041457707703317 -0.0026950603686860812 -0.0010366921632465008 0.0012596461990986697 0.0020421537871289541 0.016018338276350571 0.015442914368625877
leaf_weight=28.454007726162672 1395.7609305940568 844.16388543322682 140.75154254212976 1151.0186236351728 458.26757864654064 439.54236160963774 710.94976944103837 124.88589843735099 315.61556923389435 1983.8798878155649 175.82107600942254 370.40370443090796 1429.4779751040041 453.48740434646606 500.08475337177515 1256.247512485832 74.685499090701342 584.49421856179833 2925.6723677180707 158.72137805074453 38.216144807636738 686.90967216715217 545.13811711221933 181.57493988797069 544.56443183869123 147.40949027240276 359.40669452771544
leaf_count=357 21432 12298 1556 13591 6222 4978 8897 1339 4002 27585 2222 5193 23005 6704 5092 13730 841 7298 44067 2102 446 10283 7417 2542 7432 1864 3505
internal_value=0 0.00145018 0.0035857 0.00521896 -0.00263415 0.00705224 0.00837263 0.00974715 0.00207866 -0.00213024 -0.00465501 -0.00522259 -0.00617516 -0.00418739 0.0108949 0.0123578 0.00115433 0.00651688 -0.00607725 0.00311305 0.0092208 -0.000121318 0.00243672 -0.00578375 0.00467303 0.00931869 0.0107492
internal_weight=0 14565.3 9565.94 7441.31 4999.36 5126.63 3975.61 3264.66 1499.01 2124.63 3500.35 3324.53 3460.3 2030.82 2825.12 2115.74 2314.68 709.38 2954.13 1470.52 353.832 1145.18 1395.83 1577.34 850.695 306.131 1615.65
internal_count=246000 192317 119525 90384 72792 58430 44839 35942 20953 29141 51839 49617 53683 30678 30964 22327 31954 8637 44424 19656 4448 16505 18815 23974 11398 3966 17235
is_linear=0
shrinkage=0.0152673


Tree=45
num_leaves=28
num_cat=0
split_feature=21 21 19 11 19 414 135 19 21 17 155 19 1 141 2 14 19 27 388 391 391 391 149 1 130 155 391
split_gain=1141.45 498.249 329.149 204.167 183.939 138.627 118.756 96.4721 88.215 86.3537 78.9477 68.115 68.0424 67.4531 62.2036 58.9581 56.3611 54.1856 49.3017 59.7065 48.8928 85.987 43.6967 42.6882 41.8283 40.5589 40.2697
threshold=-0.86788298377637296 0.1746120078555157 1.0000000180025095e-35 1.0000000180025095e-35 0.039544982278674708 -1.0000000180025095e-35 0.457168894289186 -0.20494525875886938 -1.3471229168525309 1.0000000180025095e-35 78807.645000000004 -0.29070757998552249 1.0000000180025095e-35 0.055555555555555559 1.0000000180025095e-35 -1.0000000180025095e-35 -0.33317285005261182 0.070400000000000018 0.45678925033826762 0.12742144408804593 -0.81178185562575544 -0.64052006669616957 0.039546288206169559 1.0000000180025095e-35 2.0416666666666674 6600.3975000000009 0.12650512597654215
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 10 6 -5 8 -3 16 13 11 -2 -9 14 23 -14 -1 26 19 22 -13 -22 -18 -7 -23 -17 -8
right_child=1 7 -4 5 -6 9 17 12 -10 -11 -12 20 15 -15 -16 25 18 -19 -20 -21 21 24 -24 -25 -26 -27 -28
leaf_value=0.019008106012104894 0.0089235840540428189 0.0019914822069988397 -0.0062964101548575631 -0.0010532707762816063 -0.00082039738991536405 0.0062037895190923745 0.016682139667408804 -0.0078194920997707827 0.0033703842643522139 0.011729493111553852 0.0059916014530719845 -0.0076692531207568776 -0.0089030016097273422 0.00099910518814044021 0.0017851264248107206 -0.0029750132189241894 0.017231069698028043 0.0036687193106999102 0.004092347931242123 0.0058005807219021705 0.010595180151998595 -0.0027908982591272058 0.0080995417578765706 0.013054165283113929 0.0037590366799817301 0.0069649038216318482 0.0092775266658938239
leaf_weight=120.62335819751024 131.53183636441827 327.25333052501082 1566.6970487013459 915.8031033501029 619.07973024249077 553.13220491632819 551.07897324487567 3193.1716662421823 1174.7547013834119 476.56907754391432 331.20661319419742 348.53584870696068 395.55886244028807 798.61938101053238 426.04385074600577 984.82878260686994 312.07316172122955 131.93084552884102 486.32035497575998 421.39527329802513 128.21435648202896 2449.6757518909872 209.82725062966347 353.66885685920715 249.18940039724112 105.33325503021479 259.9165560901165
leaf_count=927 1504 5040 24554 12103 7424 6418 4861 55692 13189 4670 4161 5084 6831 9836 4966 16298 2640 1299 4446 3945 1724 35156 1840 3744 3520 1678 2450
internal_value=0 -0.00216024 4.08765e-05 0.00142855 0.00686361 0.00404825 0.00816301 -0.00599985 0.00653932 0.00584308 -0.00110626 -0.0018202 -0.0065608 0.00452168 0.00662501 -0.00384872 0.00893405 0.0128433 0.0080751 0.0101174 -0.00226861 -0.00159906 0.0135818 0.00888795 -0.00218251 -0.0020051 0.0143232
internal_weight=0 13735 8728.89 7162.19 4287 3523.84 3667.92 5006.15 2724.99 2608.03 3638.35 3307.15 4678.89 2131.46 1332.84 1485.72 1550.24 942.926 1429.62 943.296 3175.62 2827.08 521.9 906.801 2698.87 1090.16 810.996
internal_count=246000 202979 117440 92886 43021 41737 35597 85539 26987 29634 51149 46988 80499 24964 15128 24807 13798 8610 12871 8425 45484 40400 4480 10162 38676 17976 7311
is_linear=0
shrinkage=0.0152673


Tree=46
num_leaves=28
num_cat=0
split_feature=20 20 20 387 118 10 1 155 143 149 414 10 2 10 6 414 120 154 6 171 387 391 391 90 122 90 141
split_gain=1232.86 331.862 235.988 219.153 150.61 106.899 101.341 91.5046 83.0132 70.5754 68.0489 65.55 63.2472 62.0122 58.826 56.0405 55.0599 49.7405 51.4711 46.1971 46.1884 45.6434 57.4448 68.2847 45.072 55.1913 44.6685
threshold=-0.23944851334767706 -1.6199246107459455 0.33014794124083729 -0.037632662431008129 -0.0075539568345323735 0.11090509545392117 1.0000000180025095e-35 33998.602500000008 2.9444444444444451 -0.21135171585026369 -1.0000000180025095e-35 -0.18067573135558299 1.0000000180025095e-35 -0.32941903584672433 -0.36695906432748532 -1.0000000180025095e-35 0.56078610603290679 4.3571428571428585 -0.48520467836257303 11.250000000000002 -0.0098228363625392414 -0.84913404291403738 0.12742144408804593 -1.0000000180025095e-35 0.32758620689655177 -1.0000000180025095e-35 0.16666666666666669
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 13 4 6 20 8 9 10 14 17 -6 -12 26 -1 -5 -7 -4 18 -3 -9 -2 -13 23 -23 25 -15 -8
right_child=2 3 16 5 7 15 12 19 -10 -11 11 21 -14 24 -16 -17 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0054295470403258926 -0.0019030022133420502 0.0018412843108880309 -0.0074154712568252614 -0.0063835952482548339 -0.0042153931452032518 -0.0010688420405907399 0.014906749877146882 0.010236747454174952 0.0075757810614650841 0.0010324791136586816 -0.0024488445581278564 -0.0055792214695905397 0.0058073222530644645 0.0071902942540272869 -0.00079320526787468972 0.0052225180606892442 -0.002836525616736986 -0.0030543526659355786 0.01160370143277677 -0.0012857690050524335 -0.0063721356414518206 -0.00057618032105093608 -0.00082906047054078153 0.0092300578701315257 0.0075926957515507123 0.017125728043512506 0.0059731562159037431
leaf_weight=337.97405430674553 866.85550635680556 179.30651817470789 3233.9232831895351 674.47816574573517 862.17743023112416 458.67497597634792 481.73763262107968 297.80680146813393 200.06469376385212 1067.6382296904922 845.02478551864624 129.07573595270514 688.05126662924886 171.8441135212779 1268.0261755697429 1155.8612089604139 764.14398865401745 93.655562125146389 442.73175045102835 109.52604944258928 1456.7273584865034 233.19632181152701 388.77090137079358 555.86462243646383 271.72781347483397 596.49462328106165 184.83423527702689
leaf_count=3367 13202 1947 55230 9370 12657 5675 4760 3546 2523 12268 12669 1768 7381 1427 17230 13235 11841 1102 4728 1473 24055 3095 5411 7084 2203 4763 1990
internal_value=0 0.00432046 -0.0036938 0.00295147 -0.00170939 0.000461259 0.00592989 0.000325266 -0.00177139 0.00352962 -0.000589944 0.000858603 0.00908206 0.0111622 -0.00273948 0.00342962 -0.00654278 0.0072406 0.00880584 0.00711692 -0.00470909 0.0030042 0.0039534 0.00632094 0.0130148 0.014918 0.0124458
internal_weight=0 8273.1 9743.09 6895.06 5745.03 3757.11 3137.96 3421.44 2142.57 1783.33 3014.11 2151.93 1354.62 1378.04 1942.5 1614.54 3998.07 715.694 622.038 407.333 2323.58 1306.91 1177.83 789.061 1040.07 768.339 666.572
internal_count=246000 93969 152031 82209 84960 48033 34176 47703 29123 20045 42684 30027 14131 11760 26600 18910 67071 7777 6675 5019 37257 17358 15590 10179 8393 6190 6750
is_linear=0
shrinkage=0.0152673


Tree=47
num_leaves=28
num_cat=0
split_feature=20 20 19 120 10 155 19 135 20 118 391 19 19 135 7 391 391 163 7 391 111 133 90 10 141 414 11
split_gain=1198.76 386.268 208.188 188.582 135.546 133.167 126.528 112.347 105.76 96.2374 91.4409 82.9913 82.9682 78.4893 75.3974 91.2944 92.4133 73.2701 67.4886 76.3815 66.7471 59.5585 56.084 54.5389 53.4535 48.8141 45.4916
threshold=-0.049110989848547566 -1.126355914706455 -0.23041488655489625 -0.014168190127970747 -0.58254360664743843 36011.441250000011 1.0000000180025095e-35 0.49605103280680446 0.51688161336547822 -0.07589928057553956 -0.80185022711144738 -0.31528071226839544 0.12336000311721791 0.86482381530984209 -0.59028425701312426 0.1379033485638034 -0.80185022711144738 -1.0000000180025095e-35 -0.692293338309386 0.12742144408804593 1890.5850000000003 0.17015384615384618 -1.0000000180025095e-35 -0.14716385111935171 -0.12962962962962959 -1.0000000180025095e-35 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 -2 11 -1 8 10 12 9 -4 -6 -3 14 18 -5 16 -16 -9 -12 -20 25 -7 -18 -13 -24 -11 -27
right_child=2 3 5 7 6 21 -8 17 -10 20 13 23 -14 -15 15 -17 22 -19 19 -21 -22 -23 24 -25 -26 26 -28
leaf_value=0.0014092338869203368 0.0044816519897707442 0.01269677836683589 -0.0071628739507305795 -0.0019063154831035791 0.0011044021607705577 -0.0025150265475164897 -0.00041526076033174204 -9.1113456849218293e-05 -0.0091023708337238541 -0.0066347561007075858 0.0033389925492527464 -0.0052141382560528422 -0.0062673046811229961 0.019077480114634632 -0.0026428615925688549 -2.5169000766795592e-05 0.001406823317136408 0.010271830794897642 0.013863623465588001 0.0068832058004521792 0.0051630030645412996 0.0058314978681184492 0.013361078079669617 -0.00049069294534210249 0.0062387969347255726 -0.0041859169928620083 0.00055705815816161556
leaf_weight=630.93744114786386 576.35623175278306 86.267377823591232 2087.0588614083827 631.84511724114418 225.34236579760909 516.09519235789776 278.98811767250299 200.60849364474416 1654.4198802374303 827.8792658559978 283.55343160405755 1001.3295876830816 257.78393857553601 272.17570952326059 226.14201421290636 823.2561388798058 249.36848337575793 736.13197902590036 1070.8821317367256 565.60422041267157 221.57324818894267 323.85828705132008 463.76845066249371 1333.0510545633733 539.1904366388917 1118.1375435478985 809.38117631524801
leaf_count=7372 7520 980 35598 7708 2113 7886 3091 2401 28928 13261 2634 15137 3757 2235 2816 10562 3026 8146 9318 5480 3032 4508 4949 18204 6125 17863 11350
internal_value=0 0.00356097 -0.00435355 0.00140693 0.00779718 -0.00502858 0.00928821 0.00339161 -0.00574524 -0.00464634 0.0104117 -0.00197388 0.00202296 0.0113641 0.00275496 0.00403855 0.00630725 0.00804322 0.010264 0.0114578 -0.00287864 0.000692836 0.00793091 -0.00252101 0.00954328 -0.00352896 -0.0021897
internal_weight=0 9876.23 8134.76 6548.74 3327.48 7558.4 2696.55 4128.1 6718.45 5064.03 2417.56 2420.65 3191.35 2192.22 2933.57 2301.73 1478.47 936.74 1920.04 1636.49 2976.97 839.953 1252.33 2334.38 1002.96 2755.4 1927.52
internal_count=246000 116054 129946 83811 32243 122426 24871 49490 110032 81104 21780 34321 38943 19667 35186 27478 16916 10547 17432 14798 45506 12394 14100 33341 11074 42474 29213
is_linear=0
shrinkage=0.0152673


Tree=48
num_leaves=28
num_cat=0
split_feature=21 21 411 10 21 29 119 391 168 130 391 109 391 10 411 143 119 135 135 137 390 147 10 127 6 148 6
split_gain=1086.74 444.252 234.826 166.387 159.818 114.915 114.233 113.667 104.526 92.1155 86.9276 72.6295 71.7261 70.2142 94.7587 56.1446 55.5962 54.7505 53.227 50.982 50.5159 48.0599 43.9063 45.0022 39.9257 36.3695 38.0783
threshold=-0.73924480687859639 0.1746120078555157 1.0000000180025095e-35 0.067367119901112493 -1.7460870472760039 0.033950000000000029 0.51281287246722307 0.12742144408804593 0.75000000000000011 2.2916666666666674 1.0000000180025095e-35 -0.41666666666666657 0.054884036564190546 -0.23176761433868973 1.0000000180025095e-35 1.3888888888888891 -0.016388557806912989 0.457168894289186 0.65036452004860279 -1.0000000180025095e-35 -0.20200074523897418 0.094594594594594614 0.81712676830105768 -0.51791850166965092 -0.14257727652464494 0.071181338389014234 -0.42439431913116116
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 3 8 17 6 15 10 9 16 11 21 -12 -3 18 25 -2 20 -15 -8 -1 22 23 -5 -13 26 -6
right_child=1 13 -4 7 5 -7 19 -9 -10 -11 12 24 -14 14 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.004230885904979732 -0.0058682108496865334 -0.0079215031825258971 -0.0051240044694777481 0.021434194922691326 -0.00070850564442366656 -0.0011950991726566241 0.012679309191843652 -0.001039739164107093 0.0098170318903439534 0.0060837536278991241 0.019387043888229878 -0.0012758067937612538 0.0062347001575479904 -0.0033838038538089579 -0.008868740783022128 0.0099588559035308465 -0.001247174818428615 0.016784027979901962 0.0045709363538906774 0.0063992063960578499 0.011884342124106781 0.0019570221798543889 0.003741153689048884 0.0094244625309967897 0.0055360979174992556 -0.00076598655925954392 0.0060098487508545876
leaf_weight=319.60427764058113 902.40185859054327 2218.4305169396102 1719.1124255135655 92.509695466607809 272.77806816622615 655.23169010132551 592.14070242270827 861.08590584620833 188.75418075546622 304.49386065080762 172.23552652075887 612.88223028555512 227.22874506562948 1768.4705149158835 753.84475159272552 259.14215721189976 1874.7802805416286 295.62247443944216 219.42036422342062 633.41604219377041 564.36011304706335 324.49610130116343 241.6925968490541 377.00746809318662 297.04899219796062 574.05497993528843 683.13142331317067
leaf_count=2808 13243 39440 26091 1015 3013 7691 5963 11068 2340 4230 1862 7531 2582 29250 13294 2818 26139 2336 3555 6750 4498 3784 2556 4346 3705 6547 7545
internal_value=0 -0.002291 -0.000107247 0.00122307 0.00616392 0.00458789 0.00584785 0.00369514 -0.00119771 -0.00187594 0.00543756 0.00409769 0.0119353 -0.00589723 -0.00425553 0.00337954 -0.00275232 0.0110578 -0.00250079 0.00944255 0.00912912 0.00686357 0.00908817 0.0118184 0.000938617 0.00225801 0.00408337
internal_weight=0 13155.9 8195.73 6476.62 4849.48 3669.9 3014.66 3206.19 3270.43 3081.68 2345.1 1945.64 399.464 4960.17 2741.74 1789.11 2777.18 1179.59 1987.89 1225.56 883.964 1035.71 711.21 469.517 909.931 1529.96 955.909
internal_count=246000 196031 110492 84401 49969 40327 32636 38449 45952 43612 27381 22937 4444 85539 46099 19923 39382 9642 32805 12713 7306 11701 7917 5361 11236 17105 10558
is_linear=0
shrinkage=0.0152673


Tree=49
num_leaves=28
num_cat=0
split_feature=21 21 19 19 11 21 414 19 141 7 8 155 1 135 390 19 143 14 8 6 390 8 6 149 19 409 165
split_gain=1050.94 433.945 283.608 198.511 177.303 123.559 119.171 91.8437 79.7354 68.6268 92.231 68.505 66.7547 66.0635 64.7523 64.6353 57.8773 57.7737 56.3782 73.8443 53.4682 59.4256 49.1856 47.6256 46.8912 45.9486 43.2596
threshold=-0.73924480687859639 0.1746120078555157 1.0000000180025095e-35 0.039544982278674708 1.0000000180025095e-35 -1.3471229168525309 -1.0000000180025095e-35 -0.20494525875886938 0.092592592592592601 -0.43328979287180441 1.0000000180025095e-35 78807.645000000004 1.0000000180025095e-35 0.69410692588092349 -0.11944027006271453 -0.34657249725234812 1.0555555555555558 -1.0000000180025095e-35 1.0000000180025095e-35 -0.14257727652464494 -0.16857635277102093 1.0000000180025095e-35 -0.028517126148705094 0.015533043138304311 -0.31528071226839544 -1.0000000180025095e-35 267050.61000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 4 5 11 15 -6 -3 9 -8 22 14 -9 24 -2 -1 20 -14 19 -16 -17 23 -11 -22 -7 -26 -15
right_child=1 7 -4 -5 6 13 8 12 -10 10 -12 -13 17 26 18 16 -18 -19 -20 -21 21 -23 -24 -25 25 -27 -28
leaf_value=0.020014010581432738 -0.0043122670928736158 0.0019466683856218486 -0.0062302073019624184 -0.0014370715932475917 -0.0012087842271888063 0.012219191375248316 0.0028102950552153345 -0.0076538341712761469 0.0016574189402862914 0.011125998172321239 0.0047639756181135839 0.0055703283058413195 -0.008749331176668089 0.0094669797921479205 3.0233270858283217e-05 0.0041956949745671056 0.01454963173304312 -0.0018672429280303046 -0.0021670386660829865 0.010901379071680302 0.01651859715496844 0.0057994807377234441 0.021490571912073823 0.0070610343853916334 -0.00031399686707321919 0.0049218877332550858 0.03279976881452458
leaf_weight=139.11894329637289 1425.6034375429153 327.92651375383139 1450.6470254547894 705.27777608856559 849.13272404298186 131.08879218250513 517.94133979082108 3138.0430865772069 865.69709806889296 445.94517737627029 505.16844442859292 312.64380369707942 388.40570890530944 305.78727634251118 453.44357902184129 586.43774843961 382.13596206903458 1080.2559680752456 1007.6298202872276 215.55243790894747 373.33053556084633 443.05856745690107 144.74860414117575 192.75558325648308 674.63883603736758 917.76959507912397 19.981752056628466
leaf_count=1026 21041 5040 23035 8760 11279 1225 5672 55692 10323 4614 5844 3909 6831 3132 6071 5399 3265 17976 14482 2771 2969 3999 1451 1592 8140 10274 188
internal_value=0 -0.00226088 -0.000105725 0.00604227 0.00121055 0.00731065 0.00371857 -0.00583759 0.00540966 0.00741635 0.00958406 -0.00123153 -0.00639376 0.00462927 -0.00192029 0.00990142 0.00918348 -0.00369448 0.000108364 0.00354885 0.00789091 0.0100279 0.0136877 0.013318 0.00342896 0.00269814 0.0109455
internal_weight=0 13128.8 8194.15 4871.38 6743.51 4166.1 3328.63 4934.63 2479.5 1613.8 1095.86 3414.87 4606.7 2049.27 3102.23 2116.84 1977.72 1468.66 1676.63 668.996 1595.58 1009.14 590.694 566.086 1723.5 1592.41 325.769
internal_count=246000 196031 110492 49969 87457 41209 39183 85539 27904 17581 11909 48274 80499 22959 44365 18250 17224 24807 23324 8842 13959 8560 6065 4561 19639 18414 3320
is_linear=0
shrinkage=0.0152673


Tree=50
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 19 20 19 19 21 155 20 19 21 141 130 119 151 391 6 390 141 414 167 112 143 155
split_gain=1146.51 500.915 430.522 231.343 172.672 106.125 103.873 98.8968 93.56 79.2359 76.6264 67.4467 65.5511 59.2741 58.3377 65.8768 52.284 52.1626 51.1003 89.8616 51.0649 48.9979 46.2283 44.3894 44.051 41.6783 40.8508
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.2291473454499886 -1.4667066540297049 0.066137329671330417 -1.1460985906832077 -0.23041488655489625 0.17997716903984248 -1.2291473454499886 35028.247500000005 0.49986052388137286 -0.31528071226839544 0.34138289464776045 -0.092592592592592574 0.70833333333333337 0.92282479141835527 0.27198421645997756 0.12742144408804593 -0.3717000835421887 -0.014720089120354104 0.092592592592592601 -1.0000000180025095e-35 1.7500000000000002 -0.64902126047634823 1.7222222222222225 116907.93000000001
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 5 16 21 9 20 -4 10 -2 12 13 -6 -9 18 -16 24 -12 19 -14 -3 -5 -21 -8 -1 -23 -11
right_child=2 6 7 4 8 -7 23 11 -10 26 17 -13 14 -15 15 -17 -18 -19 -20 22 -22 25 -24 -25 -26 -27 -28
leaf_value=0.017100288232085217 0.0057742073022411192 -0.0015785619376863303 0.0013715326751904346 0.011820539885452111 0.010278231948364731 -0.0058470411038815248 -0.0041534786621345663 -0.0045466143456726407 -0.0067106164241849545 -0.0011349847634754386 0.0031989717268221416 -0.0099593738491099565 0.001241678672337641 -0.0084857454064184764 -0.0023341940012934284 0.004306702023473186 0.014703863962327843 0.013264709567164634 -0.00031793835617266295 0.0024161457648294578 0.0061421302781204347 0.003039094087357759 0.012333063825557128 0.024641686605466662 0.0078141230687434182 0.016292832642895515 0.0089350153776133322
leaf_weight=134.35116025060415 914.1913588270545 369.77560049667954 335.24584146589041 697.86756161600351 226.67104779928923 438.67338798940182 1940.165784753859 2316.2282330691814 237.81677626445889 1054.8011370636523 220.25321684777737 1457.3061695620418 571.04869405180216 1466.4664472900331 1120.2960303276777 504.71310773491859 472.23886863142252 271.67946147918701 486.95214712992311 150.29478152096272 430.0104874484241 352.64830435067415 431.35409697890282 12.274360202252863 1211.8445597812533 66.182682313024998 102.82292819395661
leaf_count=1016 9664 4904 4882 5727 2240 6486 31626 37373 3459 14988 2480 27283 6630 27995 13815 6214 3632 2750 6066 1847 5320 3155 4528 180 9880 585 1275
internal_value=0 0.00346755 -0.00427974 0.00559668 0.00399142 0.000966952 -0.00206521 -0.00664388 0.0025758 0.00241455 0.00313285 -0.00715847 0.00233412 -0.00607652 0.00177914 -0.000265679 0.0103027 0.00877972 0.00381107 0.00556305 0.00256157 0.00933277 0.00978804 -0.00396526 0.00875009 0.00516206 -0.000231243
internal_weight=0 9908.44 8085.74 7156.21 5337.78 2510.49 2752.23 5575.25 4221.08 2071.82 3983.26 5240 3491.33 3782.69 3264.66 1625.01 1818.43 491.933 1639.65 1152.7 799.786 1116.7 581.649 1952.44 1346.2 418.831 1157.62
internal_count=246000 116054 129946 74024 59496 32413 42030 97533 50029 25927 46570 92651 41340 65368 39100 20029 14528 5230 19071 13005 10224 9467 6375 31806 10896 3740 16263
is_linear=0
shrinkage=0.0152673


Tree=51
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 20 21 20 109 135 47 155 391 6 8 6 20 149 90 130 391 6 390 20 391 10 411
split_gain=1113.01 483.285 421.151 221.993 170.399 101.097 89.6487 84.7442 91.6396 74.998 60.5342 58.6595 56.9897 93.4349 68.6224 62.0305 56.6729 55.7944 52.1002 49.7449 49.3674 56.5805 49.0601 43.9399 43.5905 42.0805 44.5649
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3471229168525309 -1.1194625484164258 -1.126355914706455 -1.7460870472760039 0.49986052388137286 -0.58333333333333315 0.50455650060753354 1.0000000180025095e-35 295882.22250000009 0.12742144408804593 -0.38559732664995816 1.0000000180025095e-35 -0.017790309106098575 -2.0097992159524432 -0.24282187115445683 -1.0000000180025095e-35 0.62500000000000011 0.12650512597654215 -0.43943191311612356 -0.014720089120354104 -1.4667066540297049 -0.80185022711144738 -0.28409559126493605 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 19 10 22 -2 8 -4 12 16 -11 13 -6 15 -15 -5 20 -18 23 21 -8 -3 -1 -20 -7 -27
right_child=2 5 7 4 9 25 17 -9 -10 11 -12 -13 -14 14 -16 -17 18 -19 24 -21 -22 -23 -24 -25 -26 26 -28
leaf_value=0.014254448509704976 0.0073033769240631397 -0.0015803472338953687 -0.00083906719408226532 0.018675224205065875 -0.0011101760519319959 -0.0067880864727451135 -0.00057759418132199384 -0.0096760342625242437 -0.0065803849871976239 0.0053576561013564672 0.0017351498966339653 0.026058515363899786 -0.0020841521206381589 0.0060188478528405967 0.00087835850014551646 0.017332454410100142 0.0030331046975963952 -0.0021989764106145671 0.000468872563628981 0.01518253392456961 -0.0016985328766418624 0.010713328335618801 0.005874069011834052 0.0072244318613842668 0.010604457808442779 -0.0004820008516126818 -0.0075193286923866051
leaf_weight=278.05120253562927 429.29764957726002 380.1516520678997 816.21969818323851 127.88785496354103 884.93971978500485 749.58344123512506 166.89742578193545 1508.7491193525493 3217.7391913533211 761.39777103811502 337.95461347699165 33.412679053843021 960.7853404097259 425.99509876966476 407.4143577106297 156.14907103776932 373.05636502802372 1349.9857090972364 111.36431365460157 410.84843737632036 300.39096150174737 265.62190039455891 444.5080056078732 870.62783452868462 1044.8728252872825 898.12449375540018 274.81980047002435
leaf_count=1725 4151 5069 12332 954 10825 12800 2171 28300 56901 8641 3217 324 12482 4844 4930 1634 3731 18557 1040 3153 4148 3386 5501 7181 9343 14122 4538
internal_value=0 0.00340638 -0.00423085 0.00548918 0.00407324 -0.00203747 0.000951362 -0.00658125 -0.00542107 0.00209962 0.00765902 0.00624575 0.000933755 0.00248555 0.00570995 0.00907415 0.00886122 -0.000354006 0.00803219 0.0105894 0.00303152 0.00633705 0.00242708 0.00893629 0.00963641 -0.00395733 -0.00213965
internal_weight=0 9931.94 8054.9 7184.76 5625.23 2747.19 2512.19 5542.71 4033.96 3630.09 1995.14 794.81 2835.28 1874.5 989.559 582.144 1657.18 2082.9 1529.29 1559.53 732.91 432.519 824.66 1148.68 1156.24 1922.53 1172.94
internal_count=246000 116054 129946 74024 61965 42030 32413 97533 69233 43680 18285 8965 34715 22233 11408 6478 15068 28262 14114 12059 9705 5557 10570 8906 10383 31460 18660
is_linear=0
shrinkage=0.0152673


Tree=52
num_leaves=28
num_cat=0
split_feature=20 20 120 11 409 135 20 155 11 20 118 391 6 7 163 0 8 8 17 120 6 157 391 144 155 86 164
split_gain=1080.48 342.402 167.1 163.928 121.048 100.07 80.0235 76.202 73.4188 71.4366 71.2076 70.3445 121.987 67.5263 66.9521 64.6845 61.9569 58.7557 55.0978 54.4656 51.9919 51.3944 50.2348 49.1627 48.5494 45.0302 42.2017
threshold=-0.049110989848547566 -1.126355914706455 -0.014168190127970747 0.093784378437843804 -1.0000000180025095e-35 0.49605103280680446 0.3451954345106808 36011.441250000011 -1.1025852585258524 -1.8843834570786695 -0.085251798561151074 0.1379033485638034 -0.37970342522974093 -0.55072463768115931 -1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 -1.0000000180025095e-35 0.45658135283363804 -0.14897243107769423 191.25000000000003 -0.80185022711144738 0.61607142857142871 165056.09625000003 1.0000000180025095e-35 171427.09500000003
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 24 6 22 11 10 18 -6 -10 -2 12 -4 -11 -7 17 20 -14 -5 -20 -15 -12 -1 -9 -3 26 -24
right_child=3 2 5 7 8 14 -8 23 9 13 21 -13 15 16 -16 -17 -18 -19 19 -21 -22 -23 25 -25 -26 -27 -28
leaf_value=-0.0045340600206704171 -0.0069273727874926026 -0.0023540865247320781 -0.00038796985363465325 -0.0069870740312607139 0.0019743383021324054 -0.0002507567769667238 -0.007870953904779019 0.0040924481953378191 0.017164383665604511 0.0032095413280191663 -0.002345750098550735 -0.0014187607452692537 0.010641039171655065 0.010811939984539687 0.0096022487699854806 -0.0076762780456917168 0.006970144526698017 0.0033587042066091275 -0.0027919896233787114 0.0024526573922326413 0.020206669898462745 0.01303554237192746 0.0032752651378417041 0.032094068664228814 0.0082530003228648251 0.0136995125000483 0.018290999168693353
leaf_weight=147.61283919215202 1107.3793382197618 2300.9785953238606 1030.808232203126 470.30315574258566 251.3643492385745 202.11043870076537 2425.8908086009324 330.25858553126454 339.42208670079708 328.34952291473746 1424.3841753788292 1027.1857939958572 651.10450214147568 363.68937632068992 752.40827222168446 66.705172900110483 465.95586921647191 435.72222876176238 1542.251883957535 656.78717377781868 229.41316181793809 52.154784448444843 1090.2080916985869 15.236155483871697 104.64842765033245 121.63341842591763 45.603038195520639
leaf_count=1637 19122 33010 12494 7406 2659 2401 43238 4471 2509 3101 21890 13442 6941 3187 8146 876 4480 5190 24105 8884 1909 647 11304 183 1311 1058 399
internal_value=0 0.00334646 0.00131307 -0.0041823 0.00729313 0.0031638 -0.00587557 -0.00136531 0.00972992 0.0108532 -0.00399821 0.00186976 0.00342038 0.00930033 0.00750676 0.00683097 0.0111791 0.00773104 -0.00224105 -0.00122132 0.0144669 -0.00179455 0.00385494 0.00537166 -0.00188821 0.00484758 0.00388933
internal_weight=0 9954.92 6571.67 8024.65 3383.25 4166.04 5009.81 3014.84 1978.19 1726.83 2583.92 3211.53 2184.34 1387.41 954.519 1153.53 1059.06 1086.83 2669.34 2199.04 593.103 1476.54 1405.06 345.495 2405.63 1257.44 1135.81
internal_count=246000 116054 83811 129946 32243 49490 84897 45049 17845 15186 41659 38943 25501 12677 10547 13007 9576 12131 40395 32989 5096 22537 14398 4654 34321 12761 11703
is_linear=0
shrinkage=0.0152673


Tree=53
num_leaves=28
num_cat=0
split_feature=21 21 19 409 19 11 391 391 19 391 391 19 391 166 90 135 129 391 135 166 141 7 19 411 10 19 157
split_gain=953.189 470.247 291.45 175.228 122.044 111.485 107.154 137.411 99.5952 91.0172 116.501 77.275 69.798 63.9106 63.1067 61.0925 57.0859 56.6594 55.7781 52.5818 50.7011 46.9305 52.5742 43.1745 46.4686 52.4098 42.9613
threshold=1.0000000180025095e-35 -1.2291473454499886 1.0000000180025095e-35 -1.0000000180025095e-35 0.042042249439647579 1.0000000180025095e-35 0.12742144408804593 1.0000000180025095e-35 0.0028346554504373738 -0.80185022711144738 -0.035868283237475519 -0.31528071226839544 0.049180694651566131 34868.891250000008 -1.0000000180025095e-35 0.83748481166464173 -0.56525182483528991 -0.92257102786474277 0.40795868772782512 6968.1712500000003 0.24074074074074076 -0.67014990358897797 -0.36229080842168021 1.0000000180025095e-35 -0.17243510506798515 -0.080471531557829226 1406.2500000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 3 11 5 19 7 9 14 17 20 -3 -9 -8 -1 16 -13 -5 23 -2 -11 -7 -23 24 25 -16 -17
right_child=4 2 -4 6 -6 21 13 12 -10 10 -12 15 -14 -15 18 26 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0046921088565700392 -0.0065691711427382244 0.0097406069751486881 -0.0052031298369320106 0.0022849725056534377 -0.0096694099327135526 -0.0072216237206871262 -0.00097826088788002265 0.018927875674770858 0.0011816753167040346 0.0090821068754727216 -0.0015747589249320141 0.0049736810681884486 0.0078037534793360406 0.0083604333631166639 0.028645508770212914 0.0025471076469645668 -0.0026945091656135458 -0.008916526843914108 0.014494984459822903 0.00039908407392179898 0.0031424140319562112 0.020061185308908512 -0.00030768501303120386 0.0031410359747587567 0.011835828142450426 0.002120282862622625 0.018548615954211475
leaf_weight=625.9625054448843 2589.5447054058313 157.40209826081991 1613.3246414139867 252.25739231705666 1137.4948037602007 236.22910775616765 1165.1930673420429 228.76613415032625 464.03861865401268 1108.7015630863607 441.05219589173794 247.38028018921614 320.36782930791378 199.8400756791234 18.72262129932642 364.25584807619452 2550.7060238867998 179.3316168487072 538.90594409406185 276.91880318522453 488.17167672514915 29.967646632343531 1400.272748619318 271.50202380865812 795.23863925039768 228.43138267844915 44.014216560870409
leaf_count=5596 46430 1578 24997 2940 21057 3702 15089 2350 4974 12063 5486 3173 3542 2265 163 4548 34477 2314 4333 4716 5801 403 22198 2570 6595 2161 479
internal_value=0 0.00237306 0.000698393 0.00192861 -0.00519254 -0.00406672 0.00394016 0.00554543 0.0076965 0.00400331 0.00535343 -0.000690214 0.0124599 0.000383233 0.00891222 -0.0012057 -0.00201298 -0.00235018 0.0103324 -0.00589282 0.00727267 -0.000919863 0.000115443 0.00861612 0.0100325 0.00418821 0.00430284
internal_weight=0 12303.6 9360.76 7747.44 5670.43 4532.93 4383.68 3018.65 2942.8 2469.51 2037.93 3363.76 549.134 1365.03 2478.76 3206.36 2798.09 431.589 1852.8 2866.46 1596.87 1666.47 1430.24 1313.89 1042.39 247.154 408.27
internal_count=246000 147494 121102 96105 98506 77449 51850 34496 26392 28604 23350 44255 5892 17354 21418 42677 37650 5254 15822 51146 17864 26303 22601 11489 8919 2324 5027
is_linear=0
shrinkage=0.0152673


Tree=54
num_leaves=28
num_cat=0
split_feature=20 21 21 1 20 109 21 21 90 1 109 119 8 29 390 20 135 20 119 11 149 1 155 2 10 20 21
split_gain=1040.34 546.746 309.362 153.666 144.041 126.527 120.343 119.332 91.2069 68.4699 65.1796 60.2586 57.7513 56.1116 53.2372 51.9822 50.3152 46.18 45.4022 44.668 43.1578 42.4691 41.2774 41.2311 39.0587 37.4106 36.6055
threshold=-0.39425883824369934 -0.4706364644200467 0.1746120078555157 1.0000000180025095e-35 0.29935720544807254 -0.58333333333333315 -0.85298474263107094 -1.4231812591257043 -1.0000000180025095e-35 1.0000000180025095e-35 -0.58333333333333315 0.72377830750893934 0.51063775510204101 1.0000000180025095e-35 0.17781396277573439 -1.1460985906832077 0.457168894289186 -1.6573320931524578 0.73808104886769976 0.45352035203520358 -0.21135171585026369 1.0000000180025095e-35 23622.570000000003 1.0000000180025095e-35 -0.035228677379480836 -1.805970119445869 0.19068494058228019
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 7 3 6 5 -3 22 12 -5 -4 17 -12 14 16 18 -10 19 -8 -2 -9 -19 -7 24 -23 -1 -11 -6
right_child=1 4 9 8 26 21 10 13 15 25 11 -13 -14 -15 -16 -17 -18 20 -20 -21 -22 23 -24 -25 -26 -27 -28
leaf_value=0.0026010150055085003 0.0021140001189229093 0.0013609116998169908 -0.003760016321453724 0.0043096887811841268 -0.0063767459475473241 -0.0062570294125547836 0.013938657667339696 -0.001849153718813321 0.014065903420117595 0.015270814228200046 -0.0015999463828578007 0.0055407581427766393 -0.00044655576267147346 -0.0047080175520216568 0.012923773142397824 0.0084768656130245913 0.0057718595741242879 0.009368253707533334 0.01118396813924253 0.0045749220813438053 0.00068039321581556177 0.00099674853291620833 0.014016036603981282 -0.0049673330303776561 0.008771114051154787 0.0015522624701991743 -0.0097791938439542557
leaf_weight=376.32963790744543 400.81023509800434 928.15884084999561 1055.0667389631271 630.67009172961116 1590.0670194216073 2179.7211367785931 131.27678279578686 1016.1247157938778 770.14406007528305 51.015104025602341 1137.3477615267038 363.20092930272222 252.66127987205982 477.68102779239416 309.82187683135271 811.58068804815412 424.22315035015345 211.05965929478407 191.79351948201656 335.19960739463568 368.10989976301789 446.80916576832533 212.46950256824493 674.60966571420431 681.34900170564651 518.72252036258578 1421.9989804141223
leaf_count=3320 4126 12888 16202 6193 27567 37371 1100 14225 5862 538 13345 4033 2659 6756 2850 8006 5367 2284 1830 4281 4256 7161 1603 11120 5408 7240 28409
internal_value=0 -0.00305907 0.00441781 0.00609494 -0.00543263 -0.00361123 0.0040903 0.00198116 0.0092444 -0.00145347 0.00193296 0.000122833 0.00597071 -6.03146e-05 0.00777726 0.0112054 0.0011853 0.00574218 0.00506769 -0.000248426 0.00386436 -0.00501199 0.00783754 -0.00258313 0.00658531 0.00280164 -0.00798663
internal_weight=0 10649.7 7318.34 5693.54 7241.36 4229.3 3481.14 3408.32 2212.39 1624.8 2211 1500.55 1155.09 2253.23 902.426 1581.72 1775.55 710.446 592.604 1351.32 579.17 3301.14 1270.15 1121.42 1057.68 569.738 3012.07
internal_count=246000 166610 79390 55410 124516 68540 35349 42094 20061 23980 25018 17378 11465 30629 8806 13868 23873 7640 5956 18506 6540 55652 10331 18281 8728 7778 55976
is_linear=0
shrinkage=0.0152673


Tree=55
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 1 19 19 19 21 20 109 149 135 2 391 7 149 1 7 20 19 20 109 19 128 130
split_gain=1013.66 429.278 393.882 196.347 152.63 99.6227 99.5998 96.2021 81.4417 69.3752 65.409 70.4049 65.2289 60.2484 59.086 57.3988 57.1057 52.1035 47.7818 45.9633 43.4515 41.5873 41.2738 40.1216 39.7218 38.9167 38.6448
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3488329289326126 -0.99172777905286968 1.0000000180025095e-35 0.066137329671330417 -0.23041488655489625 0.17188924827519522 -1.2291473454499886 0.51688161336547822 -0.58333333333333315 -0.44738444019384821 0.457168894289186 1.0000000180025095e-35 -0.80185022711144738 -0.54077253218884114 -0.072050230503013499 1.0000000180025095e-35 -0.46687814890837837 -1.2014823440260756 -0.31936837048240385 -1.8421595884852648 0.41666666666666669 -0.23674106267790407 0.3172551724137932 2.0416666666666674
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 15 13 20 9 -4 12 -2 11 -9 23 16 -7 -1 -5 19 24 -17 -3 -18 -19 -6 -14 -11 -26
right_child=2 5 7 4 8 14 -8 10 -10 25 -12 -13 18 -15 -16 17 21 22 -20 -21 -22 -23 -24 -25 26 -27 -28
leaf_value=0.00072623332215045948 0.0054142588629723827 -7.2916626551365672e-05 0.0015513358214984253 -0.0003621523110850146 0.0083073076782833929 0.0063386741825472792 -0.0057293870954274002 -0.0017139857424878905 -0.0072029643805483264 0.0017040210736971313 -0.009877058798345913 -0.0069266609000637035 0.0075462958812161215 0.01220010613407487 -0.001306344138548559 0.007256364633755839 0.017829136651125652 0.012428352314286212 0.0038619894907478635 0.015022185194600359 -0.0055106081124622506 0.006430181623865874 0.0052571776347149525 -0.00022592838604096208 -0.0018515030433728643 -0.0043308654688042078 0.0068800133889263641
leaf_weight=167.58814010769129 927.10980857908726 468.96190950646996 332.08687377721071 282.51787632703781 580.49742314219475 417.9324555657804 434.28833274543285 759.14668937399983 217.03628936037421 791.48357398435473 1297.8348936475813 3054.9202312640846 135.72825755178928 448.71698440611362 536.44611218571663 256.51526919752359 82.298918604850769 275.22124487906694 1034.2908617369831 625.94641895592213 1305.8433649167418 922.16056319326162 612.0145785883069 162.22994243353605 1339.9501463882625 362.99542981013656 129.06544677913189
leaf_count=1406 9664 6246 4882 2628 6549 5875 6486 11778 3246 11082 25150 55723 1441 3677 7838 2046 628 1992 11676 4734 22071 8397 5202 1978 16840 5181 1584
internal_value=0 0.00322203 -0.00407915 0.00516012 0.00364523 -0.00193857 0.000913437 -0.00638805 0.00184818 0.00230417 -0.00690565 -0.00589168 0.00243217 0.00736533 0.00203252 0.00932598 0.00567089 0.010135 0.00130271 0.0127773 -0.00407912 0.00737662 0.0074943 0.00643155 -0.000341363 -0.000185978 -0.0010773
internal_weight=0 10001 7959.87 7271.78 5334.49 2729.18 2515.88 5443.99 3598.8 2081.59 5111.9 3814.07 3381.76 1735.69 954.379 1937.29 1286.98 1769.7 2639.03 882.462 1774.81 1004.46 887.236 742.727 1604.74 1154.48 1469.02
internal_count=246000 116054 129946 74024 58644 42030 32413 97533 43314 25927 92651 67501 40068 15330 13713 15380 11653 13974 31541 6780 28317 9025 7194 8527 19865 16263 18424
is_linear=0
shrinkage=0.0152673


Tree=56
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 1 19 19 19 155 21 20 109 1 2 391 6 8 6 10 19 411 135 149 155 390 119
split_gain=984.063 414.375 385.182 190.92 145.117 96.942 96.7998 94.2722 71.1646 67.9393 66.8776 64.7427 69.1598 59.2588 56.9572 55.7599 95.9747 74.2297 63.9827 48.4521 46.0738 45.7902 43.7032 38.7473 38.6168 39.1338 38.4555
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3471229168525309 -1.1118987782991112 1.0000000180025095e-35 0.066137329671330417 -0.23041488655489625 0.17456952062600092 181596.39750000005 -1.2291473454499886 0.51688161336547822 -0.58333333333333315 1.0000000180025095e-35 1.0000000180025095e-35 0.12742144408804593 -0.40911445279866326 1.0000000180025095e-35 -0.072765246449456963 0.19550885867325921 1.0000000180025095e-35 1.0000000180025095e-35 0.52035236938031604 -0.50486850701741959 116907.93000000001 0.66880526022619213 0.78933253873659137
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 6 21 13 19 10 -4 9 15 -2 12 -9 22 -7 16 -6 18 -18 -3 -21 26 -5 -12 -25 -26 -1
right_child=2 5 7 4 8 14 -8 11 -10 -11 23 -13 -14 -15 -16 -17 17 -19 -20 20 -22 -23 -24 24 25 -27 -28
leaf_value=0.0092815232372172735 0.0053090567451794298 -0.0057435392949923081 0.00152564449386789 0.0031744036182678403 -0.00011513004775285563 0.0062086303466216278 -0.005669710856227291 -0.0016903302927335777 -0.0065286967069713743 0.012404214392455412 0.0056857650737612477 -0.0098128726804668758 -0.0068630287842849861 0.01008923889317089 -0.0012878398121867181 -0.00089065537638436548 0.0061825904254327593 0.0013366339088645731 0.015887254683464237 0.0018458756062946686 -0.0092846233366459113 0.0045708591410305623 0.0098810767493265408 -0.0025468776134363134 0.0054341258631141554 0.051503297918329576 0.015155640087523882
leaf_weight=894.80102837830782 931.01965299993753 1212.171417336911 332.52363215759397 936.05843275785446 996.25982035323977 420.15882908180356 432.17761677131057 758.02975038439035 218.67121939733624 152.59605845808983 212.954330958426 1286.4687718153 3036.3171238340437 845.04546868056059 535.8537481687963 1061.8920723870397 508.08400180190802 443.38364424556494 234.01516348496079 449.20424174889922 107.13694027811289 326.25614778697491 302.14306213706732 849.48447746038437 87.448818698525429 4.400253362953662 378.97698983550072
leaf_count=6717 9664 19939 4882 9194 11820 5875 6486 11778 3241 1567 2906 25150 55723 6926 7838 13393 5580 5201 2388 6635 1743 2651 2655 12222 1084 51 2691
internal_value=0 0.00316578 -0.00403188 0.00506281 0.00375145 -0.00191243 0.000898734 -0.00632651 0.00189819 0.00244382 0.00226484 -0.00684225 -0.00583219 0.00696238 0.00199782 0.00197167 0.00336897 0.0063042 0.00925868 -0.00403137 -0.000283678 0.00972617 0.00481968 -0.000183105 -0.00152145 0.00784781 0.0110385
internal_weight=0 10022.7 7930.82 7298.18 5698.15 2724.53 2517.49 5413.34 3614.9 3396.23 2085.31 5080.82 3794.35 2083.25 956.013 3243.63 2181.74 1185.48 742.099 1768.51 556.341 1600.03 1238.2 1154.29 941.334 91.8491 1273.78
internal_count=246000 116054 129946 74024 61965 42030 32413 97533 43190 39949 25927 92651 67501 18775 13713 38382 24989 13169 7968 28317 8378 12059 11849 16263 13357 1135 9408
is_linear=0
shrinkage=0.0152673


Tree=57
num_leaves=28
num_cat=0
split_feature=20 21 21 21 20 1 20 109 21 155 391 6 8 6 391 149 1 6 20 143 10 130 141 11 391 231 118
split_gain=955.327 400.032 376.657 182.946 139.464 94.3287 81.2958 84.2304 79.6627 57.9837 58.8179 94.6792 72.4692 64.1823 57.6821 63.6203 56.5908 55.7808 55.3508 49.3909 47.3965 45.1327 46.2573 41.445 41.3224 40.1907 35.8411
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3471229168525309 -1.1118987782991112 1.0000000180025095e-35 0.49986052388137286 -0.58333333333333315 -1.8457901202353957 181596.39750000005 0.12742144408804593 -0.40911445279866326 1.0000000180025095e-35 -0.11691311612364243 0.12650512597654215 -0.24282187115445683 1.0000000180025095e-35 -0.43943191311612356 -1.161217900876085 2.3888888888888897 0.19550885867325921 0.62500000000000011 -0.2407407407407407 0.33470847084708477 -0.81178185562575544 227.97030000001908 0.20899280575539572
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 8 21 16 20 7 -4 -2 10 11 -6 13 -13 15 17 24 -10 -7 -17 -3 22 -1 -9 -5 -26 -23
right_child=2 5 6 4 9 18 -8 23 14 -11 -12 12 -14 -15 -16 19 -18 -19 -20 -21 -22 26 -24 -25 25 -27 -28
leaf_value=0.01115857617357136 0.0078279634693920637 -0.005684326379670682 -0.00072281028900963637 -0.0047191664855428883 -0.00053084344447959324 0.0076811857175074112 -0.0093652909191422797 -0.0072678891354933843 -0.00026795757306155219 0.010741548668847092 -0.0013619508606473782 0.0053427628430712188 0.00097425808650844416 0.014618115208603588 -0.0031814632328963687 -0.0019517128262423016 0.009864935445090291 0.010583992589343946 -0.00037984776226407748 0.0098613838977334636 -0.00027934075884941862 0.0071802887395619238 0.0050720009224619646 -0.0031615635709041881 0.0067928824258635598 -0.00098966724093322764 0.01685191427433053
leaf_weight=560.60363200306892 333.91798312216997 1206.1476817838848 810.55571940913796 98.169076010584831 1045.250244282186 279.41707039624453 1448.5003295093775 2354.3947338797152 177.20603451505303 163.92963890731335 1155.9061853289604 509.77409682422876 476.98396837338805 268.27409371361136 885.54512085020542 744.14769249781966 851.02265249937773 285.71575582399964 678.20182365179062 92.475975811481476 556.18737746402621 135.22748067975044 623.63298583030701 769.67567079141736 962.60648577660322 181.83718745410442 290.82322853803635
leaf_count=4130 3100 19939 12332 1013 12557 3163 28300 43853 2269 1698 14838 5654 5690 2753 12318 9982 6926 3545 10550 1199 8378 1071 4776 13048 9066 1770 2082
internal_value=0 0.00311067 -0.00398499 0.00496776 0.00368395 -0.00188657 -0.00626526 -0.00512127 0.000884441 0.00186635 0.00144215 0.0028552 0.0056822 0.00855565 -0.000173072 0.00187005 0.00682191 0.00641177 0.00196378 -0.000632964 -0.00398395 0.0095164 0.00796245 -0.00625941 0.00472922 0.00554838 0.0138085
internal_weight=0 10044 7902.14 7324.04 5713.75 2719.95 5383.13 3934.63 2519.01 3620.12 3456.19 2300.28 1255.03 778.048 2185.09 1299.55 2093.64 462.922 957.619 836.624 1762.34 1610.29 1184.24 3124.07 1242.61 1144.44 426.051
internal_count=246000 116054 129946 74024 61965 42030 97533 69233 32413 43190 41492 26654 14097 8407 29313 16995 18775 5814 13713 11181 28317 12059 8906 56901 11849 10836 3153
is_linear=0
shrinkage=0.0152673


Tree=58
num_leaves=28
num_cat=0
split_feature=20 21 21 19 20 20 19 21 21 19 21 1 1 1 143 90 135 149 143 29 143 391 6 154 390 2 21
split_gain=928.425 495.996 268.437 148.68 135.667 125.498 107.245 95.9704 91.1465 84.8483 68.4243 62.0595 61.2387 52.182 47.5453 46.8218 45.3328 45.1519 41.1163 41.084 44.178 38.9423 37.3967 37.0217 36.8803 36.8783 36.4311
threshold=-0.39425883824369934 -0.4706364644200467 0.1746120078555157 1.0000000180025095e-35 0.29935720544807254 -1.6973680938911146 0.066137329671330417 -0.88271474018548879 -1.2483043297940404 -0.23041488655489625 0.51771317850921039 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 2.7222222222222228 -1.0000000180025095e-35 0.43772782503037672 -0.1987258706506824 1.7222222222222225 1.0000000180025095e-35 3.1666666666666674 -0.80185022711144738 -0.60369256474519617 5.9285714285714297 -0.47147401979164855 1.0000000180025095e-35 0.19068494058228019
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 6 3 5 9 -1 8 14 16 -3 13 17 -4 21 22 -13 -2 23 -19 20 -10 -11 -7 24 -9 -17 -6
right_child=1 4 12 -5 26 7 -8 11 19 10 -12 15 -14 -15 -16 25 -18 18 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.011649048817931201 0.0042746313904363682 0.003905602251838068 -0.0035751691103437116 -0.00096535337037291426 -0.0061198075441245853 0.00085791045078350918 -0.0043637225176346058 -0.001712458731836077 0.0010672159239797697 -0.010957567901399706 -0.0073542858327634809 0.0015523342390506044 0.0026282663894944074 0.00015373668425852722 0.01837810076768728 0.011366765235253085 0.010747074140762336 -0.0017284823269452278 0.0067581507323901469 -0.0043745518387265318 0.013273620835567582 -0.0035438231843831621 0.008763017797174576 -0.0049509876638928118 0.0082722971413020686 0.004734774594756676 -0.0095589136537550107
leaf_weight=930.77043244987726 953.5992164760828 334.68564796075225 1041.2383694536984 690.46694649383426 1553.655494466424 161.31966155022383 544.1379838809371 105.06410247832537 1194.7930341809988 185.01096192374825 1081.9793382808566 326.49899005889893 574.37244432792068 916.65664064139128 108.90600184351206 449.60305494070053 347.91286466270685 796.71664058789611 159.42607710883021 314.75694537162781 73.405804350972176 1662.0734295137227 1173.0628502219915 75.963310580700636 445.14777140319347 357.58010556176305 1380.0884678512812
leaf_count=6682 9565 4524 16202 8110 27567 1340 7936 1247 15988 2996 20662 3562 7778 13826 806 4188 3212 9258 1795 4437 956 26532 9300 885 4696 3541 28409
internal_value=0 -0.00292289 0.00413295 0.00567089 -0.00522208 0.0065729 0.00184516 0.00543425 0.00301982 -0.00345166 -0.0040945 0.00373726 -0.00136404 -0.00281457 0.00862035 0.00646653 0.00601323 0.00177546 -0.000302735 0.0005524 0.00178295 -0.00429248 0.00781447 0.0049625 0.00634912 0.00844206 -0.00774129
internal_weight=0 10542.8 7396.14 5780.53 7114.15 5090.06 3428.61 4159.29 2884.47 4180.41 3845.72 2716 1615.61 2763.74 1443.29 1133.68 1301.51 1582.32 956.143 1582.96 1268.2 1847.08 1334.38 626.175 550.212 807.183 2933.74
internal_count=246000 166610 79390 55410 124516 47300 42094 40618 34158 68540 64016 29172 23980 43354 11446 11291 12777 17881 11053 21381 16944 29528 10640 6828 5943 7729 55976
is_linear=0
shrinkage=0.0152673


Tree=59
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 20 20 21 21 149 143 149 135 165 21 141 20 411 167 411 390 149 390 154 143 165 172
split_gain=903.703 374.122 359.418 171.411 132.232 91.2666 79.8562 75.5132 65.7069 64.7209 56.516 54.7708 54.7042 52.5595 51.527 47.9132 44.576 44.1036 43.6689 42.0671 40.4458 41.0232 39.4326 37.4774 36.4509 36.1334 35.9637
threshold=-0.049110989848547566 1.0000000180025095e-35 -0.45447813724047786 -1.3488329289326126 -0.99172777905286968 -1.1812398945549447 0.49986052388137286 -1.8457901202353957 0.34138289464776045 -0.44738444019384821 2.5000000000000004 -0.23678707398923718 0.457168894289186 32836.601250000007 -1.5274227628997041 -0.055555555555555546 -2.0097992159524432 1.0000000180025095e-35 1.7500000000000002 1.0000000180025095e-35 -0.014720089120354104 -0.58342319933459807 0.29782425509802973 1.3571428571428574 2.3888888888888897 109933.85250000002 3.2500000000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 7 13 12 20 8 -2 17 23 15 -9 -5 14 -1 19 -16 -4 22 -11 -3 -22 -7 -6 -13 -17 -15
right_child=2 5 6 4 9 18 -8 11 -10 10 -12 24 -14 26 16 25 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.013350562829345668 0.0075705003066907292 -0.0011607359966784075 -0.0023161668440603712 0.0051975257109774563 0.0078977055127927541 -0.0052718969132674069 -0.0092458363350933458 0.0030275279046555435 -0.0075804930312001802 0.0033194439906866283 0.0073497340386331749 -0.0029066134916617093 0.011348067405191637 0.0078729284270146697 0.014375163930829956 -0.0031532632368692294 0.005380951878584837 -0.0071477053275883747 0.024266774360681365 -0.0033158134584826233 0.018366913675980024 0.0039982148668260518 -0.0006071294194553514 0.00081019135675537278 0.0047393050909459522 0.0054031438938011234 0.018988571900155363
leaf_weight=300.11176234483719 336.97092619538307 344.79543539881706 1859.4150700010359 1309.7968418672681 530.48221561312675 1315.0297440774739 1426.4954085424542 787.42619254812598 1458.0855074040592 1059.6986002177 263.66005973517895 1235.4603112861514 460.08086881041527 116.20671147853136 144.98674421012402 1097.1230163313448 1240.0039299353957 581.68867744877934 12.757309984415768 280.50796062499285 53.788904674351215 355.39336575567722 629.2168447971344 263.24755835533142 163.71853477135301 127.62605691701174 177.65480463951826
leaf_count=1783 3100 4565 29655 11653 6087 22115 28300 10224 29179 12018 3090 16937 3677 867 1033 13909 10519 10399 185 3706 646 4314 10205 3074 2152 1430 1178
internal_value=0 0.00301035 -0.00389818 0.00479421 0.00338078 -0.00183662 -0.00614721 0.000844586 -0.00501083 0.00170605 0.000621219 -0.000188332 0.00680264 0.00864011 0.00758808 -6.73747e-05 0.00633106 -0.00347171 -0.00357728 0.00192355 0.002669 0.00591747 -0.00376717 0.0055594 -0.00200487 -0.00225342 0.0146324
internal_weight=0 10082.2 7849.26 7371.19 5392.22 2710.98 5325.68 2523.58 3899.19 3622.35 2828.62 2186.61 1769.88 1978.96 1685.1 2564.96 1384.99 2441.1 1957 1340.21 753.978 409.182 1944.25 793.73 1399.18 1224.75 293.862
internal_count=246000 116054 129946 74024 58644 42030 97533 32413 69233 43314 34153 29313 15330 15380 13335 31063 11552 40054 32505 15724 9525 4960 32320 9161 19089 15339 2045
is_linear=0
shrinkage=0.0152673


Tree=60
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 20 109 21 20 1 7 168 168 8 414 392 149 1 143 21 90 61 141 6 163 20 387
split_gain=877.36 362.18 351.401 187.771 141.242 78.8778 81.8893 73.0512 70.9441 69.6663 55.8177 53.5577 53.4037 53.1499 52.7741 59.072 51.8595 51.2986 50.7626 48.866 47.1 45.7901 44.9901 42.1374 40.1877 36.5744 35.4462
threshold=-0.049110989848547566 0.1746120078555157 -0.45447813724047786 -1.3488329289326126 -0.99172777905286968 0.49986052388137286 -0.58333333333333315 -1.7460870472760039 -1.5861933488948645 1.0000000180025095e-35 -0.54077253218884114 2.7500000000000004 0.75000000000000011 1.0000000180025095e-35 -1.0000000180025095e-35 -0.2309616026761426 -0.46807723490841552 1.0000000180025095e-35 2.6111111111111112 -1.5274227628997041 -1.0000000180025095e-35 0.0037499999999999968 0.055555555555555559 -0.0083500417710944009 11251.665000000003 -1.9246534744984347 -0.0098228363625392414
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 7 12 10 6 -4 -2 -3 16 -5 17 19 23 -9 -16 -6 -10 -18 -1 -11 25 -22 -12 -13 -21 -8
right_child=2 8 5 4 9 -7 26 14 11 20 13 24 -14 -15 15 -17 18 -19 -20 21 22 -23 -24 -25 -26 -27 -28
leaf_value=0.0130944697743621 0.0064631760813923843 0.0050467118244611562 -0.00060891539130260915 0.0015590425935435889 0.0042271621379853502 -0.0091807515468929693 -0.003998297209405882 -0.0037631353023856672 -0.0055002741949199026 -1.4422802025265645e-05 0.009074276488751188 0.028926838228290355 0.016173614743202298 0.0050500847817742866 -0.0026263415176721811 0.0038685727576419095 -0.0020453061421567961 -0.00034087151347634328 0.0063002747556490128 0.012651142725859465 0.0084896773790577498 0.00042500603570921983 0.0019856919448995804 0.018281275717804246 -0.00199344536821727 0.0063396874613910314 -0.0073912340154587671
leaf_weight=323.26326794922352 442.64970222115517 264.05862013995647 805.14655968546867 393.12604097276926 511.07345341518521 1414.7667963020504 1182.0265286639333 704.7532218657434 1292.1096461154521 451.54637886956334 551.29041012376547 20.512036304920912 191.49663408100605 683.23967691510916 528.2959316894412 849.39652372151613 1758.7931105978787 694.54852452874184 187.45263605937362 274.49488730728626 619.67307813093066 244.60826662927866 420.48139856755733 150.80403736978769 17.565740283578634 1051.9741274341941 1894.8078484460711
leaf_count=1904 4151 3117 12332 3495 6248 28300 20647 10093 21948 5508 4519 306 1300 6144 7396 10773 22686 10542 2280 2028 6526 2147 4895 1172 270 9019 36254
internal_value=0 0.00295847 -0.00385239 0.00452345 0.00309244 -0.00608684 -0.0049565 0.000831165 -0.00237988 0.00148038 0.00666628 -0.00335335 0.00844777 0.00810855 -0.000362097 0.00137134 -9.59747e-05 -0.00370134 -0.00123623 0.00766031 0.00408295 0.00653483 0.00587014 0.0110695 0.0144877 0.00765437 -0.00609109
internal_weight=0 10102.1 7821.84 7813.32 5727.48 5296.75 3881.98 2525.1 2288.79 3949.02 1778.46 2024.74 2085.84 1385.33 2082.45 1377.69 2457.32 1986.66 1946.25 1894.34 1491.7 1571.08 1040.15 702.094 38.0778 1326.47 3076.83
internal_count=246000 116054 129946 79871 63473 97533 69233 32413 36183 48143 15330 33066 16398 11835 28262 18169 31214 32490 24966 15098 16929 13194 11421 5691 576 11047 56901
is_linear=0
shrinkage=0.0152673


Tree=61
num_leaves=28
num_cat=0
split_feature=21 21 19 19 411 11 19 11 19 19 24 119 17 155 163 2 147 7 8 119 19 149 7 19 112 143 143
split_gain=773.081 360.508 258.84 153.904 145.594 137.453 119.167 106.491 81.444 74.2303 56.8936 64.9201 55.9048 54.6029 51.9562 47.2767 56.7833 46.9665 48.4219 46.9153 46.7167 46.0603 38.7106 38.4467 37.2545 36.9155 32.5253
threshold=1.0000000180025095e-35 -1.2291473454499886 1.0000000180025095e-35 -0.31528071226839544 1.0000000180025095e-35 1.0000000180025095e-35 0.042042249439647579 1.0000000180025095e-35 0.0028346554504373738 -1.0000000180025095e-35 3.5000000000003335 0.51281287246722307 1.0000000180025095e-35 118299.98250000001 1.0000000180025095e-35 1.0000000180025095e-35 0.41891891891891903 -0.67014990358897797 0.51063775510204101 -0.10995232419547078 -0.36229080842168021 -0.27498209239536847 -0.43328979287180441 -0.4294617065977519 -0.64902126047634823 1.8333333333333335 2.6111111111111112
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 3 23 5 13 7 14 10 -7 11 24 15 19 -2 16 21 -9 20 -5 -19 22 -11 -3 -1 -4 -21
right_child=6 2 25 4 -6 9 -8 17 -10 12 -12 -13 -14 -15 -16 -17 -18 18 -20 26 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.014339318352779518 -0.0062561801852369066 0.022316112962469076 -0.0059416104390337615 -0.0038301455530280696 -0.0033369212819477877 0.0010028885322525825 -0.0093209448188968386 -0.0069557237498939235 0.00080282339286402542 0.0062086343530293776 0.0030960447271596546 0.011933654839218728 0.011870943355079617 0.0069811935513056089 0.00019621622955513321 0.0013588466688579598 0.0006231586505823861 0.023044086370441502 -0.0039121827953157691 -4.1952343498709776e-05 0.0017740497943172495 0.006185586167455728 0.017967311732374508 0.0084474691635231542 0.0054876874265707499 0.00076896247453776454 0.0066372971950434635
leaf_weight=125.83448053151369 2439.8918604888022 53.117507554590702 1367.6424278728664 781.60823677480221 1347.4804402701557 927.01416417211294 1086.6717322021723 230.15708673745394 471.97748287022114 105.40324791520834 504.34578139334917 902.72970296442509 343.17441670969129 236.56718344241381 327.12791626527905 543.36178695037961 261.14808683469892 24.585967753082514 411.44375057145953 1826.338492076844 964.44696225970984 552.55423073470592 185.72933669388294 447.30318995565176 1042.5016478523612 219.30666217952967 186.88420823961496
leaf_count=973 45375 483 21678 10940 19119 10126 21057 3702 4974 1104 4363 7165 3141 2691 5771 6220 3042 321 6923 24463 15357 6186 1867 4332 8917 3319 2391
internal_value=0 0.00209269 0.000610056 0.00175479 0.00119154 0.00221875 -0.00478844 -0.00366599 0.00665521 0.0045837 0.00772403 0.0088462 0.00624576 -5.51707e-05 -0.00549008 0.00506767 0.00688282 -0.000564781 0.000479822 -0.000654495 0.00231661 0.00880892 0.0137488 0.00994619 0.00645117 -0.0050085 0.00057412
internal_weight=0 12432 9384.63 7797.68 7297.26 5949.78 5484.33 4397.65 3047.39 2918.39 2575.41 2071.07 1991.37 3031.4 2767.02 1648.2 1104.83 1630.63 1400.48 2794.83 989.033 843.687 291.133 500.421 1168.34 1586.95 2013.22
internal_count=246000 147494 121102 96105 91290 72171 98506 77449 26392 31686 21418 17055 21560 40485 51146 18419 12199 26303 22601 37794 15678 9157 2971 4815 9890 24997 26854
is_linear=0
shrinkage=0.0152673


Tree=62
num_leaves=28
num_cat=0
split_feature=21 21 19 10 414 19 391 391 90 10 411 141 118 70 155 52 149 157 19 130 19 17 7 391 391 391 130
split_gain=751.614 347.321 251.598 155.095 158.804 117.498 115.853 136.713 122.301 114.862 81.177 80.6031 80.3554 62.143 64.5915 60.9513 55.4584 54.0052 51.9744 45.8823 44.2672 42.5689 41.0287 62.0924 51.2916 39.2576 37.6783
threshold=1.0000000180025095e-35 -1.2291473454499886 1.0000000180025095e-35 -0.55809641532756482 -1.0000000180025095e-35 1.0000000180025095e-35 0.12742144408804593 -0.80185022711144738 -1.0000000180025095e-35 -0.23176761433868973 1.0000000180025095e-35 -0.27777777777777773 0.59028776978417274 -0.30540540540540534 33998.602500000008 3.5000000000003335 -0.21135171585026369 13162.500000000002 -0.37481395413786084 0.62500000000000011 -0.24626255267163494 1.0000000180025095e-35 -0.60819804689929702 0.29953522766670132 -0.80185022711144738 -0.92629748585859206 0.79166666666666685
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 12 3 -3 18 9 7 25 -9 -2 13 -10 20 -11 22 19 -13 -8 -5 -14 -1 -20 -15 24 -24 -6 -4
right_child=5 2 26 4 6 -7 17 8 11 10 -12 16 15 14 -16 -17 -18 -19 21 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.011623217259920063 -0.0064561564390693254 -0.0027141325178498383 -0.0063268386077097024 0.014404268688229664 0.0020605277772554136 -0.0089166378430887878 8.9052342880722757e-05 0.0014704531480011786 0.012499739536772976 -0.0033094444177688876 -0.0063611067448239213 0.010221535559676512 0.008888845997101007 -0.0047449632329410723 0.013730246640106076 0.0026267398221289976 0.0037195082226911848 0.018333075057354046 -0.0030296785871953892 0.015932940008779359 0.0032962543381817519 0.0037294515843922529 -0.0044444756025619177 -0.0027446882939199282 0.0081663691332368796 -0.0069577754625393569 -0.00087617136959716746
leaf_weight=167.12671165168285 1801.4172976352274 1483.2245345041156 1180.2210159003735 46.745314903557301 246.39748212322593 1219.5772540345788 1417.9236848391593 701.6878351084888 847.7414256259799 724.13124309852719 578.66698977351189 523.64138663932681 881.25757737457752 211.51800363138318 106.4522111415863 275.42141314595938 751.64148265123367 38.689853526651859 1284.4987986944616 292.8392067104578 1444.6922326609492 260.10169944167137 89.90714256465435 298.47405015304685 431.01419104635715 205.21490204334259 399.91544345766306
leaf_count=1309 33576 20998 18784 469 2761 23664 17581 8271 8465 12670 10456 5582 7014 3427 1581 2335 8313 423 17658 2295 13439 3028 1441 4981 6710 2556 6213
internal_value=0 0.00205788 0.000600497 0.00172581 0.0027686 -0.00473561 0.00417187 0.00576478 0.00701245 -0.00353092 -0.0013673 0.00883953 0.00652364 0.000180674 0.00241099 0.00913724 0.00639766 0.000582379 -0.00139921 0.010656 0.00416668 -0.00188522 0.00123084 0.00278538 0.00597138 -0.00201843 -0.00495342
internal_weight=0 12449 9387.64 7807.51 6324.28 5461.16 4732.94 3276.32 2824.71 4241.58 2440.16 2123.02 3061.34 1861.5 1137.37 1449.52 1275.28 1456.61 1591.35 1174.1 1611.82 1544.6 1030.91 819.395 520.921 451.612 1580.14
internal_count=246000 147494 121102 96105 75107 98506 53952 35948 30631 74842 41266 22360 26392 30810 18140 11644 13895 18004 21155 9309 14748 20686 16559 13132 8151 5317 24997
is_linear=0
shrinkage=0.0152673


Tree=63
num_leaves=28
num_cat=0
split_feature=20 20 19 1 118 164 19 135 143 2 1 19 6 11 8 6 7 11 149 2 13 157 171 7 135 20 7
split_gain=838.347 281.622 183.479 162.056 148.419 109.811 106.461 106.164 79.2548 76.8801 76.588 66.2852 65.1541 54.7752 54.0245 80.4582 56.8322 51.1656 50.3965 50.0217 46.3213 43.1098 42.2945 42.1699 41.5303 41.1352 38.6066
threshold=-0.63287083336150685 0.33014794124083729 -0.33317285005261182 1.0000000180025095e-35 -0.0075539568345323735 37601.448750000003 -0.23999248241935275 0.71051032806804393 2.3888888888888897 1.0000000180025095e-35 1.0000000180025095e-35 -0.25931946189574345 -0.48520467836257303 0.31985698569856991 1.0000000180025095e-35 -0.028517126148705094 -0.096411021956832724 1.0000000180025095e-35 -0.013124371921925478 1.0000000180025095e-35 1.0590516823426745 1.0000000180025095e-35 11.250000000000002 -0.19593207688001488 0.72934386391251527 -2.0097992159524432 -0.6171549418423834
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 26 6 13 8 -1 12 10 18 20 -3 -8 24 15 -14 -17 -13 -5 -12 -6 -9 -7 -10 -4 -11 -2
right_child=1 11 4 9 5 22 7 21 23 25 19 17 14 -15 -16 16 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.011355848479049737 3.096806679125412e-05 0.0033039763800259995 -0.0058177340803009523 0.013530798900859191 -0.0033316118151171612 0.0091843919516087832 -0.0035048175159635461 0.0063410367789816617 9.9968500579639672e-05 0.018277925024080058 0.0050180220311771386 -0.0077157465027622675 0.0024600678679076999 -0.00033178698005882049 -0.00027710086334402107 -0.0038388476680190982 0.017522474910286322 -0.0039270923309633393 0.0072155622480950575 -0.0008206550123913077 0.0038819280447061431 0.019287396085012617 -0.00028282125935693783 0.010981498660495902 0.00068974982236246396 0.0042519231166080708 0.013140836880923669
leaf_weight=299.54640473052859 67.445597853511572 174.84181301295757 2008.3614853620529 615.52878785505891 2238.2515125721693 422.02424581348896 665.72774643078446 480.75208327174187 142.13281260430813 51.360175982117653 626.12673801183701 2221.7985136769712 834.54311300441623 760.79851796850562 1179.3578599467874 34.880254179239273 153.68319009616971 1348.9239943958819 584.45257799327374 748.60173618048429 227.38836194202304 69.531667143106461 146.21607592701912 205.34594308957458 255.10906286165118 1083.4041105993092 257.89591999351978
leaf_count=2556 714 2365 33883 5378 31957 4699 7665 4820 1899 341 8105 41984 9014 11338 13843 402 1387 22722 5416 10095 3067 577 1886 2707 4038 10549 2593
internal_value=0 -0.0023746 -0.000773412 0.00460907 -0.00124428 0.000435486 0.00262549 0.00185719 -0.000417102 0.00776343 -0.00105104 -0.00583704 0.000674991 -0.00388884 0.00194276 0.00451016 0.0135227 -0.00628736 0.0104643 0.00183228 -0.00266238 0.00799994 0.00673299 0.00655948 -0.00508025 0.00489793 0.0104529
internal_weight=0 11851.3 8105.7 6052.77 7780.36 4756.09 3718.02 3418.48 4187.85 2334.75 3840.37 3745.56 2868.19 3024.27 2202.46 1023.11 188.563 3570.72 1199.98 1374.73 2465.64 550.284 568.24 347.479 2263.47 1134.76 325.342
internal_count=246000 184052 116981 61948 113674 64415 40264 37708 57830 21684 53224 67071 32311 49259 24646 10803 1789 64706 10794 18200 35024 5397 6585 4606 37921 10890 3307
is_linear=0
shrinkage=0.0152673


Tree=64
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 19 19 19 20 21 10 8 387 143 166 135 19 112 10 90 391 20 0 411 149 149 1
split_gain=814.843 329.719 323.982 172.683 125.757 88.5058 86.8022 79.312 68.0087 62.7893 61.6804 60.5612 59.3282 56.2699 52.2015 49.9197 48.8152 47.9502 47.746 46.8848 46.8911 46.6188 46.1772 42.2369 41.5175 40.803 40.2062
threshold=-0.049110989848547566 -0.45447813724047786 0.1746120078555157 -1.3488329289326126 -0.99172777905286968 -0.20494525875886938 0.066137329671330417 0.17188924827519522 -1.6973680938911146 0.33355253456915318 -0.58254360664743843 0.51063775510204101 -0.056328829545551164 1.5000000000000002 86467.668750000012 0.457168894289186 1.0000000180025095e-35 -1.0000000180025095e-35 0.045117428924598274 -1.0000000180025095e-35 -0.66458914984868689 0.49986052388137286 1.0000000180025095e-35 1.0000000180025095e-35 -0.050780194320468798 -0.21757018075529433 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 6 3 16 15 -3 10 12 -4 21 -2 13 17 22 18 -5 19 -6 -10 -1 -21 26 -12 -20 -22 -19 -7
right_child=1 5 8 4 7 9 -8 -9 14 -11 11 -13 -14 -15 -16 -17 -18 25 23 20 24 -23 -24 -25 -26 -27 -28
leaf_value=0.0045143406915266037 -0.0038955967097724599 0.0010187405486685734 0.0062732000765259805 0.004747088084258993 0.00061817176469416524 -0.005397354271049812 -0.0054979703636016779 -0.0071139631797144023 -0.0057954219289339352 -0.008661459898976126 0.0047525925982016557 -0.0017068759805935467 0.00011049206732906482 0.012790987667568317 0.0064734008892784189 0.010559227754774416 0.00078512957698723671 0.0096696779072208243 0.00096015440620312903 0.0023281605927173549 0.013670154448338174 -0.008362652998185607 -0.0043669248597044867 -0.0069529660374218526 0.0081080456165215468 0.0036271035669673307 -0.00095769921631806752
leaf_weight=462.74947204440832 338.98319228738546 392.60566091537476 198.36652267724276 1332.040228433907 640.15928623452783 1453.8021961636841 425.91665587201715 238.80938934907317 1094.6815767139196 1906.2668547220528 1000.8642127253115 437.46255822107196 1950.7559571042657 179.59272839128971 124.707922834903 470.98997768759727 198.88933529704809 417.23395491763949 643.36012536287308 162.20050370693207 694.48117392510176 755.08030053600669 147.44076601788402 207.36409571021795 593.73367553204298 715.1310038305819 714.74907771870494
leaf_count=3811 4556 5975 2312 11653 7134 24946 6486 3687 18727 40082 11829 5672 25040 2036 1911 3677 1868 4339 9811 1261 4975 14862 1834 3422 4483 7943 11668
internal_value=0 -0.00374004 0.00283401 0.00429846 0.00292758 -0.00593171 0.000780106 0.00140335 -0.00224713 -0.0064986 0.00205554 0.00320377 0.00195246 0.00482844 -0.00306854 0.00627143 0.00803549 0.00397422 -0.00368552 0.00878428 0.0101395 -0.00508475 0.00357313 -0.000959085 0.0111154 0.00586297 -0.0039385
internal_weight=0 7752.76 10145.7 7877.17 5765.12 5222.5 2530.26 3962.09 2268.48 4829.9 2104.34 1765.36 3723.28 1327.9 2070.11 1803.03 2112.05 1772.52 1945.41 1913.16 1450.42 2923.63 1148.3 850.724 1288.21 1132.36 2168.55
internal_count=246000 129946 116054 79871 63473 97533 32413 48143 36183 91558 25927 21371 44456 15699 33871 15330 16398 19416 31960 14530 10719 51476 13663 13233 9458 12282 36614
is_linear=0
shrinkage=0.0152673


Tree=65
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 19 19 19 20 21 387 21 7 168 109 8 168 8 20 391 160 165 21 122 19 19 158
split_gain=791.125 322.256 313.108 165.834 121.037 86.7129 84.3728 77.1822 66.1526 62.0304 56.3841 54.8909 52.5355 50.2538 48.5787 48.2791 48.1943 46.6399 45.9238 45.0465 43.3532 42.5573 39.9573 39.0902 39.0387 38.3197 34.5969
threshold=-0.049110989848547566 -0.45447813724047786 0.1746120078555157 -1.3488329289326126 -0.99172777905286968 -0.20494525875886938 0.036948907581812025 0.16380191123207924 -1.5861933488948645 0.33355253456915318 -0.056328829545551164 -1.8457901202353957 -0.54077253218884114 2.7500000000000004 -0.58333333333333315 1.0000000180025095e-35 0.75000000000000011 0.51063775510204101 0.49986052388137286 -0.80185022711144738 10751.220000000001 37614.352500000015 -1.6426344058948754 1.1896551724137934 -0.24962301927574029 1.0000000180025095e-35 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 6 3 16 12 -3 11 10 -4 18 14 -2 -5 24 -6 23 19 21 26 -1 -15 -13 -21 -14 -10 -24 -7
right_child=1 5 8 4 7 9 -8 -9 13 -11 -12 17 15 20 -16 -17 -18 -19 -20 22 -22 -23 25 -25 -26 -27 -28
leaf_value=-0.00036780350880164328 0.0083090645255592347 0.0010023187689581347 0.004929865109457897 0.0012270047296302823 0.007476002005806095 -0.0044080471820473234 -0.0049989093356247721 -0.00681131638942246 0.0052755472971600294 -0.0085964867943034602 0.00013433521741308208 0.0013788910046429841 0.012824691409254935 0.03171775276231216 0.0021017461246458703 0.0046338255986758618 0.015116015482866825 -0.0031483278846672156 -0.0082971455129624925 0.013470623065621558 -0.0002492123662746487 0.0090282573722663042 0.0076778803881120067 0.0051600109902083845 -0.004043910563526024 -0.0005625805134222558 0.0033254976923539552
leaf_weight=168.26490589231253 287.17566733062267 392.94643510878086 265.29259503632784 398.82062378525734 592.7036449201405 2018.1461228094995 478.51009334996343 250.46753434836864 110.058135535568 1891.4665880724788 1943.3187168426812 1118.1490153521299 481.77637238055468 17.386499557644129 1179.8133975379169 694.05066490918398 196.45349307358265 447.08072996139526 749.46756008639932 255.34625115245581 21.309184420853853 200.76102279126644 1359.7260712236166 236.34993692487478 1849.8861797377467 143.31649449467659 142.97712731733918
leaf_count=1414 2508 5975 3117 3495 6134 34424 7238 3882 1574 40082 24923 14371 3781 248 13204 6144 1300 6079 14862 1431 328 2217 10833 1910 30916 1420 2190
internal_value=0 -0.00369572 0.00278556 0.00422036 0.00287678 -0.00587245 0.000767422 0.00138044 -0.00221732 -0.00643693 0.00193541 0.00211614 0.00614837 -0.00317099 0.00390463 0.00753139 0.00787151 0.00110306 -0.00502988 0.00712657 0.0139677 0.00255139 0.00784889 0.010317 -0.00351543 0.00688608 -0.00389191
internal_weight=0 7726.68 10164.3 7900.41 5777.3 5195 2531.68 3966.3 2263.93 4802.06 3715.84 2053.17 1811 1998.64 1772.52 1412.18 2123.11 1765.99 2910.59 1926.65 38.6957 1318.91 1758.39 718.126 1959.94 1503.04 2161.12
internal_count=246000 129946 116054 79871 63473 97533 32413 48143 36183 91558 44261 25175 15330 33066 19338 11835 16398 22667 51476 15098 576 16588 13684 5691 32490 12253 36614
is_linear=0
shrinkage=0.0152673


Tree=66
num_leaves=28
num_cat=0
split_feature=20 21 21 20 1 109 130 21 11 109 21 90 24 129 90 1 118 119 248 0 390 411 21 1 25 1 20
split_gain=769.313 468.325 172.249 149.294 111.432 101.454 94.4461 76.1049 71.9979 63.2586 59.4036 51.7848 46.7761 42.1174 41.8646 41.7951 40.5998 39.4855 39.1631 38.8138 38.0847 37.7037 35.4127 35.0174 32.1164 32.0864 31.9116
threshold=-0.63287083336150685 -0.55092222074356589 0.38034479682904804 0.12356881070161159 1.0000000180025095e-35 -0.41666666666666657 0.62500000000000011 -0.73924480687859639 0.093784378437843804 -0.58333333333333315 0.093766758909517342 -1.0000000180025095e-35 2.5000000000002225 -0.5108175359488899 -1.0000000180025095e-35 1.0000000180025095e-35 0.0802158273381295 0.72377830750893934 0.63888888888888895 1.0000000180025095e-35 -0.26524235613468555 1.0000000180025095e-35 -2.0621762643796608 1.0000000180025095e-35 -0.3501999999999999 1.0000000180025095e-35 -1.6973680938911146
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 6 4 5 7 13 8 -1 20 -9 21 -6 19 -3 -8 -7 -16 -11 26 22 -2 25 -10 -4 -24 -5 -13
right_child=1 3 23 10 11 15 14 9 12 17 -12 18 -14 -15 16 -17 -18 -19 -20 -21 -22 -23 24 -25 -26 -27 -28
leaf_value=0.0067183671355824318 -0.0046637395979391072 0.0076346336566645934 -0.00354629810186218 -0.0050148097715110541 0.0043403543426453611 -0.0054511592201699037 0.00082630659356059267 0.0058778263000924405 0.01709778215172959 -0.0015728368072015018 -0.0082670936795599167 0.016185769881451602 -0.0018898367288793132 3.9291703713135121e-05 0.0032322607677817104 -0.0012669213338786637 0.010758170082252584 0.0047209931215141977 0.0056922397851424909 -0.0032345423479032895 0.00039949776058126937 -0.0079413383433013119 0.044453111251547404 0.0023873099214674052 0.0048743209673969582 -0.00050778046257044754 0.0098756240069645118
leaf_weight=1200.3605402223766 583.09057766571641 199.92166303098202 639.9166548512876 1031.5457783490419 554.57051918283105 1634.9992901645601 253.89319077506661 604.361572150141 62.554691553115845 994.0498049929738 2002.1890259645879 253.7375083938241 309.4593062363565 1153.8786286599934 265.60403128713369 853.37984458357096 470.80206441506743 302.92000075802207 391.58851145207882 119.71607296913862 844.92020635306835 586.60694305598736 4.6706322878599158 361.50692641735077 824.01268572360277 579.98781076073647 799.00206423923373
leaf_count=9224 7454 2643 9891 17729 5149 27771 3031 6102 493 11723 42636 1617 3485 16010 3272 13307 5055 3324 3256 1352 10333 11112 54 4725 9004 9311 6937
internal_value=0 -0.00229242 0.00438639 -0.00436818 0.0055233 -0.00218947 0.00217038 0.00370603 0.000709878 0.00179894 -0.00635874 0.00833792 0.00328172 0.00116866 0.00621358 -0.00402009 0.00805781 -9.52881e-05 0.00986569 0.00487388 -0.00166189 -0.00461574 0.00597381 -0.00139511 0.00511912 -0.00339869 0.011408
internal_weight=0 11781.2 6102.01 8042.51 5100.59 3842.18 3738.72 3101.69 2748.42 1901.33 4200.33 1998.9 1320.41 1353.8 990.299 2488.38 736.406 1296.97 1444.33 1010.95 1428.01 2198.14 891.238 1001.42 828.683 1611.53 1052.74
internal_count=246000 184052 61948 140519 47332 59731 43533 30373 32175 21149 80788 16959 14388 18653 11358 41078 8327 15047 11810 10903 17787 38152 9551 14616 9058 27040 8554
is_linear=0
shrinkage=0.0152673


Tree=67
num_leaves=28
num_cat=0
split_feature=21 21 19 409 19 11 391 391 391 391 411 19 391 155 155 109 391 165 149 392 388 8 411 6 392 141 143
split_gain=667.746 308.24 229.488 145.615 114.531 100.864 86.4941 116.856 78.6623 99.1949 75.5464 63.7846 59.859 59.6452 56.1824 54.5418 51.871 50.6272 50.0376 48.7149 59.559 41.8487 38.3628 41.9316 52.6457 38.2824 36.3279
threshold=1.0000000180025095e-35 -1.2291473454499886 1.0000000180025095e-35 -1.0000000180025095e-35 0.042042249439647579 1.0000000180025095e-35 0.12742144408804593 1.0000000180025095e-35 -0.80185022711144738 -0.13637983244433508 1.0000000180025095e-35 -0.38103144053362498 0.049180694651566131 116907.93000000001 20145.960000000003 -0.24999999999999997 -0.92257102786474277 6975.326250000001 -0.47408841764994508 -0.17120751453753016 0.45678925033826762 1.0000000180025095e-35 1.0000000180025095e-35 -0.50939849624060141 0.0080663032771929478 0.24074074074074076 2.6111111111111112
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 3 11 5 17 7 8 16 15 19 -3 -9 18 -8 25 -5 -2 -13 -1 21 -21 23 -7 -25 -10 -20
right_child=4 2 -4 6 -6 22 14 12 9 -11 -12 13 -14 -15 -16 -17 -18 -19 26 20 -22 -23 -24 24 -26 -27 -28
leaf_value=0.004071720995747769 -0.005909994970798093 0.015044672312442182 -0.0048034811992468925 0.0018658395377853653 -0.0090473789246468973 -0.0049317567041213071 -0.00111399472746115 0.016876773445513658 0.011835719173496731 0.00026919815169116284 0.0018136322165340144 0.0025025189797507966 0.0067994660005258707 0.0061222459826859596 0.0073564200158310368 0.0035483290328838803 -0.0088467611641675926 0.0010681484408115133 -0.0031517348422452104 0.013837386483418902 0.0054718200977668273 0.0071052273772661623 -0.0047585286080563645 -0.0014472433834090818 0.0055045145242510821 0.0038226809249755204 0.0032080006044541121
leaf_weight=716.2760205976665 2436.6223682463169 58.011103138327599 1560.9809413701296 256.62055186182261 1049.5131501406431 234.298399746418 1156.7121920958161 240.86070057377219 569.67743502929807 770.33349808678031 739.70365856960416 551.32747676596045 331.62760710343719 247.9878352470696 216.43315850198269 563.46808949112892 177.32480119168758 266.62224867939949 2285.5066213272512 599.58607490360737 702.00605641305447 348.22351138293743 363.10117812082171 477.81081376597285 537.70243188738823 189.07351940497756 228.89504791796207
leaf_count=6411 46430 534 24997 2940 21057 3736 14941 2350 5795 9124 6960 6990 3542 2815 2413 6256 2314 4716 30930 4424 5745 2852 6423 7962 8182 2175 2986
internal_value=0 0.00191897 0.000540721 0.00160552 -0.00451898 -0.00341537 0.00341206 0.00482546 0.00340844 0.00463668 0.00608928 -0.000787953 0.0110597 -0.00106878 0.000215306 0.00717385 -0.00249265 -0.00521832 -0.00165381 0.00742183 0.00887008 0.0113757 -0.000387657 0.000875419 0.00222497 0.00985255 -0.00256893
internal_weight=0 12510.6 9404.84 7843.86 5365.67 4316.16 4472.13 3098.99 2526.5 2092.55 3105.8 3371.73 572.488 3313.72 1373.15 1322.22 433.945 2703.24 3065.73 2366.09 1649.82 947.81 1612.91 1249.81 1015.51 758.751 2514.4
internal_count=246000 147494 121102 96105 98506 77449 51850 34496 28604 23350 26392 44255 5892 43721 17354 14226 5254 51146 40906 19432 13021 7276 26303 19880 16144 7970 33916
is_linear=0
shrinkage=0.0152673


Tree=68
num_leaves=28
num_cat=0
split_feature=20 21 21 20 21 19 19 19 20 21 10 8 389 149 143 155 1 10 20 168 391 19 149 19 1 20 109
split_gain=742.037 301.218 284.498 153.304 109.591 84.0702 80.4744 73.2539 63.9503 59.7467 58.5394 55.8863 56.1178 54.4676 52.204 49.4338 47.1103 46.0555 45.0491 44.8959 42.4552 40.2184 40.073 39.3245 38.711 37.8846 37.4139
threshold=-0.049110989848547566 -0.45447813724047786 0.1746120078555157 -1.3488329289326126 -0.99172777905286968 -0.20494525875886938 0.066137329671330417 0.17188924827519522 -1.6973680938911146 0.33355253456915318 -0.58254360664743843 0.51063775510204101 0.5309879781417487 -0.44738444019384821 2.5000000000000004 86505.97500000002 1.0000000180025095e-35 0.045117428924598274 0.49986052388137286 0.75000000000000011 -0.80185022711144738 -0.34657249725234812 -0.19168877239106538 -0.23674106267790407 1.0000000180025095e-35 -1.9246534744984347 -0.41666666666666657
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 6 3 19 21 -3 10 13 -4 18 -2 12 22 26 16 17 23 -10 24 20 -1 -5 -12 -15 -7 -22 -6
right_child=1 5 8 4 7 9 -8 -9 15 -11 11 -13 -14 14 -16 -17 -18 -19 -20 -21 25 -23 -24 -25 -26 -27 -28
leaf_value=-0.00045227375253474789 -0.0038918665930137816 0.0010438409658440513 0.0061231851812605332 0.014729720439164243 0.0092000998717574941 -0.0052247849186968006 -0.0053857090990045101 -0.006936234777499317 -0.0056174092106006449 -0.0084364295815450643 0.010768819831279194 -0.0017028338881260408 0.00058446668693464714 0.0063491798458371398 0.0072567490911059802 0.0063387163487517934 0.0026809615078751017 -0.0008421974480673246 -0.0081704921108539958 0.014465820192562831 0.011820507015668624 0.0052531349929429748 0.0039676551850756601 -0.0022241012317466436 -0.00084848574971135577 0.0063319780646074932 0.0025817618953984582
leaf_weight=168.84246821701527 338.78351166471839 392.01811737567186 199.52711082994938 112.37454148381948 339.12730810791254 1433.1210136376321 421.98947320505977 234.86304851993918 1078.1016157157719 1855.7792945578694 371.05155765637755 437.22757630050182 513.85513151437044 135.90974079817533 269.13145316392183 125.40843990445137 1063.5224338285625 844.70557399094105 738.75784910097718 199.60329883545637 378.60526049882174 1718.3602133393288 457.2201907299459 1438.317612990737 710.00444950535893 1398.5060880854726 495.45781095698476
leaf_count=1414 4556 5975 2312 790 3613 24946 6486 3687 18723 40082 4156 5672 6118 1433 3096 1916 11915 13232 14862 1300 2572 14540 5425 18499 11668 11112 5900
internal_value=0 -0.0036011 0.00268431 0.00404023 0.0027491 -0.00573031 0.000695257 0.00132287 -0.00210882 -0.00629279 0.00191147 0.00302186 0.00456789 0.00184411 0.00085316 -0.00291574 0.000195825 -0.00352469 -0.00490873 0.00752987 0.0068123 0.00584138 0.00702738 -0.0014774 -0.00377943 0.00750764 0.00528361
internal_weight=0 7669.81 10200.4 7952.62 5807.06 5129.68 2540.13 3976.33 2247.74 4737.66 2118.14 1779.35 1342.13 3741.47 2906.88 2048.22 2637.75 1922.81 2881.88 2145.56 1945.95 1830.73 828.272 1574.23 2143.13 1777.11 834.585
internal_count=246000 129946 116054 79871 63473 97533 32413 48143 36183 91558 25927 21371 15699 44456 34943 33871 31847 31955 51476 16398 15098 15330 9581 19932 36614 13684 9513
is_linear=0
shrinkage=0.0152673


Tree=69
num_leaves=28
num_cat=0
split_feature=20 21 21 109 1 19 2 119 391 10 19 20 19 21 149 130 57 389 8 19 411 20 149 20 141 152 391
split_gain=720.744 296.424 264.99 224.703 121.284 86.5404 83.0389 79.9107 77.8712 81.1436 71.9034 71.6206 69.3629 57.986 56.1633 54.4032 53.8009 50.0231 69.618 46.2777 45.855 45.2479 38.6401 37.5465 37.0032 37.2088 36.4331
threshold=1.0000000180025095e-35 -0.70835755058453587 -0.45447813724047786 -0.58333333333333315 1.0000000180025095e-35 -0.22703662689892457 1.0000000180025095e-35 0.51281287246722307 -0.80185022711144738 -0.29288559263837383 0.052622876335499676 -1.6973680938911146 0.14515642090416706 0.38034479682904804 -0.21757018075529433 0.62500000000000011 0.031200000000000023 0.043981449847253752 1.0000000180025095e-35 -0.31528071226839544 1.0000000180025095e-35 -1.4667066540297049 -0.52480564017390718 -1.9246534744984347 -0.16666666666666663 2.8125000000000004 0.11717319917109396
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 12 11 8 -4 -6 19 -5 -10 17 -3 15 20 24 22 -9 18 -11 -1 -7 -8 -2 -21 25 -13 -17
right_child=2 3 5 4 6 13 21 16 9 10 -12 14 -14 -15 -16 26 -18 -19 -20 23 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.012338296510021322 0.0048764008186828857 0.013270745440775984 0.0019355304930848945 -0.0093908709006767163 0.0055940920799990726 -0.0038453236843458576 0.006251033928486565 0.010185564838718688 -0.0048790721803031352 0.0087146893241568345 -0.0068003368864760338 0.013493252473003273 -0.0068112423658488333 -0.0086312311596182887 0.0020575511972748474 0.0086537324687551553 0.0014883480333988072 -0.0016496963599668445 0.00027859944825450267 0.012319257611180814 -0.008280650129359789 -0.0020305911221524739 -0.0012757390489899682 0.0030003962256881503 0.0039072086228025766 -0.0054702214003211451 0.00057268823325254663
leaf_weight=152.35834435373545 293.40099080651999 237.65715005993843 311.34566582739353 344.39942712336779 919.01081966608763 2072.8970041796565 184.61683633923531 1221.1134379990399 1189.1484782025218 384.48736906051636 292.13182992488146 271.53608083352447 273.55948323011398 1665.9062278717756 996.13169592246413 333.01392353326082 194.83706255629659 708.77840001136065 565.66675401106477 107.70449069142342 745.18242360278964 909.53545988723636 1254.1169577986002 1726.1115682497621 265.03525151312351 25.635577846318483 217.48686423152685
leaf_count=1082 3531 1717 4661 5308 10947 36505 1623 9717 18771 4555 4748 2705 4289 36368 11384 3945 1676 9345 7723 645 14715 12514 15899 15562 2976 278 2811
internal_value=0 0.00249699 -0.00375973 0.000759666 -0.000770526 -0.00582431 0.0022103 0.00621867 -0.0024953 -0.00173556 0.000175971 0.00544844 0.000411128 -0.00636522 0.00424806 0.00135777 0.00899566 0.00141067 0.00370308 0.00423362 -0.00502191 -0.000623971 -0.000102929 0.00355399 0.00811087 0.011824 0.00547915
internal_weight=0 10695.9 7166.91 7293.77 5497.78 4795.33 2013.16 3402.12 3484.61 3140.21 1951.06 1796 2371.58 4483.99 1558.34 2098.02 1415.95 1658.93 950.154 1986.17 2818.08 1094.15 1547.52 1833.82 562.207 297.172 550.501
internal_count=246000 123276 122724 94594 75534 92249 25084 28682 50450 45142 26371 19060 30475 87588 17343 26186 11393 21623 12278 17289 51220 14137 19430 16207 5959 2983 6756
is_linear=0
shrinkage=0.0152673


Tree=70
num_leaves=28
num_cat=0
split_feature=19 10 411 391 391 0 141 164 119 19 19 391 128 1 10 164 7 8 6 171 118 135 19 19 387 149 142
split_gain=467.665 360.235 265.683 213.849 275.371 278.327 124.658 92.4307 76.3825 73.0185 71.4662 70.22 68.0136 60.2539 57.9911 52.5555 51.5522 73.6202 62.4453 49.4437 48.4375 44.6609 40.9857 40.9578 40.3787 36.9328 35.782
threshold=1.0000000180025095e-35 -0.56647438538662265 1.0000000180025095e-35 0.12742144408804593 -0.80185022711144738 1.0000000180025095e-35 0.055555555555555559 33462.978750000002 -1.0000000180025095e-35 0.19388630579008007 -0.3376378893188533 -0.92257102786474277 0.23948275862068968 1.0000000180025095e-35 0.85599505562422762 36029.92500000001 -0.46140449088760332 1.0000000180025095e-35 0.034761904761904765 1.0000000180025095e-35 0.54352517985611526 0.72934386391251527 -0.35101553262171653 -0.25593239003289309 -0.094444699905398458 -0.072050230503013499 1.5312500000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 3 4 11 6 12 20 -1 15 -4 -3 14 23 16 -2 -6 18 -18 -9 -5 22 -8 -10 -12 -24 -25
right_child=9 2 10 7 5 -7 21 19 13 -11 24 -13 -14 -15 -16 -17 17 -19 -20 -21 -22 -23 25 26 -26 -27 -28
leaf_value=-0.006446477835314544 -0.0043574604081618789 0.00089235553245130988 0.009601149730378903 -0.0022109189813937702 0.0077253204940298656 -0.0017157324255981598 0.013687105309472255 0.013004133042392245 0.034342786884237989 -0.0081140772820325752 -0.00068743842477010132 -0.00780914372418342 0.0064968523526335482 0.0031006358408031233 0.0046938089612417319 0.0032798769563266062 0.014432549262195397 0.0078505159364324287 0.024651659132431624 0.0025328248154262295 0.0026972530147759007 0.012876746255174015 0.0058201524331259174 -0.0045819796145574639 -0.0047588449214233317 0.0012001326795151972 0.0034745010219945391
leaf_weight=1282.1883119903505 1670.5289136506617 500.97831616550684 113.53249227255583 1912.1347495131195 380.53862374648452 840.05737464129925 98.00821591168642 169.71420653164387 6.4418650455772868 1289.450023304671 1110.7841061837971 377.87299382314086 927.01225519180298 476.23184699937701 249.257572773844 238.67075127735734 709.16707370430231 316.06209688261151 178.58318880200386 283.47304845973849 619.286755990237 146.96995473280549 803.30163581296802 1013.1930275000632 1174.4192300215364 822.21831951290369 145.69148017093539
leaf_count=21843 27272 5914 1136 27440 4096 10658 872 1774 64 23005 14861 5403 10183 6530 2108 3406 7197 3782 1718 3476 7129 1604 9353 15229 17814 10125 2008
internal_value=0 0.00114095 0.0023362 0.00350116 0.00508541 0.00636013 0.00782704 0.000127357 -0.00365249 -0.00530221 -0.00219331 -0.00283947 0.00989202 -0.00146405 0.0116026 -0.00339767 0.012683 0.0142411 0.0165037 0.00647844 -0.00100645 0.00477375 0.00407606 -0.00333757 -0.00278407 0.00348933 -0.00356082
internal_weight=0 14657.1 11733.4 9334.64 6350.03 5471.18 4631.12 2984.61 2923.75 3198.65 2398.74 878.851 2760.62 1641.56 1833.61 1909.2 1584.35 1203.81 887.75 453.187 2531.42 1870.5 1723.53 1165.33 2285.2 1625.52 1158.88
internal_count=246000 192317 146643 112832 73013 61696 51038 39819 45674 53683 33811 11317 29084 23831 18901 30678 16793 12697 8915 5250 34569 21954 20350 17301 32675 19478 17237
is_linear=0
shrinkage=0.0152673


Tree=71
num_leaves=28
num_cat=0
split_feature=21 21 19 19 414 10 19 11 391 391 90 141 118 10 52 165 109 128 168 143 19 130 130 130 141 391 1
split_gain=609.792 281.27 208.872 127.459 121.266 133.075 109.809 95.9411 95.449 102.903 85.3808 78.9385 68.0693 59.8039 54.1059 48.7551 47.8346 47.6091 46.5366 38.9856 36.8973 36.6371 36.2421 35.8338 35.1353 34.2339 33.6445
threshold=1.0000000180025095e-35 -1.2291473454499886 0.023652303677922096 -0.31528071226839544 -1.0000000180025095e-35 -0.54216453783820895 0.042042249439647579 1.0000000180025095e-35 0.12742144408804593 -0.80185022711144738 -1.0000000180025095e-35 -0.27777777777777773 0.59028776978417274 0.78512566955088603 3.5000000000003335 6975.326250000001 1.5833333333333337 0.38593103448275862 1.0000000180025095e-35 1.2777777777777779 -0.099622888837908138 0.79166666666666685 3.2916666666666674 0.62500000000000011 -0.31481481481481471 -0.92629748585859206 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 12 3 13 19 -6 7 15 9 25 -11 -12 20 -3 16 -2 23 22 -10 -5 -1 -4 -13 24 -14 -7 -9
right_child=6 2 21 4 5 8 -8 26 18 10 11 17 14 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0079842222236878729 -0.0057410798450369888 0.013194161958808749 -0.0063602480954560439 -0.0034657142704775162 -0.0023512612146731338 0.0017632564798271818 -0.008851706339557305 -0.0024005865871361189 -0.00096994675469417094 0.0010695256137317243 0.011220558733931232 0.0060176924271917202 0.010746604256838639 0.0026497315686975493 0.002066353781195841 0.0011214916823532812 0.025413415149229557 -5.0174826017150449e-05 0.0082351217650237056 0.0029937054844433003 0.0024108186633136396 -0.00071079177071973099 0.019262690263099857 0.013655911560334589 0.0045709121135660818 -0.0069708598332668828 0.0020253282580923616
leaf_weight=356.06030289828777 2400.1292306669056 300.59649480879307 1048.7182717770338 1519.8839435838163 1257.6097933612764 226.10471633821726 1024.3770850896835 854.65749592334032 1257.1065290309489 647.75307985022664 791.08839704468846 826.19231196120381 400.57361655309796 219.46723615378141 281.33337066322565 265.78273306414485 43.175563834607601 318.2665361315012 142.31989747658372 252.53657173737884 1288.2529239095747 364.36009296029806 51.795808460563421 288.33154547959566 480.54161189496517 192.49911465123296 751.69550354778767
leaf_count=2864 46430 2820 17293 21122 17647 2564 21057 14485 15938 7701 7796 8873 3042 1995 2335 4716 333 3568 1525 3427 11884 5813 549 2174 3760 2471 11818
internal_value=0 0.00181955 0.000499193 0.00145556 0.000946145 0.00202977 -0.00435746 -0.00327735 0.00326913 0.0047822 0.00590013 0.00746974 0.00577806 0.00876474 0.00814189 -0.00505344 0.00954332 0.00498019 -2.62151e-05 -0.00253997 0.00362408 -0.00491033 0.0068137 0.00894532 0.00739071 -0.00223275 -0.000323776
internal_weight=0 12554.6 9416.3 8003.22 7483.16 5710.74 5296.64 4272.26 4453.13 3053.7 2635.1 1987.34 3138.27 520.064 1493.96 2665.91 1212.62 1196.25 1399.43 1772.42 1644.31 1413.08 877.988 1169.45 881.115 418.604 1606.35
internal_count=246000 147494 121102 97996 93181 68632 98506 77449 50985 33522 28487 20786 26392 4815 11644 51146 9309 12990 17463 24549 14748 23106 9422 8976 6802 5035 26303
is_linear=0
shrinkage=0.0152673


Tree=72
num_leaves=28
num_cat=0
split_feature=20 20 19 1 155 391 118 392 7 8 391 2 19 165 19 154 128 143 19 149 414 120 155 143 149 20 7
split_gain=691.155 248.776 154.702 135.118 130.933 105.835 99.5245 93.3012 81.5551 115.732 100.087 67.581 60.3349 59.0562 57.917 54.7233 46.1387 45.7426 43.9467 43.61 41.1944 38.0628 37.6932 35.8888 35.7516 35.3692 35.7544
threshold=-0.63287083336150685 0.33014794124083729 -0.33317285005261182 1.0000000180025095e-35 40370.388750000006 -0.81178185562575544 -0.07589928057553956 -0.088191213128057486 -0.21608509050195931 1.0000000180025095e-35 -0.72863400763517527 1.0000000180025095e-35 0.018489692726097188 160400.56500000006 -0.25931946189574345 5.2142857142857153 0.50808620689655182 2.3888888888888897 0.081652381945261435 -0.013124371921925478 -1.0000000180025095e-35 -0.41361974405850083 36011.441250000011 2.6111111111111112 -0.26860095034936238 -2.0097992159524432 -0.69652298314362115
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 -2 5 6 -1 24 13 -8 10 -10 19 20 -7 -3 -6 23 -11 22 -5 -9 -22 -16 -12 -4 -13 -27
right_child=1 14 4 11 15 7 8 12 9 17 16 25 -14 -15 18 -17 -18 -19 -20 -21 21 -23 -24 -25 -26 26 -28
leaf_value=-0.0061470947473150758 0.0094374934581533034 0.0029600021389702045 -0.0016255213718261365 0.012247201959991749 0.0066804375249285147 -0.00044757769618908094 -0.0030588730719221082 0.0020437183429411398 -0.0027726533020943599 -0.0018305226756643669 0.0098724051349608245 0.016450499584687667 -0.0021392222439890127 0.01262853362811981 -0.0056869147462786478 -0.0017237655075062358 0.0018363357516604452 0.0069582314816031927 -0.0093009301272064509 0.0064585690193289741 0.0019036021938059636 0.0088671597721495451 0 0.024914775791996798 -0.0055650129989168878 -0.0042738189173839218 0.0046435666215275308
leaf_weight=314.55766080319881 336.14481951668859 177.51857318356633 800.11729256808758 637.53734276071191 648.19946983084083 1443.9476370513439 1710.6512527503073 405.70625260099769 236.60835095867515 1588.8906873762608 443.16493345052004 53.496744111180305 220.55639342218637 85.026387460529804 2427.8035174831748 248.05155747383833 168.38079119101167 150.66644389927387 725.49881128594279 599.46406272426248 225.3704029545188 1063.1957838274539 305.81787345558405 41.344321437180042 1681.5813484191895 115.99137135222554 989.6683088503778
leaf_count=3818 3307 2365 13182 5378 7736 17374 23909 3914 3374 23243 5249 341 2674 828 44937 3490 2105 2063 14848 5416 2530 9126 4921 473 28850 1155 9394
internal_value=0 -0.00219327 -0.000695337 0.00412778 -0.00113809 0.00231766 -0.00185987 0.00309381 -0.000462897 0.00122285 0.00570338 0.00696268 0.00533943 0.000275152 -0.00550789 0.00434436 0.00878904 -0.00106333 -0.00594524 0.00945087 0.00631853 0.00765682 -0.00505068 0.0111847 -0.00429882 0.00429831 0.00369918
internal_weight=0 11690.4 8053.8 6154.52 7717.66 3758.36 6821.41 3443.8 4339.71 2629.06 889.498 2396.16 1914.83 1528.97 3636.64 896.251 652.89 1739.56 3459.12 1237 1694.27 1288.57 2733.62 484.509 2481.7 1159.16 1105.66
internal_count=246000 184052 116981 61948 113674 40264 102448 36446 60416 36507 11201 21684 18244 18202 67071 11226 7827 25306 64706 10794 15570 11656 49858 5722 42032 10890 10549
is_linear=0
shrinkage=0.0152673


Tree=73
num_leaves=28
num_cat=0
split_feature=20 21 21 109 20 19 119 20 19 19 52 10 1 21 135 21 155 387 21 164 387 7 8 391 7 90 119
split_gain=670.772 271.065 252.143 208.428 114.066 80.9643 73.7489 66.4177 64.3464 61.799 61.149 60.4851 56.2602 56.2403 51.6615 51.1954 47.558 44.9373 43.454 40.8312 40.7089 39.5427 36.371 57.012 59.3585 35.6543 35.1106
threshold=1.0000000180025095e-35 -0.70835755058453587 -0.45447813724047786 -0.58333333333333315 -1.161217900876085 -0.22703662689892457 0.51281287246722307 -1.6973680938911146 0.14515642090416706 0.089247058428345918 3.5000000000003335 -0.2233896442796319 1.0000000180025095e-35 0.38034479682904804 0.6783110571081411 -1.8457901202353957 35028.247500000005 -0.056328829545551164 -1.5586313096075675 333306.65250000003 0.84250630998422127 -0.55072463768115931 1.0000000180025095e-35 -0.81178185562575544 0.02326304658829384 -1.0000000180025095e-35 0.72377830750893934
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 8 7 12 -4 18 -3 15 11 25 19 -5 14 -7 -2 26 -9 -1 -6 21 -13 23 -23 -25 -8 -17
right_child=2 3 5 4 9 13 10 17 -10 -11 -12 20 -14 -15 -16 16 -18 -19 -20 -21 -22 22 -24 24 -26 -27 -28
leaf_value=0.0069897301549132033 0.0072520454644798456 0.012693903000926951 0.0017867477295787761 0.00037894739926244556 -0.0045552596593361038 -0.0057587567936663361 0.0053466318628299751 0.0066249467289737404 -0.006616460964984478 -0.0072964181647278267 0.0016970120602550292 -0.0031595457224964014 0.0062342399262040413 -0.0084742156369146896 6.5431162109754769e-05 -0.0021964747653243329 0.0062391105613534888 0.0014395056861541545 0.0023042703198372719 0.026045577634958614 -0.0038768845152691647 -0.004724708534214507 -5.8146533731723052e-05 0.0033461401908000993 0.014077146850998023 0.011564702593597148 0.0028336040959084769
leaf_weight=734.40076043456793 291.36193161457777 241.30591490119696 313.59436535090208 992.28067852184176 1145.8826808407903 2374.0244711339474 292.38192616030574 792.92468117177486 268.71214412152767 481.60519937053323 251.34276510030031 389.92206945642829 626.00818695127964 1634.6528466790915 413.74985779449344 1077.6418094970286 271.86316683888435 776.5956461392343 1265.9140504747629 9.9732940308749658 487.22429159283638 115.94092573225498 699.33709578588605 355.25952031090856 184.05836158245802 890.18137107416987 460.93405089899898
leaf_count=5147 2556 1717 4661 11498 18665 43954 2432 7969 4289 8595 2105 5320 5792 36368 7266 14673 3099 9374 12142 124 7472 1608 9809 4495 2156 6856 5858
internal_value=0 0.00239584 -0.00365129 0.000729985 -0.0007507 -0.00568592 0.00593316 0.00522167 0.000409929 -0.00217552 0.00858131 -0.0014444 0.00265012 -0.00621793 -0.00489113 0.00131314 0.000351617 0.00406555 0.00402961 -0.00427884 1.97426e-05 0.0011136 0.00235067 0.00493474 0.00702926 0.0100362 -0.000683414
internal_weight=0 10732.5 7106.53 7298.32 5487.49 4736.02 3434.22 1810.83 2370.51 3869.2 1433.91 3387.6 1618.29 4422.43 2787.77 2101.8 1810.44 1569.52 2000.31 1155.86 2231.74 1744.52 1354.6 655.259 539.318 1182.56 1538.58
internal_count=246000 123276 122724 94594 75534 92249 28682 19060 30475 58244 11393 49649 17290 87588 51220 26186 23630 17343 17289 18789 30860 23388 18068 8259 6651 9288 20531
is_linear=0
shrinkage=0.0152673


Tree=74
num_leaves=28
num_cat=0
split_feature=20 21 21 1 19 20 391 109 19 135 2 130 10 19 11 149 130 409 11 155 390 10 141 416 130 19 157
split_gain=652.547 355.535 188.397 120.76 104.659 99.7857 91.7868 88.1859 79.4402 76.8704 73.4015 62.5544 57.7876 49.8336 49.7596 47.1354 46.1722 44.8937 40.5297 40.1418 37.5126 37.0001 50.543 50.7817 36.449 39.5776 35.9204
threshold=-0.28709838983579977 -0.4706364644200467 0.38034479682904804 1.0000000180025095e-35 -0.23999248241935275 0.45114359061287296 -0.82711714898909583 -0.58333333333333315 0.039544982278674708 0.71051032806804393 1.0000000180025095e-35 0.87500000000000011 -0.32941903584672433 0.068777473923543955 0.34185918591859193 -0.21757018075529433 0.95833333333333337 -1.0000000180025095e-35 1.0000000180025095e-35 18957.757500000003 -0.5986112817049366 0.77853316852080767 0.16666666666666669 -1.0000000180025095e-35 1.0000000180025095e-35 -0.25593239003289309 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 8 3 4 -1 7 -6 -3 11 12 21 14 -8 19 -2 -14 -12 -13 -4 20 -9 22 23 -5 -22 -26 -11
right_child=1 5 18 10 6 -7 9 13 -10 26 16 17 15 -15 -16 -17 -18 -19 -20 -21 24 -23 -24 -25 25 -27 -28
leaf_value=0.010120114268080342 -0.00066559084449594884 0.00023773070166537561 -0.0040700800401093206 0.01757970448166012 -0.0064942845212082661 -0.008089707658658931 -0.0018197055886259969 -0.007795905825271664 -0.0038348303304672096 0.0058790982521268499 0.0026521633602006262 0.0024556576170922692 0.0056303652523150239 -0.0086670952532813816 0.0043683419776878703 0.00089200010755792188 0.0098595060991411715 0.010451433599035356 0.0013094161598437466 0.001125521407010076 -0.0047264074094243826 0.0044348845094556149 0.0056359407228994754 0.0093013627610479075 0.016267028832264652 -0.0010915608993786114 0.016896625558255565
leaf_weight=383.27534185349941 1279.2240120358765 1023.788185428828 861.84178408235312 301.55759094282985 290.3577762581408 1649.7127992659807 900.16240018233657 650.12493685260415 560.36436817422509 530.57716799154878 1072.8432420864701 324.49471194669604 827.42148899286985 650.80214785784483 710.49830508977175 1211.3009589314461 258.85676252841949 338.13110437244177 521.96159769594669 317.15707439556718 1506.8914665654302 315.02061283588409 351.18870402127504 425.59284935519099 32.617723010480404 455.19647440686822 80.663995958864689
leaf_count=3149 15641 15043 14304 2482 3370 34955 10894 12440 8386 5030 9941 3876 7941 13515 7731 12376 2328 3695 7250 5167 27517 2437 3277 3730 469 8425 631
internal_value=0 -0.0027485 0.00310517 0.00413004 0.00250975 -0.00486033 0.00174737 -0.00370902 0.0013809 0.00242435 0.00663771 0.00248649 0.0013957 -0.00482994 0.0011276 0.00281994 0.00406128 0.00655156 -0.00203445 -0.00398322 -0.00459934 0.00909263 0.0104437 0.012751 -0.00355224 5.65424e-05 0.00735309
internal_weight=0 9499 8332.62 6948.82 4223.76 6286.29 3840.48 4636.58 3212.71 3550.13 2725.06 2652.35 2938.88 3612.79 1989.72 2038.72 1331.7 662.626 1383.8 2961.99 2644.83 1393.36 1078.34 727.15 1994.71 487.814 611.241
internal_count=246000 156860 89140 67586 43391 117531 40242 82576 39329 36872 24195 30943 31211 67533 23372 20317 12269 7571 21554 54018 48851 11926 9489 6212 36411 8894 5661
is_linear=0
shrinkage=0.0152673


Tree=75
num_leaves=28
num_cat=0
split_feature=20 20 11 1 10 130 391 2 11 391 0 391 164 20 135 47 149 149 119 119 109 119 111 389 13 389 124
split_gain=636.193 234.919 140.999 123.188 108.451 103.458 67.3313 61.6484 59.5527 58.6287 96.8913 87.6839 56.4269 51.591 49.8868 43.4392 42.4715 40.9419 38.6881 35.6088 36.0037 35.1507 38.5592 33.6011 32.8444 39.1769 32.7823
threshold=-0.63287083336150685 0.33014794124083729 0.093784378437843804 1.0000000180025095e-35 -0.32941903584672433 0.87500000000000011 -0.81178185562575544 1.0000000180025095e-35 1.0000000180025095e-35 0.12650512597654215 1.0000000180025095e-35 -0.66458914984868689 38432.463750000003 -1.8421595884852648 0.83748481166464173 0.0003499999999999962 -0.10758206668188493 -0.013124371921925478 -0.074791418355184727 -0.11889153754469606 0.58333333333333337 0.72377830750893934 22625.190000000006 1.6064207626278313 -0.30931833608067483 0.28314687917001718 3.1250000000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 2 5 4 14 12 -6 17 -3 10 11 -4 18 -8 -1 21 24 -5 -2 26 -21 -13 -23 -9 -15 -26 -7
right_child=1 8 9 7 6 19 13 23 -10 -11 -12 15 -14 16 -16 -17 -18 -19 -20 20 -22 22 -24 -25 25 -27 -28
leaf_value=-0.0028691125129036814 -0.0064871662006561219 -0.0069548025637897037 -0.0019939312420742409 0.011664655335771596 -0.0045915900809994151 -0.0033740396679126069 0.010424683755698121 0.0049710088605543325 -0.002917755644721483 -0.0012341928454494165 -0.0038398077037129024 0.0058847569112732692 0.0017413435877155811 0.0013344516987676871 0.0060370945943650422 0.001158923957688815 0.0016439362494070858 0.0060963024930019124 -0.0029821850297285474 0.0015578770635176846 0.009330864613366319 0.011243087229136016 0.058781682127178193 -0.0034689490640401445 0.010024104747461239 0.0024038108308481942 0.014328041253711059
leaf_weight=1023.7076818533242 1271.9237203113735 2174.7866465598345 393.05908129364252 648.22896856442094 196.53427889570594 368.63885747641325 317.58539465814829 1047.0039724335074 1417.0580979734659 1101.8206219896674 396.10961446538568 917.5886278450489 384.44141414016485 261.08745734393597 170.40003295987844 335.36249144375324 1058.2633317559958 607.12427838519216 1774.6795789375901 578.08862963691354 184.48790997639298 299.76016910746694 3.9425639845430842 121.39560819417238 514.62412044405937 231.6911449059844 25.766974028199911
leaf_count=13224 22691 42891 5283 5378 2169 6350 2281 9736 24180 15401 5359 11176 5159 2736 1849 4142 10984 5416 26968 8444 2426 3148 45 1154 4807 2214 389
internal_value=0 -0.00211879 -0.000666585 0.00393754 0.00220874 -0.00242046 0.00397047 0.00662519 -0.0053649 0.00166477 0.00303028 0.00443098 -0.00375249 0.00468071 -0.00158972 0.00605922 0.00379225 0.00898034 -0.00444881 0.00152175 0.00345234 0.00739692 0.0119286 0.00408582 0.00603916 0.00767196 -0.00218765
internal_weight=0 11627.5 8035.67 6197.65 3773.89 4588.03 2579.79 2423.75 3591.84 3447.64 2345.82 1949.71 3431.04 2383.25 1194.11 1556.65 2065.67 1255.35 3046.6 1156.98 762.577 1221.29 303.703 1168.4 1007.4 746.315 394.406
internal_count=246000 184052 116981 61948 40264 72427 25191 21684 67071 44554 29153 23794 54818 23022 15073 18511 20741 10794 49659 17609 10870 14369 3193 10890 9757 7021 6739
is_linear=0
shrinkage=0.0152673


Tree=76
num_leaves=28
num_cat=0
split_feature=20 21 21 20 1 2 19 19 119 155 19 390 149 21 135 130 24 90 390 21 11 390 149 135 13 411 147
split_gain=618.79 254.168 239.859 160.509 108.847 86.5048 78.795 72.1222 69.2076 61.6335 61.3531 59.2718 57.9426 55.3456 50.5621 49.5413 48.3289 44.1125 42.692 42.052 40.5646 38.1451 46.2449 37.8492 36.8537 36.5008 34.1121
threshold=1.0000000180025095e-35 -0.70835755058453587 -0.45447813724047786 -1.523630872707755 1.0000000180025095e-35 1.0000000180025095e-35 -0.22703662689892457 -0.18975535038981672 0.57479141835518488 162010.71000000005 0.14515642090416706 0.10148339268756748 -0.21757018075529433 0.38034479682904804 0.6783110571081411 0.62500000000000011 3.5000000000003335 -1.0000000180025095e-35 -0.014720089120354104 -1.5586313096075675 -1.0085258525852583 -0.48423963718801671 -0.52480564017390718 0.89216281895504268 1.100940560457675 1.0000000180025095e-35 0.28378378378378383
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 10 18 7 17 -4 -5 19 11 15 24 -13 14 25 21 -10 -6 23 -1 -19 -2 -23 -3 -9 -8 -22
right_child=2 3 6 4 5 -7 13 9 16 -11 -12 12 -14 -15 -16 -17 -18 20 -20 -21 26 22 -24 -25 -26 -27 -28
leaf_value=0.0067802752343523662 -0.0039700900108267786 0.00036864854018800334 0.0018422884240691436 0.0047530515234616415 0.00026182891179416467 -0.00054889285524923671 -0.0044569209166985604 -0.0055122836580190782 0.0097513072882889941 0.0066858880345484805 -0.0064837767010874217 0.0028074884265774447 -0.0031838654618496273 -0.0083286173287454961 0.00016869971894262781 0.0052060987107617309 0.0020009261478716131 -0.0016891841156049018 0.0081435860317972345 0.0023179122270015266 0.010739932500756274 0.0076242882677976789 -0.00015493239201587336 0.012678780864697729 0.0042771637645817916 -0.0087989698755208713 0.0034673336368401773
leaf_weight=787.8377163335681 429.7020160369575 399.80166547000408 312.68395991250873 343.83460514619946 294.5429591499269 1196.4125906825066 1722.2451398819685 1632.2030448205769 1105.7125994935632 159.27690321207047 265.52685384452343 609.32568794861436 979.83306616172194 1606.6406056508422 411.27399108931422 556.3811264000833 229.71087111532688 103.09907265380025 720.44436150044203 1338.6415093764663 490.75220019742846 221.52096834778786 895.03479427844286 68.303954280912876 93.638476174324751 621.94483385980129 223.20686081051826
leaf_count=5463 5601 3903 4661 3941 3769 15587 31206 25574 8576 1971 4289 8392 14268 36368 7266 6756 1911 1389 6020 12732 5300 2619 11210 564 1328 12748 2588
internal_value=0 0.00228699 -0.00353214 0.000672496 -0.00032231 0.00229324 -0.00553754 -0.00190582 0.00569539 -0.0025677 0.000422822 -0.00301544 -0.000880793 -0.00606871 -0.00474718 0.0012999 0.00842549 0.00536001 0.0058069 0.00397596 0.00718614 -0.00010022 0.00138133 0.0021891 -0.0049754 -0.00561348 0.00848072
internal_weight=0 10776.6 7042.95 7314.68 6126.13 2308.01 4674.79 3818.11 3461.9 3474.28 2368.17 3315 1589.16 4362.1 2755.46 2102.64 1335.42 1111.6 1188.55 2126.48 817.058 1546.26 1116.56 468.106 1725.84 2344.19 713.959
internal_count=246000 123276 122724 94594 84107 28633 92249 55474 28682 51533 30475 49562 22660 87588 51220 26186 10487 13046 10487 18195 9277 19430 13829 4467 26902 43954 7888
is_linear=0
shrinkage=0.0152673


Tree=77
num_leaves=28
num_cat=0
split_feature=20 21 21 20 391 19 90 391 130 411 1 391 391 11 2 391 392 19 19 141 391 391 157 126 24 19 110
split_gain=601.652 377.25 131.434 129.62 87.5752 83.2556 83.168 101.363 82.215 79.223 65.9837 61.8867 67.1624 60.6936 54.343 51.4326 79.4769 47.4796 44.7797 44.1539 43.9836 43.5971 42.7127 42.5297 42.0957 40.1659 39.8672
threshold=-0.63287083336150685 -0.55092222074356589 0.38034479682904804 0.29935720544807254 -0.80185022711144738 -0.37481395413786084 -1.0000000180025095e-35 0.12742144408804593 0.62500000000000011 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 0.049180694651566131 0.093784378437843804 1.0000000180025095e-35 -0.80185022711144738 0.28975724929073066 0.18796971717912833 -0.20825903592772327 -0.27777777777777773 -0.92629748585859206 0.10767533198381948 11137.500000000002 -0.59905132224506819 2.5000000000002225 0.0052888466891881101 -3590.9999999999995
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 8 4 5 20 -3 23 11 13 10 15 19 -13 18 -12 -7 -17 -10 -2 26 -1 -14 -9 -6 25 -15 -8
right_child=1 3 -4 -5 6 9 7 22 17 -11 14 12 21 24 -16 16 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0031107221528143447 0.0064229835644869452 0.012698200410037499 -0.0012697300398282821 -0.0066492392055229263 0.009596882626847162 -0.0097695671935462813 -0.0010843944163250784 0.0026213130897271247 0.0065935670510543559 -0.0065195082504044205 0.0041051947695354531 0.018725163031002329 0.0031650774586405852 0.0055688852232982722 -0.0018733314168269059 -0.0041311293255837092 0.00266010602765329 -0.0054649267647479171 -0.0025752412729116935 0.0050248313794084669 -0.0062662227975944151 0.014453527375885874 0.019519126833948273 0.00083518822610176779 -0.0020438866128737075 -0.0030211937976682667 0.011316758593637457
leaf_weight=233.86740608513355 142.6395100466907 81.921722553670406 993.0179448723793 2760.7511168569326 147.52213440090418 256.48768410459161 65.626503571867943 1238.1024077758193 930.84145026654005 1045.481154538691 646.75669761374593 254.42749573662877 183.09025771543384 885.26061839237809 781.39625245332718 1708.2175532281399 523.25962126627564 81.899650413542986 1283.8078352287412 1038.3687817677855 230.88374368101358 145.02583142369986 35.895718708634377 1056.2496686391532 311.72442734614015 146.50169924646616 603.54657697305083
leaf_count=2061 1443 883 14616 57408 1369 4565 532 12049 10158 18862 9349 1867 1572 8925 12153 29804 7495 1200 16344 8908 2532 1084 289 10420 3485 1978 4649
internal_value=0 -0.00206962 0.00381496 -0.00398787 0.00478167 -0.00252905 0.00539873 0.00657163 0.0018856 -0.00278281 -0.00178261 0.00849426 0.0128108 0.000520834 0.0008279 -0.00328474 -0.00253445 0.00560848 -0.00166826 0.00701494 -0.00152864 0.00818819 0.0031076 0.00191796 0.00285182 0.00433994 0.0100869
internal_weight=0 11586.9 6225.62 7804.27 5232.61 5043.52 4767.86 3564.08 3782.68 4961.6 3916.12 2290.09 582.544 2769.93 1428.15 2487.96 2231.48 1012.74 1426.45 1707.54 464.751 328.116 1274 1203.77 1343.49 1031.76 669.173
internal_count=246000 184052 61948 140519 47332 83111 42739 30950 43533 82228 63366 18612 4523 32175 21502 41864 37299 11358 17787 14089 4593 2656 12338 11789 14388 10903 5181
is_linear=0
shrinkage=0.0152673


Tree=78
num_leaves=28
num_cat=0
split_feature=20 21 109 21 19 10 20 143 20 19 21 14 19 141 387 19 10 1 20 8 143 389 124 125 155 389 7
split_gain=586.657 278.855 211.501 190.598 124.688 102.364 87.2678 66.5129 63.4665 59.2456 56.2459 55.6482 55.08 51.345 48.0893 47.8093 49.2682 47.7454 44.4894 44.3197 42.4348 40.4945 40.2928 40.615 39.0502 37.7762 36.8388
threshold=0.12356881070161159 -0.70835755058453587 -0.58333333333333315 -0.45447813724047786 0.044598349626972018 -0.54216453783820895 -1.417518363968721 1.7222222222222225 -1.6973680938911146 -0.20825903592772327 -2.0621762643796608 -1.0000000180025095e-35 -0.31528071226839544 -0.16666666666666663 0.84250630998422127 0.015927314024199116 -0.54216453783820895 1.0000000180025095e-35 -1.0967390244420938 0.51063775510204101 2.5000000000000004 0.65006229665501025 0.37500000000000006 -0.22103448124349154 162010.71000000005 0.028776983416879412 -0.46687814890837837
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 8 15 5 -4 26 10 -3 -5 -1 -8 -12 22 17 16 -2 24 -14 21 -11 -18 23 25 -13 -10 -7
right_child=3 2 4 9 -6 6 11 -9 13 20 12 14 18 -15 -16 -17 19 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.010878456108980377 -0.0045980706420033291 0.011878599299760807 -0.0041626645859960164 0.00074437771992547877 -0.0064686404659811576 0 -0.0048306533222599807 0.010394799444144728 0.013235202254482376 -0.0070138654259820216 0.010522839979101731 -0.00078586960312905117 0.0059760089172597331 0.00097707866679936218 -0.0030945368239144325 -0.0048199774976257935 0.0064971928835803354 0.0043907512530600356 0.0018591800763724481 -0.0024687774199501572 -0.00096273447539419626 -0.00016239372335294643 0.016242622124101415 0.0020847330674158395 0.010685076021343599 0.0027875911237586538 0.0075230249811443434
leaf_weight=294.82948566228151 282.68979006260633 246.6722519248724 1187.8949613682926 280.77886489033699 863.610271461308 205.77689268812537 502.34104868769646 518.05065341666341 205.57112185657024 3267.4313273690641 265.98945627361536 1239.4326533600688 921.8095278814435 883.88703653216362 615.07708201184869 394.71842861548066 599.68130135163665 919.72019513696432 1851.089114960283 315.23349580168724 298.42373061180115 325.73798523470759 84.828691571950912 452.66420150920749 73.041083354502916 137.07532667741179 571.7651697434485
leaf_count=1887 3900 1717 19028 4403 15018 1924 7317 4184 2096 67876 1882 17593 6474 10460 9600 6248 7021 11604 18251 4168 6038 3943 858 5109 882 1443 5076
internal_value=0 0.0019046 0.000309982 -0.00401792 -0.00108849 -0.000212367 0.000922552 0.00529239 0.00461157 -0.00597818 0.00449616 -0.000144504 0.00387327 0.00358896 0.000679333 -8.16817e-05 0.00114053 0.0017235 0.0032314 0.00245602 -0.0065101 0.00414366 0.00620075 0.00511434 -0.000138986 0.00908643 0.00553001
internal_weight=0 12041.1 8189.36 5764.69 6178.66 5315.05 4127.15 3851.77 2010.7 3846.63 3333.72 3349.61 3038.89 1764.03 2847.27 1918.06 1523.34 2232.19 2772.9 1240.65 3565.86 925.419 880.139 795.311 1312.47 342.646 777.542
internal_count=246000 142403 109725 103597 88042 73024 53996 32678 21683 78317 28494 46996 26607 19966 39679 25280 19032 30079 24725 15132 73914 10964 9506 8648 18475 3539 7000
is_linear=0
shrinkage=0.0152673


Tree=79
num_leaves=28
num_cat=0
split_feature=19 11 90 19 391 391 391 391 165 118 130 47 390 69 391 391 387 19 16 157 130 147 141 2 111 389 414
split_gain=403.596 312.292 150.366 147.509 135.313 196.58 134.253 140.33 95.8963 79.4675 61.1867 54.653 49.9986 49.1591 44.3957 45.837 44.363 43.3204 42.3418 41.2086 40.8266 39.2875 38.1258 39.1794 35.8631 33.9225 33.914
threshold=0.066137329671330417 1.0000000180025095e-35 -1.0000000180025095e-35 -0.24312884957925313 0.12742144408804593 -0.66068996828538784 -0.80185022711144738 -0.63378138164839226 5045.8050000000012 -0.12050359712230214 2.0416666666666674 1.0000000180025095e-35 -0.53258004075641796 1.0000000180025095e-35 0.12742144408804593 0.032076008662947908 0.31408071976838031 0.19388630579008007 1.0000000180025095e-35 11137.500000000002 0.95833333333333337 0.98648648648648662 0.055555555555555559 1.0000000180025095e-35 1440.1575000000003 -0.57300939015262586 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 13 16 5 -4 -5 -8 9 -9 12 18 -11 26 15 24 -1 20 22 -6 -2 -10 23 -7 -14 -18 -3
right_child=17 2 4 6 19 11 7 8 21 10 -12 -13 14 -15 -16 -17 25 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.016819176025389366 -0.0052765698172091884 -0.0044412690456670668 -0.0011073608172262094 -0.0078958522632651164 0.00049504242589158351 0.010910898768831679 0.0087581505051109645 -0.0046817217053444857 0.0074185665163665109 -0.0046405810671776328 0.0054869125490976285 0.0034593012548658785 -0.00078192638043007628 0.0076008675407305297 -0.0024990961546439991 0.0076456759811236296 0.016797156744856025 -0.0077879501539854451 0.01232524631210645 0.014796550386178248 0.0013301269577905967 0.00063612440114752629 0.0046904402858567807 0.0050467463185862793 0.010788113317615495 0.0030796908908571068 0.00012713707220551575
leaf_weight=85.431332226842642 906.17645077034831 583.0303994230926 744.44696008041501 750.48978206887841 1760.9809893295169 884.33892916142941 321.11722306907177 2077.8502616025507 316.87430665269494 867.723827265203 318.08828464150429 607.28929518535733 761.33281079679728 151.35298473387957 1070.0409091413021 248.06228284165263 47.812883570790291 1243.6673832908273 558.95214885473251 48.132688630372286 284.29950068518519 544.13335880637169 718.98680686578155 390.30780101940036 67.797528918832541 369.81626227498055 1069.8918966911733
leaf_count=907 15584 7842 8788 12510 22465 8685 4008 35778 3694 13076 4230 6721 10588 1709 16165 3019 526 23005 4834 511 4558 7358 8045 4009 786 4144 12455
internal_value=0 0.000902288 0.00312633 -0.0012274 0.0043399 0.00593959 -0.00177633 -0.00107813 -0.00158347 -0.00233751 -0.00087317 0.00760268 -0.00154754 -0.000711553 -0.000293019 0.00188997 0.00676506 -0.00578855 0.0085845 0.0008822 -0.00369116 0.00314403 0.00752998 0.0091235 0.000155477 0.00467937 -0.00147906
internal_weight=0 15364.3 7517.71 7846.57 5713.44 3904.32 7343.51 6593.02 6271.9 5410.9 3333.05 3159.87 3014.96 1804.28 2147.23 1077.19 503.06 2434.14 2552.59 1809.11 1190.48 861.008 1993.63 1274.65 829.13 417.629 1652.92
internal_count=246000 202853 86064 116789 64058 41082 111212 98702 94694 83642 47864 32294 43634 22006 30558 14393 5577 43147 25573 22976 20142 11052 20739 12694 11374 4670 20297
is_linear=0
shrinkage=0.0152673


Tree=80
num_leaves=28
num_cat=0
split_feature=21 21 19 10 414 19 10 141 411 391 7 165 411 70 155 387 130 7 391 391 17 391 140 17 130 11 90
split_gain=512.102 235.207 177.373 111.509 125.872 101.738 97.016 85.6316 71.6634 70.436 74.3951 62.063 61.962 54.0776 62.2272 44.4707 43.3299 42.9821 48.2797 42.7279 42.0903 38.2738 37.6311 37.0071 35.7047 33.6935 32.5097
threshold=1.0000000180025095e-35 -1.2291473454499886 1.0000000180025095e-35 -0.55809641532756482 -1.0000000180025095e-35 1.0000000180025095e-35 -0.23176761433868973 0.055555555555555559 1.0000000180025095e-35 0.12742144408804593 -0.43328979287180441 159038.95500000005 1.0000000180025095e-35 -0.55250965250965234 33998.602500000008 -0.037632662431008129 0.95833333333333337 -0.69652298314362115 0.30652385897453438 -0.81178185562575544 1.0000000180025095e-35 -0.80185022711144738 0.43811881188118817 -1.0000000180025095e-35 0.79166666666666685 0.35726072607260734 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 12 3 -3 20 6 -2 9 13 10 -6 16 15 -8 17 23 -9 -15 19 -19 26 -12 -17 -1 -4 -21 -5
right_child=5 2 24 4 7 -7 8 11 -10 -11 21 -13 -14 14 -16 22 -18 18 -20 25 -22 -23 -24 -25 -26 -27 -28
leaf_value=0 -0.0057348062459220911 -0.0024682088012086124 -0.0057486192718794122 -0.0061801008551853045 0.0026922890598069238 -0.008151241296722532 -0.003484097143739298 -0.0011877923374282856 -0.00577867254876549 0.0010616351216539363 0.0018755710285889662 0.010005500575819023 0.0013778475516754789 -0.0061759230902728003 0.012469666405845721 0.0057918233335935319 0.0041042066198944968 -0.0043891751806653676 -0.0024822007858286066 0.0034197687775968421 0.0038879580196362071 0.0096683844769232564 -0.00055300717769601209 0.0092823787825356118 -0.00034428515959581562 0.011212302989421009 -0.001008933467973391
leaf_weight=108.99917954578996 1685.6370690502226 1456.2054447606206 1120.5302064493299 416.90318271145225 755.49069342389703 1113.5613398961723 549.54041538760066 1361.3279215916991 548.31972401589155 740.26908925175667 171.2355384491384 164.10534266382456 752.36260684207082 160.95731643587351 125.02939155325294 930.97556862607598 490.12763473764062 101.15816139057279 325.04790692031384 353.12750427052379 276.61911689862609 1185.1890112608671 281.0622176900506 1121.9982015676796 387.07057359814644 208.93506494536996 902.05545413121581
leaf_count=961 33576 20998 18784 5984 7953 23664 10076 16292 10456 8834 1946 1672 6960 2703 1833 7800 5778 1702 5630 5854 3117 11477 2403 8268 6213 3012 12054
internal_value=0 0.00164507 0.000430625 0.00134524 0.00220589 -0.00405912 -0.00293352 0.00342625 -0.000938736 0.0051292 0.0065504 0.0010116 0.00522485 0.000511832 0.0022426 0.00640562 0.00020848 0.00112 0.00231855 0.00468527 -0.00151136 0.00869179 0.0043131 0.00845744 -0.00436738 0.00633573 -0.0026511
internal_weight=0 12622.5 9427.13 7919.53 6463.32 5171.31 4057.75 4867.75 2372.12 2852.18 2111.92 2015.56 3195.4 1823.8 1274.26 2443.04 1851.46 1149.23 988.269 663.221 1595.58 1356.42 1212.04 1231 1507.6 562.063 1318.96
internal_count=246000 147494 121102 96105 75107 98506 74842 53952 41266 30210 21376 23742 26392 30810 20734 19432 22070 18901 16198 10568 21155 13423 10203 9229 24997 8866 18038
is_linear=0
shrinkage=0.0152673


Tree=81
num_leaves=28
num_cat=0
split_feature=20 20 155 1 10 2 119 154 409 411 143 149 130 391 7 8 391 90 147 6 135 141 161 149 90 135 167
split_gain=560.033 227.184 133.739 112.73 106.558 86.1739 85.7909 74.7936 73.3125 72.6301 72.1581 67.9659 58.4009 51.1944 48.2492 57.6975 44.1908 66.1423 43.0024 41.9032 39.8694 39.8554 46.1913 43.9381 38.4629 36.1205 34.6362
threshold=0.12356881070161159 -1.126355914706455 33998.602500000008 1.0000000180025095e-35 -0.16446916632330721 1.0000000180025095e-35 -0.049165673420738971 4.5000000000000009 -1.0000000180025095e-35 1.0000000180025095e-35 2.5000000000000004 -1.0000000180025095e-35 2.4583333333333335 -0.81178185562575544 -0.44772034583566583 1.0000000180025095e-35 0.12742144408804593 -1.0000000180025095e-35 -0.067567567567567557 -0.14897243107769423 0.48754556500607543 -0.16666666666666663 7374.2175000000007 -0.21135171585026369 -1.0000000180025095e-35 0.86482381530984209 0.75000000000000011
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 3 4 12 18 -2 20 21 13 11 26 -3 -6 25 19 17 -15 24 -16 -4 23 -23 -1 -5 -10 -8
right_child=6 2 7 5 9 -7 10 -9 14 -11 -12 -13 -14 16 15 -17 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.010205842572838882 -0.0062820014786312845 -0.0055524701051238873 0.0041672533429821332 0.0020814837336302731 -0.0063335875254617374 -0.00027194709035644046 -0.0011978436579607437 -0.0008981044337811649 0.0017549425286791231 -0.0040927376907934285 0.0043702398635925123 -0.0052416536595967745 0.0030720435285288812 -0.0020293821575852532 0.0079585749740771084 0.0051469327212678734 -0.00095241507431470063 0.0059683934570719903 0.0018457892906202137 0.015027119864334379 0.011352410101052028 -0.00078103789510449557 0.013443878720460292 0.0020313505513791328 0.009854596289292087 0.012572228110499887 0.01162654308280836
leaf_weight=254.0617735311389 2233.9742583148181 1618.3625241406262 328.02257820591331 214.17127331346273 173.30182577669621 1507.2454924508929 1427.071348644793 292.29144666716456 539.45104926079512 698.24665628001094 326.97850420698524 1691.1615178734064 204.77909107878804 320.00050831586123 451.6991580016911 729.21579377353191 638.11932139098644 957.06076139211655 540.15741788223386 358.73813065141439 414.28115774691105 773.91464091092348 56.916382726281881 395.4181117862463 509.01902924105525 83.515577275305986 50.547750074416399
leaf_count=2214 44173 25942 3690 2660 2385 19240 23698 3701 4677 9987 5332 29718 2887 3973 3503 6450 8737 10766 6662 2602 4039 7997 476 3711 5491 613 676
internal_value=0 0.00185467 0.000474601 -0.000244884 -0.00170877 0.00218745 -0.00394252 0.00561508 0.00503987 0.000165582 -0.00244458 -0.00315091 -0.00457849 0.00159392 0.00683401 0.00828836 0.00231663 0.00395717 0.00512847 0.0111017 0.00819162 0.00241201 0.000185423 0.00524528 0.00756648 0.00322339 -0.000751423
internal_weight=0 12058 8415.06 7380.46 4609.87 2770.59 5729.73 1034.6 3642.93 2786.73 3495.76 3168.78 1823.14 2088.48 2162.62 1539.65 1915.18 1277.06 1263.35 810.437 742.304 1480.31 830.831 649.48 723.19 622.967 1477.62
internal_count=246000 142403 110160 98730 64677 34053 103597 11430 32243 35848 59424 54092 28829 25861 17845 12555 23476 14739 14813 6105 7729 14398 8473 5925 8151 5290 24374
is_linear=0
shrinkage=0.0152673


Tree=82
num_leaves=28
num_cat=0
split_feature=20 20 155 120 20 118 387 135 7 391 391 33 111 0 163 133 391 391 20 167 391 391 391 148 86 390 135
split_gain=544.538 188.16 115.191 101.866 91.4407 77.1644 72.5564 68.3433 58.2414 59.3776 65.9641 55.8539 55.4225 55.2534 51.5546 49.225 43.9703 55.2041 41.38 40.7137 39.5886 37.021 36.387 35.375 34.4481 33.0501 31.2679
threshold=1.0000000180025095e-35 -1.126355914706455 36011.441250000011 -0.047074954296160869 0.51688161336547822 -0.07589928057553956 -1.0000000180025095e-35 0.49605103280680446 -0.59028425701312426 0.12742144408804593 -0.80185022711144738 1.0000000180025095e-35 1175.2425000000003 1.0000000180025095e-35 -1.0000000180025095e-35 0.17015384615384618 -0.80185022711144738 -0.45016581085748902 -1.8843834570786695 1.7500000000000002 -0.80185022711144738 -0.47078515063125309 -0.54098017844301649 -0.3996028899364622 1.0000000180025095e-35 0.3974512790610718 0.71051032806804393
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 4 19 5 -2 18 8 -5 10 -10 20 16 23 -9 -4 -7 21 -1 25 -8 22 -18 -12 -22 -3 -17
right_child=2 3 15 7 -6 12 11 14 9 -11 13 -13 -14 -15 -16 26 17 -19 -20 -21 24 -23 -24 -25 -26 -27 -28
leaf_value=0.011725900570932077 -0.0054864212384275034 -0.0030485300993452519 -0.0010771452818665542 -0.0028078913882322036 -0.0073635545384537916 -0.0079092131825363888 -0.0036407406451598938 -0.0011015724274454554 -0.0033210844879490746 -0.00093909463406653335 0.0096217663078582549 -0.0030438406368094475 0.0055422843672451932 -0.0078124962234272051 0.0070222285453120249 0.00083402530788788507 0.0054830794398957033 -0.0022876199444859147 0.0059391934121920814 0.020012589520944857 0.0040587660924548009 0.020628068828534858 -0.010142959647740852 0.0041227872023524717 0.012823210895961787 0.0010147615109176028 0.010381205498804082
leaf_weight=365.02080006152391 1796.1010963283479 1817.3166688419878 489.06137495860457 746.24643139541149 1491.5389862246811 271.43685233592987 141.48650080710649 227.59035841375589 270.10003748163581 1036.4577030017972 365.85967825725675 314.95513451099396 241.78397870436311 75.917603954672813 873.63615157827735 137.65562812611461 212.08578802645206 2035.8770731985569 1461.8600416816771 19.462423503398895 1256.4009609892964 31.00300795212388 41.027559954673052 1124.9219758361578 115.24900839477777 623.61391608044505 198.29998914897442
leaf_count=2336 34698 27323 7891 9176 30097 4664 1587 2638 3462 13659 3702 3256 3301 1022 8902 1981 3031 33284 11902 234 12177 413 713 12065 985 8850 2651
internal_value=0 0.00212634 -0.00334962 0.000689532 -0.00407193 -0.00300914 0.00494661 0.00200317 0.000986678 0.00197552 0.00362508 0.00278751 -0.00143517 0.00482872 0.00533507 0.00199782 -0.00209009 -0.00140469 0.00710158 -0.00182717 0.00400759 0.00488705 0.00290806 0.00547957 0.00480361 -0.00200668 0.00649938
internal_weight=0 10836.1 6945.87 7181.12 6120.85 4629.32 3654.97 4720.73 3619.5 2873.26 1836.8 1828.09 2833.21 1566.7 1101.23 825.017 2591.43 2319.99 1826.88 2460.39 1513.14 284.116 253.113 1490.78 1371.65 2440.93 335.956
internal_count=246000 123276 122724 91033 110201 80104 32243 54626 43086 33910 20251 18005 45406 16789 11540 12523 42105 37441 14238 36407 14749 4157 3744 15767 13162 36173 4632
is_linear=0
shrinkage=0.0152673


Tree=83
num_leaves=28
num_cat=0
split_feature=20 21 109 21 1 2 391 130 19 20 135 390 19 149 69 20 19 8 6 21 149 20 21 409 147 164 130
split_gain=530 257.49 197.456 178.198 117.358 80.6121 71.3241 71.0811 61.3363 57.4232 53.5771 55.7936 53.5044 51.3888 48.3599 46.671 46.2621 43.0844 63.5125 39.8382 38.7462 38.3552 36.8602 32.6655 31.6284 30.5582 30.149
threshold=0.12927495037510783 -0.70835755058453587 -0.58333333333333315 -0.45447813724047786 1.0000000180025095e-35 1.0000000180025095e-35 -0.80185022711144738 0.62500000000000011 0.10232330998452184 -1.6973680938911146 0.81318347509113009 -0.0069849579866133093 -0.20825903592772327 -0.21757018075529433 1.0000000180025095e-35 -1.0967390244420938 -0.16380825808307148 1.0000000180025095e-35 -0.1333583959899749 -2.0089485232886477 -0.1637686521149341 -1.4667066540297049 0.34138289464776045 -1.0000000180025095e-35 0.20270270270270274 172561.78125000003 0.79166666666666685
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 9 16 6 -6 -4 15 10 -3 11 -8 -5 24 22 -1 -2 18 -13 -17 -18 -7 -14 -9 -11 -12 -15
right_child=3 2 4 12 5 21 8 23 -10 13 25 17 14 26 -16 19 20 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0064906135192006574 0.0059140618111432107 0.011227082118769906 -0.0090406544078977802 0.0006318711416040141 0.004758655415214373 0.0052975414440415277 -0.0045067838106782627 0.0053816931534535215 -0.0070089970573207379 0.0094185080160773867 0.0025192673439288853 -0.00056560959544045574 -0.0054913094220949647 3.9974069654549822e-05 0.00024269404278092597 0.0089211657801056086 0.0019014664057245027 -0.0022179443452383005 0.0095818263257716075 0.0016255655306922176 -0.0029165218945398906 -0.0021287874306611188 -0.008856502183205989 0.010939250573673587 0.0023284887123923175 0.015905260611243095 0.0058565658824468615
leaf_weight=980.97776334732771 260.30049501359463 251.02280755341053 375.74682651460171 275.51629411056638 1047.9309682063758 190.89470694959164 1154.1827710084617 453.19563012197614 497.21091192215681 410.20734594762325 328.58005943521857 403.99714614078403 1956.2060669846833 865.99392725899816 240.29597261548042 195.12606051564217 639.91020573675632 883.66582890227437 221.68969240412116 1709.7181640304625 986.67743810638785 1054.498558524996 1271.0039699114859 567.16668637469411 234.56789947301149 45.595993477851152 274.40770641714334
leaf_count=6550 2855 1717 6261 4337 12644 1623 18023 3924 9015 4216 4395 5206 38115 10038 5010 1360 8415 13232 2681 16562 13748 15116 30143 4480 2620 500 3214
internal_value=0 0.00178213 0.000250454 -0.00388469 -0.00110234 0.00163713 -0.00271118 0.00501072 -0.00203532 0.0043764 -0.00121781 -0.00198015 -0.00581315 0.00340681 -0.0063279 0.0037799 -5.41389e-05 -4.16511e-05 0.00301705 0.00237857 -0.00101546 -0.000982453 -0.00681996 0.00848137 0.0068549 0.00418254 0.0014484
internal_weight=0 12146.4 8240.19 5629.91 6203.99 2293.32 3910.67 3906.18 3534.92 2036.2 3037.71 2663.54 3743.02 1785.18 3467.51 2885.82 1886.89 1509.35 625.687 1904.84 1626.59 1245.39 3227.21 1020.36 644.775 374.176 1140.4
internal_count=246000 143377 110501 102623 88696 29383 59313 32876 53052 21805 44037 39142 77605 20088 73268 24472 25018 21119 7887 17922 22163 16739 68258 8404 6836 4895 13252
is_linear=0
shrinkage=0.0152673


Tree=84
num_leaves=28
num_cat=0
split_feature=20 11 130 19 19 10 0 19 128 20 19 8 7 135 20 11 7 8 6 155 149 147 165 14 164 19 19
split_gain=515.601 203.188 117.649 111.761 107.501 104.138 81.6841 78.5018 78.2969 71.0741 60.8462 53.203 93.0276 52.4113 51.6207 48.1794 44.6278 69.4769 71.7188 41.6116 39.3168 37.8626 35.2788 35.1269 38.065 34.1947 33.4257
threshold=-0.63287083336150685 1.0000000180025095e-35 0.62500000000000011 0.1340576586752896 1.0000000180025095e-35 -0.55809641532756482 1.0000000180025095e-35 -0.094094051649595542 0.38593103448275862 -1.6973680938911146 -0.23674106267790407 0.51063775510204101 0.069042731852957659 0.71051032806804393 0.3451954345106808 -1.8655115511551152 -0.55072463768115931 1.0000000180025095e-35 -0.017790309106098575 40370.388750000006 -0.57728082535034619 0.71621621621621634 147260.48625000005 -1.0000000180025095e-35 30463.627500000006 -0.34208608255695944 0.2220264028087873
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 2 7 6 5 22 8 -2 11 -7 -4 12 23 15 19 -11 -17 18 -18 20 -9 -21 -1 -3 -25 -10 -12
right_child=1 3 10 -5 -6 9 -8 14 25 13 26 -13 -14 -15 -16 16 17 -19 -20 21 -22 -23 -24 24 -26 -27 -28
leaf_value=-0.00081110840209393329 5.9496274905062324e-05 -0.0042507592018386376 0.013838012328386152 -0.006871046417738713 -0.0019833145681802233 0.0087729796036706571 -0.0046139644376674595 -0.00044047128825922948 0.0091516839737384188 -0.0042210718492344222 -0.00018362652473414429 -0.00058544043400818031 0.0083840733154361222 0.0086616699184657395 -0.0082753315698471507 0.00033733158449529961 0.0054568916251820677 0.001972080824487364 0.014645485427019956 0.0092908722239067112 -0.0060424734563551147 -0.0026926950808386046 0.014046215339603858 0.0016300445238451311 0.0088395531270682969 -0.0021343579683050823 -0.007509893679394134
leaf_weight=961.9588003270328 610.60061771422625 187.12251694500446 67.637572437524796 458.96909312531352 734.050427634269 1015.3129930123687 530.61181408539414 344.39103325456381 65.742115449160337 180.41690244153142 1465.6835085824132 695.74463615193963 807.5145168043673 520.84695789590478 1326.5741810761392 643.53675194457173 933.18359912931919 1012.0081338994205 253.91977696865797 86.738754607737064 2062.1686492264271 208.26317525282502 38.532308612018824 1043.2947912588716 205.35480749234557 1147.7877962589264 161.29902427271008
leaf_count=11903 8933 2549 806 8597 9231 6933 7692 5730 630 2133 24540 10435 10240 4374 28012 6390 8319 10256 2033 1085 35903 3027 376 13851 2307 16483 3232
internal_value=0 -0.00193851 -0.00376912 0.000314452 0.00349908 0.00422461 0.00102088 -0.00502691 0.00174329 0.00520347 -0.000320552 0.00309135 0.00423572 0.00417781 -0.00580016 0.00340172 0.00388901 0.00492407 0.00743217 -0.00458084 -0.00524471 0.000803683 -0.000227055 0.00189537 0.00282429 -0.00151399 -0.000916416
internal_weight=0 11475.5 6333.36 5142.14 6293.77 5559.72 4683.17 4638.74 4152.56 4559.23 1694.62 2939.03 2243.29 3543.91 4028.14 3023.07 2842.65 2199.11 1187.1 2701.56 2406.56 295.002 1000.49 1435.77 1248.65 1213.53 1626.98
internal_count=246000 184052 111268 72784 61948 52717 64187 82690 56495 40438 28578 39382 28947 33505 73757 29131 26998 20608 10352 45745 41633 4112 12279 18707 16158 17113 27772
is_linear=0
shrinkage=0.0152673


Tree=85
num_leaves=28
num_cat=0
split_feature=20 21 109 21 20 149 130 20 70 21 19 20 411 19 389 19 143 141 21 6 8 149 165 165 411 152 21
split_gain=504.499 246.704 190.824 173.927 86.2985 79.7362 67.4754 60.6037 58.7778 51.8399 51.5699 45.4053 44.7845 44.1267 42.585 41.2899 41.2535 38.8252 44.1395 38.4281 38.6352 37.1799 37.0637 35.6966 35.6035 35.1468 34.9431
threshold=0.12927495037510783 -0.73924480687859639 -0.41666666666666657 -0.45447813724047786 -1.161217900876085 -0.21757018075529433 0.62500000000000011 -1.9674411247048098 -0.28455598455598446 0.62100165391621365 -0.20825903592772327 -1.0967390244420938 1.0000000180025095e-35 -0.26283576276536469 -0.11788761337740293 0.089247058428345918 2.5000000000000004 0.055555555555555559 -2.1181404424088144 -0.33396407685881363 1.0000000180025095e-35 -0.1637686521149341 166362.54750000002 205616.89125000002 1.0000000180025095e-35 2.4375000000000004 0.42665896000262526
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 5 13 19 8 11 -7 -3 15 -5 -1 -9 -2 25 23 24 18 -13 -4 -21 -15 -22 -6 26 -10 -12
right_child=3 2 4 10 9 7 -8 12 14 -11 16 17 -14 21 -16 -17 -18 -19 -20 20 22 -23 -24 -25 -26 -27 -28
leaf_value=0.0064123548382439685 0.0082174694212513184 0.00034664082088129095 -0.001577319572172089 0.00059485734138702408 -0.0013759031912532495 0.015372071265470645 0.008336764942998922 0.0019030553871933001 0.013159178473229774 -0.0059033616874547513 -0.0043092486594920399 0.015102308237738593 -0.0044763801912470844 0.0020496619431109812 0.0049539052622294645 -0.0064898673322267703 -0.00070479168110529496 -0.00045039226970326681 0.0032385122268791637 0.0083391096666145248 0.00049922330188618925 -0.0025028332826511927 0.017926765953840157 0.0082508401090652297 -0.0093753660341532701 -0.0024118299556280219 -0.0082997610374886018
leaf_weight=966.0704738907516 139.86041545122862 276.66751606762409 498.87250538542867 276.06062041223049 2489.8627419471741 69.745541796088219 1007.5502756722271 1623.0447973050177 397.28957477211952 902.36625308170915 1468.2937296926975 78.927707448601723 303.87580024823546 692.4892451800406 415.92476540803909 369.57237105816603 291.66025921702385 718.2713127322495 1063.7521997652948 284.99743146821856 541.88945545256138 1050.9850764721632 29.917089719325304 92.724735841155052 875.58297626674175 35.798508156090975 801.2257087379694
leaf_count=6361 1393 3419 5457 4337 36166 480 8180 18980 3989 17111 28224 536 4232 9023 4333 6829 5990 6992 9809 2713 6006 14602 270 1103 19966 411 19088
internal_value=0 0.00173243 0.00025646 -0.00380628 -0.00153089 0.00324182 0.00493714 0.00140379 0.00649304 -0.00269708 -0.00572316 0.00372177 0.000891903 -2.2245e-05 0.00848463 -0.0017136 -0.00623333 0.00231955 0.00406849 0.00177802 0.00374227 -0.00068935 0.001433 -0.00102611 -0.00674303 0.0118504 -0.00572269
internal_weight=0 12167.1 8332.55 5596.16 5210.2 3122.35 3834.57 1996.67 1125.68 3854.53 3712.82 2827.02 1926.92 1883.33 849.013 2952.16 3436.76 1860.95 1142.68 1355.68 856.804 1743.47 571.807 2582.59 3145.1 433.088 2269.52
internal_count=246000 143377 111499 102623 75655 35844 31878 23692 12152 61209 77605 23698 23212 25018 8733 44098 73268 17337 10345 14446 8989 23625 6276 37269 67278 4400 47312
is_linear=0
shrinkage=0.0152673


Tree=86
num_leaves=28
num_cat=0
split_feature=20 20 135 387 11 391 90 391 143 155 141 10 414 152 391 130 67 411 119 414 155 2 388 12 67 13 391
split_gain=490.254 196.649 114.469 96.7012 86.1789 79.512 65.5782 60.8097 56.8068 55.9776 54.0059 50.9802 48.7277 48.1647 47.9789 46.8744 42.5789 42.2362 39.4208 38.154 35.8892 33.4946 33.2216 32.6287 30.0073 29.2368 29.1477
threshold=0.12927495037510783 -1.055547744992388 0.49605103280680446 -0.028394675390716356 1.0000000180025095e-35 -0.80185022711144738 -1.0000000180025095e-35 0.12742144408804593 2.2777777777777781 33998.602500000008 0.16666666666666669 0.067367119901112493 -1.0000000180025095e-35 3.8125000000000004 -0.93013883649556617 0.62500000000000011 1.0000000180025095e-35 1.0000000180025095e-35 0.70828367103694878 -1.0000000180025095e-35 166477.46625000003 1.0000000180025095e-35 0.077739692133391769 0.65677501826150486 1.0000000180025095e-35 0.10220110540095027 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 3 16 15 14 -7 10 12 25 26 22 -6 -11 -1 24 19 21 -14 -3 -9 -13 -5 -21 -2 -4 -8
right_child=4 2 9 11 8 6 7 20 -10 13 -12 17 18 -15 -16 -17 -18 -19 -20 23 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.003853919109444433 -0.0070425381498580748 -0.0023299429747542589 -0.00032958441784835716 -0.0024352705251620126 -0.005335467942088082 0.0015746958962061107 0.0083375711691576569 0.0025576270453841724 0.0063509913507174926 0.010443833626516829 0.0041117661775774868 0.0028906296341397789 -0.0018814083246128182 -0.0014130451882859428 -0.0070881583715406409 -0.0023088216075756209 0.0063952561882258934 -0.0047648794070473894 0.0043918885978345935 0.0010086369938107063 0.014098933665006183 -0.0022260057516998301 -0.0067086880642445168 0.0066801302645786076 -0.0013727807199547673 0.0043574485288567248 0.013752440416841104
leaf_weight=166.08363196253777 2149.4578030444682 689.35766802728176 609.99337069317698 1064.5969464182854 756.57615567371249 935.70835836976767 863.54597678035498 975.36589439213276 195.89270210638642 402.19295500218868 575.20597378537059 779.33142482861876 1057.5496103577316 97.933525983244181 211.17593644559383 871.61914960294962 352.74580729007721 399.14525826275349 299.04484729096293 1558.6779385060072 67.462956409901381 481.08913730084896 716.54867361113429 280.03492682799697 246.77359799668193 623.96517674997449 329.31548516079783
leaf_count=1420 43173 9104 8120 17262 13542 9183 6596 9578 3060 3897 4999 9761 17331 1186 2426 16520 4088 5889 4216 18524 541 6229 11626 3137 4781 7399 2412
internal_value=0 0.00170417 0.000314895 -0.000637083 -0.00376135 0.00441564 0.00508908 0.00625552 -0.00149789 0.00379024 0.00798377 -0.00236585 -0.00223035 0.0081041 -0.00224729 -0.00535771 0.00142452 -0.000434307 -0.000491341 0.000726868 0.0033156 0.000930354 -0.00416015 0.00187802 -0.00646263 0.00203337 0.0098422
internal_weight=0 12179.5 8055.61 6321.53 5576.91 4123.86 3746.6 2810.9 2309.06 1734.09 1768.07 3440.71 2113.17 500.126 377.26 3267.85 2880.82 1659.57 1356.59 2528.07 1042.83 1260.42 1781.15 1838.71 2396.23 1233.96 1192.86
internal_count=246000 143377 106222 85620 102623 37155 33309 24126 38149 20602 14007 50767 35089 5083 3846 64474 34853 21879 21547 30765 10119 15990 28888 21661 47954 15519 9008
is_linear=0
shrinkage=0.0152673


Tree=87
num_leaves=28
num_cat=0
split_feature=20 21 21 19 20 21 7 8 391 7 130 19 69 19 141 21 8 7 391 155 21 141 132 143 64 20 151
split_gain=476.375 233.276 173.497 150.739 127.228 85.5199 71.6003 99.4936 89.643 73.8205 65.5323 53.6036 46.4272 43.4447 42.4472 47.8873 38.8523 43.4045 38.104 36.7528 36.6819 34.7727 32.7461 31.6409 30.5345 28.876 28.0017
threshold=0.12356881070161159 -0.70835755058453587 -0.45447813724047786 0.023652303677922096 -1.523630872707755 0.62824895294929128 -0.46140449088760332 1.0000000180025095e-35 -0.66068996828538784 -0.0048516514275051305 0.62500000000000011 -0.20825903592772327 1.0000000180025095e-35 0.015927314024199116 -0.16666666666666663 -1.9198993040030075 0.51063775510204101 -0.0240094545002177 -0.64052006669616957 132220.58625000002 0.23070768362874469 0.27777777777777785 -182674.24999999997 2.7222222222222228 18.015625000000039 -1.1194625484164258 0.52113866967305533
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 13 4 21 6 19 8 -8 18 14 -4 20 16 15 -1 17 -2 -10 -6 -13 -3 -7 -9 -17 -16 -20
right_child=2 3 11 -5 5 22 7 23 9 -11 -12 12 -14 -15 25 24 -18 -19 26 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.011836198743606339 0.00018936027193266865 0.0075302310711452686 0.00078950551978480691 -0.0050111141311004548 -0.0025550372458968472 0.01134820369980476 -0.0017194117021018479 -0.00068880753935523912 0.014935727517674068 0.011692912290772732 0.0080686620050976002 -0.0051510278036764733 0.00030649626452300074 -0.004510355862791195 0.0048539717814896121 0.005000772323420978 -0.0029480060280004878 0.0063025512458370573 0.0015318172519447652 0.0084959502611787162 -0.008469413975118566 0.001578329908558354 -0.0043609024124210416 0.0064165834046211187 -0.0029929068852294172 0.00019684430127582715 0.010198213894796788
leaf_weight=228.94300117343664 675.41149080917239 784.93908482044935 280.02309082821012 1107.6074462495744 1309.2028453424573 31.436345260590315 356.44357378035784 1848.6338502839208 67.286671176552773 473.02544488757849 1029.1882415041327 1791.6460179463029 240.38838312774897 385.33780734613538 458.23005698621273 1108.6072090864182 384.91495740786195 455.27620954811573 578.47899579256773 73.596552908420563 1407.1929548047483 329.05231816321611 987.93881011381745 158.36118837073445 122.20264473557472 974.47669592872262 103.05348190292716
leaf_count=1420 8350 6258 4403 18992 17239 494 4610 25000 706 4934 8346 34878 5055 6248 3086 9307 5234 5448 6976 779 33981 3026 17596 2030 1124 9395 1085
internal_value=0 0.00168998 -0.00368678 0.000225454 0.00104361 0.000160505 0.000988513 0.00212797 0.00499584 0.00696231 0.00475313 -0.00560446 -0.00612774 6.05962e-05 0.00356977 0.00540479 0.00122923 0.00265964 0.00395946 -0.0019591 -0.00661411 0.00578097 -0.00386534 -0.000123012 0.00419931 0.00169322 0.00285829
internal_weight=0 12130.7 5620.19 8209.06 7101.45 5987.46 4968.08 3585.28 1578.29 1221.84 3921.65 3719.25 3439.23 1900.94 2892.46 1459.75 1515.6 1130.69 748.819 1382.8 3198.84 1113.99 1019.38 2007 1230.81 1432.71 681.532
internal_count=246000 142403 103597 109725 90733 81449 63359 45341 18311 13701 32678 78317 73914 25280 24332 11851 19032 13798 8767 18018 68859 9284 18090 27030 10431 12481 8061
is_linear=0
shrinkage=0.0152673


Tree=88
num_leaves=28
num_cat=0
split_feature=20 387 19 155 391 392 143 7 20 20 391 391 19 67 20 387 19 10 128 141 157 130 391 152 90 7 118
split_gain=463.44 154.798 125.781 104.118 92.0017 90.9069 99.294 89.1282 82.2566 77.1608 68.9218 70.3886 65.1466 66.8054 50.2968 48.0637 46.4354 45.1364 45.0404 43.5697 42.0073 38.1637 36.9617 36.6789 35.3556 35.1047 35.6593
threshold=-0.049110989848547566 -0.037632662431008129 0.066137329671330417 36011.441250000011 -0.80185022711144738 0.30113188380779204 3.3888888888888897 -0.55072463768115931 0.53544518614522296 -1.805970119445869 0.12742144408804593 -0.80185022711144738 -0.32834624111576771 1.0000000180025095e-35 -1.6199246107459455 -0.0098228363625392414 -0.38840974305326348 0.81712676830105768 0.14481034482758623 -0.20370370370370366 13162.500000000002 1.7916666666666667 -0.93476319353839921 0.68750000000000011 -1.0000000180025095e-35 -0.6171549418423834 -0.11187050359712229
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 3 8 -3 6 14 -1 12 -9 11 22 -2 15 -6 18 -13 19 -14 -18 -12 -21 -11 -5 -7 -16 -27
right_child=2 4 -4 23 5 24 -8 9 -10 10 20 16 13 -15 25 -17 17 -19 -20 21 -22 -23 -24 -25 -26 26 -28
leaf_value=0.00019849588047949238 0.0070483720742892959 -0.0057415586963198021 -0.0072475099570423664 0.0082515068432755367 0.0037313297940653237 -0.00031902031629711723 0.0086409835692363521 0.011662900902636962 -0.0066414580554279455 0.0050129414948696287 0.00094859919336420871 0.01886356122154375 0.0011632557904561519 0.0031898304333316937 -0.0057284248273174977 -0.0044799562196980907 0.010181037221950571 0.00088810675307058749 -0.0041359368267288544 0.0035515179941577294 0.020974295455333008 0.011817237094506392 -0.0058384806072992613 0.00093433178293495314 0.0053809702095076288 -0.003481796302360304 0.00037887502491221555
leaf_weight=1111.0470689348876 183.8678683154285 532.13854518905282 1310.3920661844313 243.18576526269317 427.91944169998169 321.87985485419631 261.45689303427935 379.86562417447567 1028.5654112994671 131.36343393102288 1150.5738028809428 74.493955656886101 949.67374840006232 467.81906609237194 462.73228907585144 2037.789353813976 759.04965524747968 286.18538753315806 614.6993317566812 696.75797186046839 24.811938274651766 162.10877951979637 163.85492543503642 474.5182278342545 1145.9540571942925 909.62955618649721 1431.4868642576039
leaf_count=11293 2006 7379 27512 3169 3779 3510 3051 2392 20692 1311 13122 524 14588 7702 6603 37460 6790 2304 9762 7003 230 1538 1986 7055 11273 13839 18127
internal_value=0 0.00205304 -0.00295989 -0.00202177 0.000287655 0.000936419 -0.000400906 0.00401412 -0.00276405 0.00511881 0.00439481 0.00594759 -0.00182408 -0.00222749 -0.00113574 -0.00293373 0.00698568 0.00651424 -0.000913398 0.00750352 0.00138262 0.0051247 -0.000978786 0.00342804 0.00412491 -0.00188202 -0.00111743
internal_weight=0 10433.3 7310.51 6000.12 5493.2 4961.06 3493.23 4940.11 5282.41 3829.07 3449.2 2273.81 4253.85 4069.98 3231.77 3602.16 1978.6 1904.1 1564.37 1617.92 1175.39 858.867 295.218 717.704 1467.83 2803.85 2341.12
internal_count=246000 116054 129946 102434 67561 60182 45399 48493 92210 37200 34808 21456 71518 69512 42348 61810 18159 17635 24350 15331 13352 8541 3297 10224 14783 38569 31966
is_linear=0
shrinkage=0.0152673


Tree=89
num_leaves=28
num_cat=0
split_feature=20 21 411 21 11 1 130 391 391 391 19 120 19 387 23 20 19 7 8 7 164 24 157 7 8 122 67
split_gain=451.405 323.139 121.143 108.261 88.8559 73.891 72.8643 64.3781 51.0633 63.9892 50.37 48.8587 48.3426 42.4264 42.262 41.5631 40.8519 39.6571 70.4341 40.6976 39.1761 38.3383 38.3243 38.2282 36.5478 47.478 35.4281
threshold=-0.69501558637790939 -0.55092222074356589 1.0000000180025095e-35 0.38809800176773507 1.0000000180025095e-35 1.0000000180025095e-35 0.62500000000000011 -0.82711714898909583 -0.84913404291403738 -0.63378138164839226 0.16380191123207924 -0.40265082266910418 0.066137329671330417 -0.085097128818110032 0.0094499999999999949 0.40764048554982751 0.19388630579008007 -0.43328979287180441 1.0000000180025095e-35 0.085712508552590674 124939.44000000002 2.5000000000002225 281.25000000000006 -0.55072463768115931 1.0000000180025095e-35 0.39655172413793111 2.5000000000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=3 6 4 5 8 7 12 -1 -3 -10 17 -9 13 21 20 22 -8 -6 19 26 -13 -2 -11 -7 25 -25 -19
right_child=1 2 -4 -5 10 23 16 11 9 15 -12 14 -14 -15 -16 -17 -18 18 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=-0.0052008845450929372 0.0048752715479701619 -0.0095780239315951827 -0.006997301497352235 -0.0014148785457622094 -0.0029240838735066668 0.0021646339843532474 0.0060923181948893904 -0.0010976556408688878 0.0060144765538030342 -0.0032958364567485287 -0.0090155238469604628 0.0043856219472113937 -0.004526882383944014 -0.00059389778377557084 -0.0012032236175496004 -0.0071759453564990191 -0.0052499291922530663 0.0017296241311732883 -0.00124057826833672 0.0094914615838137695 0.012031269901396104 -0.0016400189135606265 0.0079566542325889469 0.011673142815986788 0.0049177851887590041 0.0038728962701881265 0.055745588877698662
leaf_weight=219.06874256208539 925.26130763068795 355.06705266237259 1828.0921800211072 923.98801197856665 661.78842044621706 387.00667813420296 980.55497946590185 472.29695089161396 157.1992384493351 2177.582988768816 145.33198165521026 1912.4312018975616 378.8865683786571 1286.4855119027197 286.84781799837947 712.87551163136959 79.037836357951164 439.40454815328121 954.81241308152676 290.61702574044466 171.87553033605218 269.94354051724076 72.274169716984034 674.05788533017039 717.71800653263927 254.86174184456468 2.6622036807239047
leaf_count=2391 9309 7286 37320 13502 9976 3204 10444 5062 2800 40142 2966 17184 5715 15076 2663 16404 1178 6193 15214 3900 1306 2880 1067 4845 6050 1888 35
internal_value=0 -0.00175791 -0.00355591 0.00338564 -0.00250031 0.00425785 0.0018162 0.00275429 -0.00407863 -0.00344925 -0.000297889 0.00337073 0.000545696 0.00132413 0.00426464 -0.00395485 0.0052368 0.000238226 0.00148402 0.00504651 0.00502158 0.00339607 -0.00292962 0.00651709 0.00753409 0.00954419 0.00210069
internal_weight=0 11717.9 7797.71 6020.15 5969.62 5096.16 3920.17 3062.52 3475 3119.93 2494.62 2843.45 2860.58 2481.69 2371.15 2962.73 1059.59 2349.28 1687.5 732.684 2084.31 1195.2 2249.86 2033.64 1646.64 928.92 442.067
internal_count=246000 187905 143303 58095 105983 44593 44602 28606 67699 60413 38284 26215 32980 27265 21153 57613 11622 35318 25342 10128 18490 12189 41209 15987 12783 6733 6228
is_linear=0
shrinkage=0.0152673


Tree=90
num_leaves=28
num_cat=0
split_feature=19 11 391 391 90 391 391 19 135 390 149 128 391 10 19 69 155 19 391 130 157 164 47 245 120 130 141
split_gain=341.458 247.97 130.216 153.11 130.041 109.322 168.502 97.5974 93.3692 66.6012 61.3131 56.9783 55.6878 51.8191 48.219 45.4047 42.2036 41.2278 40.6604 37.5596 35.8499 35.0864 34.4262 33.5213 33.3717 30.1245 30.1207
threshold=0.066137329671330417 1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 -1.0000000180025095e-35 0.12742144408804593 -0.66068996828538784 -0.31045995720902853 0.63578371810449585 -0.43750805970333967 -0.28675913025453731 0.15534482758620691 0.12742144408804593 0.81712676830105768 -0.34208608255695944 1.0000000180025095e-35 35028.247500000005 0.19388630579008007 -0.92257102786474277 0.95833333333333337 11137.500000000002 173595.48750000002 1.0000000180025095e-35 1508.5969999999218 0.59003656307129815 0.12500000000000003 -0.2407407407407407
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 18 -4 15 6 -6 25 9 -9 12 13 -11 16 23 -3 22 19 -1 -2 -7 -10 -8 -13 -12 -5 -16
right_child=17 4 3 7 5 20 11 8 21 10 24 14 -14 -15 26 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.002020678629171596 -0.0049167935588390142 -0.0015383165332535729 0.0090697390915576905 0.0056394047423185389 -0.0012226995069053847 0.000410262100300209 0.0094481567569824967 -0.0046379808326704446 0.0017766421585818871 0.0053287422125306971 -0.0031275324650690737 0.010901109347670209 -0.0013331875567082656 0.0030286035898843783 0.006004381122202136 0.0071242199125139084 0.014786117946916697 -0.0074207937056746344 -0.0095284598334235485 0.0014648797501083531 0.013528015759045713 0.010510723130025096 0.0033158480174400582 0.039156631505154881 0.0017159038067226557 0.018807687109282722 0.00075533051863633984
leaf_weight=254.73930967226624 878.80350180715322 1653.4456757679582 372.91630445420742 160.05636865273118 746.82621540129185 1764.0571565963328 1183.9791996181011 1708.8897914998233 957.25542564690113 567.66403510794044 2060.4430171959102 84.634260058403015 599.62081420794129 364.15832346305251 458.91630465909839 153.75728921219707 287.93412389233708 1195.3301626220345 515.56839492172003 281.81287344545126 49.824048168957233 121.39467064291239 266.70092003047466 11.352172657847403 392.43636042624712 55.889461252838373 583.21138120442629
leaf_count=3750 15584 20297 4447 1615 8788 22465 11902 27506 13255 7555 32866 662 9375 3052 4590 1709 2479 23005 9334 4558 511 1355 3020 90 5198 533 6499
internal_value=0 0.000817141 -0.00110102 -0.0004436 0.00277634 0.00389054 0.00530435 -0.000980848 -0.00132243 -0.00215253 -0.000976563 0.00681124 0.0018991 0.00830476 0.00404281 -0.000795531 0.00940412 -0.00542434 -0.00705871 -0.00335936 0.000777084 0.00276986 0.00832769 0.0144126 -0.00234882 0.00910415 0.00307632
internal_weight=0 15375.7 7766.87 6996.57 7608.8 5801.59 3987.71 6623.65 6407.7 5329.05 3620.16 3240.89 1167.28 2102.77 1138.11 1807.2 1738.61 2355.95 770.308 1160.62 1813.88 1078.65 1450.68 95.9864 2452.88 215.946 1042.13
internal_count=246000 202853 116789 103705 86064 64058 41082 99258 97110 82500 54994 32294 16930 20453 11841 22006 17401 43147 13084 20142 22976 14610 14922 752 38064 2148 11089
is_linear=0
shrinkage=0.0152673


Tree=91
num_leaves=28
num_cat=0
split_feature=20 21 21 1 2 10 19 119 38 90 411 135 19 141 149 19 21 7 129 135 154 149 163 112 135 411 166
split_gain=438.924 218.952 161.49 148.802 100.021 91.3545 87.5787 68.5927 54.2716 51.8865 50.2234 50.0831 48.1378 43.2561 40.7295 40.5676 40.3582 39.0197 38.1493 37.7367 36.8721 36.3158 35.2118 33.6835 33.1264 33.0917 32.5833
threshold=0.12927495037510783 -0.70835755058453587 -0.45447813724047786 1.0000000180025095e-35 1.0000000180025095e-35 -0.32090372201620648 0.057861324674422961 0.56168057210965439 0.001749999999999974 -1.0000000180025095e-35 1.0000000180025095e-35 0.5871810449574727 -0.20825903592772327 0.055555555555555559 -0.56276057860585704 -0.16380825808307148 0.38034479682904804 -0.54077253218884114 -0.43956739595151945 0.5653098420413124 1.5000000000000002 -0.1637686521149341 -0.078749999999999973 -0.64902126047634823 1.0000000180025095e-35 1.0000000180025095e-35 163488.19500000001
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 15 5 9 19 10 17 -9 -5 11 14 -4 18 20 -2 25 -1 -11 -3 -7 -17 -13 -19 -6 -14 -26
right_child=2 3 12 4 24 6 -8 8 -10 13 -12 22 16 -15 -16 21 -18 23 -20 -21 -22 -23 -24 -25 26 -27 -28
leaf_value=-0.00077773206250612425 0.0055988908857473284 -0.0053945649038394348 0.0006353033978680479 0.00076839495484193831 -0.0018812194169523266 0.0096425725686228817 -0.0063398304789962813 0.0083335357938805112 0.00075003828309677689 0.015143413437073209 -0.0030810953529044243 -0.00052242816730214156 -0.0035029686395225685 0.0034099997886948849 4.0531229868452976e-05 0.0019624776437699508 -0.0081598997382191039 0.010289830962144073 0.0072351999366767191 4.8490651895751388e-05 -0.0026856985664454212 -0.0027195477169883919 0.0096048214671094097 0.0032741418830249747 0.0016399067799031484 -0.0078439942061612877 0.014674402549318058
leaf_weight=517.45635584741831 263.44445751234889 1394.5236761346459 275.38256991654634 403.52758734673262 885.93522468209267 208.04427277669311 433.0962724275887 1296.3577170222998 268.21910110488534 202.31086874380708 558.08648093044758 107.15623246505857 1540.5235704407096 451.21125766634941 1627.5317815206945 637.68265020102262 1248.3454667441547 177.60889856144786 513.4881577603519 372.95577157661319 76.096451934427023 973.68735633045435 297.2428241558373 1707.8068098053336 675.39673475548625 566.08734604343772 47.989353343844414
leaf_count=4590 2855 23520 4337 4971 11807 2461 7568 9957 2243 1945 8013 1279 29842 5266 20370 8415 30828 1332 5144 5449 1009 13748 3049 14754 8158 12598 492
internal_value=0 0.00160022 -0.00359152 0.000182354 0.00277277 -0.00143906 5.57513e-05 0.00454774 0.0070396 0.00551356 0.00102304 0.00201612 -0.00547058 0.00714608 0.000977615 4.23537e-05 -0.0059745 0.00292096 0.00948675 -0.00424097 0.00630912 -0.000860988 0.00689977 0.00394091 9.19844e-05 -0.00467447 0.00252109
internal_weight=0 12222 5505.15 8254.59 3179.86 5074.73 3307.25 3967.45 1564.58 1570.54 2874.16 2316.07 3630.34 1167.01 1911.67 1874.81 3354.96 2402.87 715.799 1767.48 284.141 1611.37 404.399 1885.42 1609.32 2106.61 723.386
internal_count=246000 143377 102623 110501 37783 72718 43749 32876 12200 17326 36181 28168 77605 12355 23840 25018 73268 20676 7089 28969 3470 22163 4328 16086 20457 42440 8650
is_linear=0
shrinkage=0.0152673


Tree=92
num_leaves=28
num_cat=0
split_feature=20 21 411 10 1 391 10 119 391 90 19 10 416 141 19 1 128 391 135 21 143 411 135 429 20 149 7
split_gain=427.344 319.649 124.635 96.6842 88.5718 85.3487 80.0781 75.6526 70.0651 69.6091 51.6628 49.2756 81.4902 50.1143 48.3964 47.4648 43.9407 43.5931 41.0538 40.009 38.8541 38.1285 35.4853 35.217 31.6535 31.3799 30.8388
threshold=-0.78572725661621623 -0.55092222074356589 1.0000000180025095e-35 -0.28409559126493605 1.0000000180025095e-35 0.12742144408804593 -0.32941903584672433 0.73808104886769976 -0.81178185562575544 -1.0000000180025095e-35 0.018489692726097188 0.72043675319324285 -1.0000000180025095e-35 0.20370370370370372 -0.30194024828142119 1.0000000180025095e-35 0.48968965517241386 -0.81178185562575544 0.457168894289186 -1.183691474673304 2.6111111111111112 1.0000000180025095e-35 0.83748481166464173 1.0000000180025095e-35 0.60147958347304475 -0.57728082535034619 -0.85923990794302407
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=4 7 3 15 6 8 22 14 -5 -10 17 12 13 26 -2 20 24 -8 25 -14 -3 -9 -1 -19 -11 -16 -6
right_child=1 2 -4 5 11 -7 10 21 9 16 -12 -13 19 -15 18 -17 -18 23 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.002779726875537957 0.0078222710490619771 -0.0069675073599987595 -0.0068503998034649179 -0.0050198950826006701 0.00071585257313541803 -0.0039945922802582809 -0.0036450769389262767 0.0065016998861269866 -0.0025226225726308576 0.005739341116342841 -0.0025626441248972382 0.0019352347515301947 0.010889249848165564 0.0046989900753120614 0.0036463308319208743 -0.0012353050008910035 -0.00067062910464039602 0.0057981975202402759 0.0033689077344275669 0.0035238859335274585 0.00022016243135009487 0.00047260765882865265 0.0051647059482763449 -0.00050748315146866983 -0.0059067143853242859 -0.0018861812915428266 0.016736456875472538
leaf_weight=880.24639374762774 193.57917051017284 1498.5564002916217 1856.3725251480937 407.22725016251206 31.926433604210615 1327.8865263946354 144.98211126774549 944.67246202751994 598.98977461829782 1076.8646091520786 283.38166224211454 557.35998413339257 213.74931909143925 147.8417429998517 275.55137066915631 641.21837558224797 408.3885539136827 1636.4588500112295 615.93383522704244 921.8721860460937 195.72201234474778 334.42784484103322 153.1429976336658 233.19651750847697 56.363932352513075 1754.0277027674019 330.87791477516294
leaf_count=11209 1616 30900 38067 6995 275 23612 1511 9398 9848 15390 3400 4020 1302 1302 3209 11647 6262 14176 6611 8886 3658 3924 1577 2056 1179 21386 2584
internal_value=0 -0.00160989 -0.00337692 -0.00233713 0.00350574 -0.000855511 0.00193072 0.00184953 0.000777113 0.00188458 0.00351917 0.00588229 0.00721264 0.0122895 0.000456924 -0.00479164 0.00360302 0.00437936 -7.91061e-05 0.00491995 -0.00613186 0.00493284 -0.00159277 0.00500684 0.00515107 -0.00113025 0.0153531
internal_weight=0 12185.8 8067.59 6211.22 5535.04 3875.72 3331.41 4118.19 2547.83 2140.61 2298.02 2203.63 1646.27 510.646 2839.09 2335.5 1541.62 2014.64 2645.51 1135.62 1694.28 1279.1 1033.39 1869.66 1133.23 2029.58 362.804
internal_count=246000 193702 147558 109491 52298 63286 33929 46144 39674 32679 21143 18369 14349 4161 32822 46205 22831 17743 31206 10188 34558 13322 12786 16232 16569 24595 2859
is_linear=0
shrinkage=0.0152673


Tree=93
num_leaves=28
num_cat=0
split_feature=20 20 155 1 10 391 119 154 411 391 388 90 1 143 143 411 10 391 391 391 90 391 392 128 8 147 416
split_gain=420.157 180.799 117.996 98.4156 89.8921 69.5582 68.8138 66.1769 61.1424 58.0336 60.6838 57.447 59.0607 56.6313 52.4918 50.8649 47.5509 44.7467 42.337 38.1722 54.5565 35.4549 70.8566 32.0938 30.3723 29.8108 29.3379
threshold=0.18705904504727433 -1.055547744992388 33998.602500000008 1.0000000180025095e-35 -0.16446916632330721 -0.80185022711144738 -0.057508939213349215 4.5000000000000009 1.0000000180025095e-35 0.1379033485638034 0.75920292075488105 -1.0000000180025095e-35 1.0000000180025095e-35 2.2777777777777781 2.6111111111111112 1.0000000180025095e-35 -0.32090372201620648 -0.93013883649556617 -0.81178185562575544 0.12742144408804593 -1.0000000180025095e-35 -0.84913404291403738 0.19292129862590529 0.14481034482758623 0.51063775510204101 0.12162162162162164 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 3 4 14 17 -2 23 18 10 24 -7 16 15 -3 21 -13 -1 -6 20 -20 -8 -23 -4 25 -5 -14
right_child=6 2 7 9 8 11 13 -9 -10 -11 -12 12 26 -15 -16 -17 -18 -19 19 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0036411545652921431 -0.0061094830305104949 -0.0054111799098050129 0.0094698311899916125 0.0075494573531586827 -0.0060854204255385673 0.0013879584505118174 -0.0084453143944597728 -0.0011192929843947105 -0.0039928263489110247 -0.0016136553666556239 -0.00041353782183993531 -0.0003864480603188214 0.011735908422965576 0.0036491996460142639 0.0026546321739171833 -0.00637413054931644 0.0054332930243472834 -0.0069360593096184876 -0.002122679046806734 -0.001233658853838652 0.0050660768662280859 -0.0033607531308258868 0.0031158349595282906 0.0028777361407951807 -0.0018115255608748008 0.0022479258808269001 0.0065347501561134952
leaf_weight=167.28297310322523 1884.446093108505 1632.0925376340747 515.52406047657132 802.17142754048109 173.00903154909611 942.42996953427792 168.0716950558126 305.01114401966333 724.2324820831418 844.54273026436567 714.31262526661158 430.03074202686548 420.20154738426208 322.58298775926232 210.82740537822247 787.44553956016898 1331.4344425164163 208.28262373805046 325.39011501893401 650.69483514875174 988.81303346529603 1123.8967316895723 604.69669843837619 265.68468610197306 130.59772177785635 365.72934025526047 675.12849047407508
leaf_count=1420 39405 27264 5198 8873 2482 9183 3100 3925 10738 11778 8929 4801 2880 5443 3052 15496 11214 2426 4127 9148 11160 20595 9004 2886 1768 4474 5231
internal_value=0 0.00144015 0.000179505 -0.000495289 -0.00185346 0.00404941 -0.00381903 0.00488517 -0.000156723 0.00173791 0.00314875 0.00466977 0.00574903 -0.00238014 -0.0044833 -0.00310839 0.00400742 -0.00220099 0.00113875 0.00178006 0.00327916 -0.00174718 -0.00108972 0.00724093 0.0051152 0.00589779 0.00854021
internal_weight=0 12823.4 8648.63 7562.41 4705.06 4174.79 4891.14 1086.22 2862.14 2857.35 2012.81 3799.23 2856.8 3006.69 1842.92 2684.11 1761.47 375.566 2137.91 1964.9 1314.2 1896.67 1728.59 781.209 1298.5 1167.9 1095.33
internal_count=246000 152957 115802 103793 67971 37155 93043 12009 37655 35822 24044 33309 24126 53638 30316 48195 16015 3846 26917 24435 15287 32699 29599 8084 15115 13347 8111
is_linear=0
shrinkage=0.0152673


Tree=94
num_leaves=28
num_cat=0
split_feature=20 21 109 21 1 149 119 135 21 7 152 20 19 90 52 411 416 130 143 411 21 390 109 19 164 137 128
split_gain=408.353 227.924 179.119 130.163 78.7051 71.6076 63.7597 58.2763 55.7907 55.7208 58.1635 54.5014 48.3162 48.1237 46.4134 45.1364 42.9269 44.2804 40.6754 39.7986 36.7303 36.6451 32.6758 32.3253 30.9172 30.8691 30.3243
threshold=0.18705904504727433 -0.73924480687859639 -0.41666666666666657 -0.94860626875739484 1.0000000180025095e-35 -0.21757018075529433 0.57479141835518488 0.81318347509113009 0.093766758909517342 -0.46140449088760332 1.3125000000000002 -1.9674411247048098 -0.18666175517883321 -1.0000000180025095e-35 3.5000000000003335 1.0000000180025095e-35 -1.0000000180025095e-35 0.12500000000000003 1.3888888888888891 1.0000000180025095e-35 -1.6426344058948754 -0.11944027006271453 2.4166666666666674 -0.26591259781672544 80128.271250000005 -0.92857142857142849 0.17865517241379311
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 5 23 7 9 18 12 19 24 26 -7 -4 -6 22 -13 -15 -18 20 25 -1 -14 -8 -2 -3 -5 -11
right_child=3 2 4 8 13 11 14 -9 -10 10 -12 15 21 16 -16 -17 17 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0049803456435365068 0.010164578339293719 -0.00032103921183121074 0.0026213779933422438 0.0040613719579303586 -0.0028145146274462674 0.01422110196939087 0.0077947680209679727 0.0023222170186139143 -0.0072818475166530417 0.012502501999334534 -0.00034791145706751704 0.0016731298147782431 -0.0063656375481841937 0.0066846771713456685 0.0010931258649041215 -0.0045733340405389204 -0.001162190343108351 0.0063238424623183343 0.0075961566717060516 -0.0068488950081008158 0.00066955367953498094 -0.0028333605859461436 0.037386710915551256 0.00023136068842059883 0.014209912067860519 -0.0029721129551993431 0.0053917673480608367
leaf_weight=680.94762168079615 83.10930261015892 349.14700312167406 251.9568334557116 159.85100189596415 605.2536836899817 71.690055832266808 1297.6426200419664 414.60185402259231 1571.1953364238143 431.37018687650561 149.83397752419114 1706.0078046433628 1198.6001190021634 383.7605306878686 277.78921858966351 319.59885968267918 751.14037343114614 243.40351839363575 363.66749833151698 615.9126433506608 1443.4022493101656 1632.4876882210374 8.7408784404396993 944.65294755622745 37.511405277997255 1499.8605204299092 215.62442123517394
leaf_count=4651 748 3973 3055 2795 8625 480 9906 5735 38571 4426 1745 20141 20591 4469 2325 4599 9911 3183 2995 12777 13781 25622 69 11503 341 26649 2334
internal_value=0 0.00141682 2.8717e-05 -0.00377373 -0.00165903 0.00285115 0.00440116 -0.00303721 -0.00506362 0.00585535 0.0081643 0.00115114 -0.00376101 0.000766597 0.00679944 0.000682691 0.00234599 0.000661627 0.00287002 -0.00352752 0.002056 -0.0043324 0.00800547 0.00104534 0.00107161 -0.00228877 0.0101493
internal_weight=0 12834.2 8761.99 4874.58 5481.2 3280.78 4072.19 3497.65 3846.82 1183.49 796.829 2097.3 3083.04 1983.56 1584.17 2025.61 1378.3 994.544 2488.02 2275.62 2124.35 2831.09 1306.38 1027.76 386.658 1659.71 646.995
internal_count=246000 152957 119230 93043 81191 38039 33727 55003 80792 12819 8505 25220 49268 26188 12300 24740 17563 13094 21427 42221 18432 46213 9975 12251 4314 29444 6760
is_linear=0
shrinkage=0.0152673


Tree=95
num_leaves=28
num_cat=0
split_feature=19 11 391 391 90 391 391 19 143 166 390 391 391 128 10 391 19 69 19 391 155 86 113 157 390 245 141
split_gain=317.364 225.289 123.823 142.988 119.631 98.1387 154.477 90.0667 84.6718 63.7522 53.3926 63.1457 87.7426 52.1662 50.3739 46.1104 44.4484 43.4427 40.0744 39.3934 38.1932 39.571 37.4563 33.6417 32.8106 30.9657 29.7626
threshold=0.066137329671330417 1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 -1.0000000180025095e-35 0.12742144408804593 -0.66068996828538784 -0.31045995720902853 2.6111111111111112 5029.4025000000011 -0.43750805970333967 0.12742144408804593 1.0000000180025095e-35 0.15534482758620691 0.81712676830105768 0.049180694651566131 -0.34208608255695944 1.0000000180025095e-35 0.19388630579008007 -0.92257102786474277 33998.602500000008 1.0000000180025095e-35 0.75491594814217489 11137.500000000002 0.26216017897065569 1508.5969999999218 2.2407407407407409
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 19 -4 17 6 -6 -5 9 10 -9 12 22 14 20 -14 25 -3 -2 -1 21 -8 -12 -7 -10 -15 -26
right_child=18 4 3 7 5 23 13 8 24 -11 11 -13 15 16 -16 -17 -18 -19 -20 -21 -22 -23 -24 -25 26 -27 -28
leaf_value=-0.0019486031132595056 -0.0032272395796811258 -0.0015194395607554274 0.0087238565512212478 0.0086815912274540562 -0.0012260735310003481 0.00039215775770056344 0.0069473199502068624 -0.0048072165947257309 0.0023082227691297707 0.002249955220988897 -0.0027223450010358864 -0.0034173262656375502 0.014636371679952451 0.01030179709608642 0.0027063791177423129 0.0033448295041132049 0.0028889112345537767 0.0069295898485210892 -0.0072584330338971107 -0.009376316877025264 0.014011497545738626 0.014472174171797934 0.0033120809665310286 0.013014073492410405 0.0093720959240421974 0.03703627058991036 0.045504131513593213
leaf_weight=253.38766669481993 1149.1104594990611 1649.8215028941631 377.12821532040834 218.88167306035757 745.99991345778108 1763.4502664878964 1277.8701769076288 1576.4675055667758 504.23304421827197 763.61024427041411 949.72563377767801 1760.1915971450508 127.69935796409845 86.087870206683874 368.42468136548996 256.79586290568113 1049.1098535060883 154.74959084764123 1175.1370437964797 505.52586937323213 294.71143123880029 190.15700719878078 319.44076729938388 50.525961507111788 116.77796624228358 11.754059895873068 5.5589670799672595
leaf_count=3750 20142 20297 4447 2148 8788 22465 13138 26057 7122 9704 14546 29031 1442 662 3052 3463 11089 1709 23005 9334 2489 1774 4164 511 1511 90 70
internal_value=0 0.000782868 -0.00105307 -0.0004145 0.00264227 0.00370448 0.00503384 -0.000938357 -0.00127006 -0.00185156 -0.00248107 -0.00140398 0.000733678 0.00646119 0.0078782 0.00712447 0.00381932 -0.000789136 -0.0052698 -0.00690957 0.00895352 0.00793011 -0.00119602 0.00075017 0.0040542 0.0136759 0.0111603
internal_weight=0 15378.1 7735.42 6976.51 7642.66 5838.09 4024.11 6599.38 6380.5 5753.93 4990.32 3413.85 1653.66 3278.12 2131.16 384.495 1146.95 1804.57 2324.25 758.914 1762.74 1468.03 1269.17 1813.98 626.57 97.8419 122.337
internal_count=246000 202853 116789 103705 86064 64058 41082 99258 97110 88407 78703 52646 23615 32294 20453 4905 11841 22006 43147 13084 17401 14912 18710 22976 8703 752 1581
is_linear=0
shrinkage=0.0152673


Tree=96
num_leaves=28
num_cat=0
split_feature=20 21 109 21 20 130 1 21 2 149 21 20 29 411 141 128 155 8 390 7 150 7 118 155 124 152 149
split_gain=393.793 218.72 191.013 126.423 92.5351 65.4823 57.9308 54.6199 47.319 47.2889 46.1774 42.0787 41.8854 38.8462 35.2857 40.6546 41.5583 36.7864 34.5826 33.0781 34.7366 31.0426 30.4779 29.8933 29.6453 44.2601 29.6069
threshold=0.18705904504727433 -0.55092222074356589 -0.58333333333333315 -0.94860626875739484 -1.1812398945549447 0.62500000000000011 1.0000000180025095e-35 0.093766758909517342 1.0000000180025095e-35 -0.21135171585026369 -2.0089485232886477 -2.0097992159524432 0.033950000000000029 1.0000000180025095e-35 0.98148148148148151 1.125689655172414 40370.388750000006 -0.57116836734693865 0.15276444275590673 -0.46140449088760332 0.62422360248447217 -0.47409342539030908 0.19172661870503599 303345.55125000008 2.8750000000000004 0.93750000000000011 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 9 -2 21 10 18 13 -8 19 -1 -11 14 -5 15 16 17 -12 23 -3 -21 -4 -7 -6 -13 -26 -23
right_child=3 2 4 7 6 22 8 -9 -10 11 12 24 -14 -15 -16 -17 -18 -19 -20 20 -22 26 -24 -25 25 -27 -28
leaf_value=0.0083271680166988309 0.0010274604955567001 0.0022083805449589619 -0.0018362231684514701 -0.002250863862992461 -0.005709482252193099 0.0037434262777570147 0.0026291791647829522 -0.0072013702979859887 -0.0025905255307560626 0.019135503411676465 -0.0013547007330971489 0.001247677533652423 -0.0018982061482395889 -0.0067705427919080262 -0.001459178414326573 -0.0014428465655710258 0.010016928269359331 0.0046355980162606789 -0.0020283132591635443 0.0079564766886767915 0.02565812645432184 0.0056273720824357634 0.0088099560191543368 0.0095923433452154289 0.0087399290902654709 0.064016513644433851 0.00055648491317560663
leaf_weight=334.89092513918877 1028.4806686937809 260.27572020888329 400.17458926141262 1655.4063735418022 1569.4365842603147 435.36118583008647 713.94752101972699 1557.8049852214754 933.28037459775805 32.599687241017818 283.13091148436069 1291.0883362852037 459.07671128213406 611.16550262644887 344.11694980040193 301.6758672632277 280.20678329095244 1455.1930529363453 1270.1009277738631 511.37190587818623 27.646561004221439 547.05095457658172 800.89511642605066 29.719086233526468 24.436372254043821 3.8736185804009429 535.39722957834601
leaf_count=2095 12251 2688 4438 29444 28337 4091 9909 38571 14343 198 2604 14558 4478 12777 3347 2761 2066 12896 20685 5069 222 5424 6312 406 291 45 5694
internal_value=0 0.00138806 -0.000122856 -0.0037168 -0.00152357 0.00401306 -0.00261076 -0.00499504 -0.000322577 0.0037787 0.00293014 0.00202805 0.00234804 -0.0034741 0.00308322 0.00376093 0.00454325 0.00365461 -0.00392109 0.00672719 0.00889057 0.00178205 0.00703402 -0.00541822 0.00159558 0.0170207 0.00312825
internal_weight=0 12844.9 8150.4 4852.86 5999.11 4694.55 4516.48 3824.38 1647.23 2151.29 3458.29 1352 3123.4 2266.57 2664.32 2320.21 2018.53 1738.32 2869.26 799.294 539.018 1482.62 1236.26 1599.16 1319.4 28.31 1082.45
internal_count=246000 152957 112307 93043 89236 40650 73680 80792 24252 23071 30247 15092 28152 42221 23674 20327 17566 15500 49428 7979 5291 15556 10403 28743 14894 336 11118
is_linear=0
shrinkage=0.0152673


Tree=97
num_leaves=28
num_cat=0
split_feature=11 130 155 17 125 14 1 166 152 118 390 6 1 144 124 130 111 37 125 43 390 130 14 14 1 390 2
split_gain=260.156 141.92 117.984 98.0173 79.8975 71.7354 89.5736 67.2478 63.3786 60.4025 58.127 44.6061 42.8368 42.3337 41.4931 38.5048 37.9362 37.4399 36.8196 34.1584 34.0062 32.6319 30.9755 28.9037 31.1486 28.7864 28.0431
threshold=1.0000000180025095e-35 1.0000000180025095e-35 33998.602500000008 1.0000000180025095e-35 -0.44592301806447304 -1.0000000180025095e-35 1.0000000180025095e-35 83175.176250000019 4.0625000000000009 -0.10323741007194244 -0.53258004075641796 -0.58470760233918118 1.0000000180025095e-35 0.61607142857142871 1.8750000000000002 2.0416666666666674 14561.370000000001 0.0068500000000000028 -0.14186188546173653 0.18745000000000003 0.2802937305696464 0.79166666666666685 -1.0000000180025095e-35 -1.4999999999999998 1.0000000180025095e-35 0.23771444146488135 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 3 5 10 -2 15 12 13 -3 -1 -8 20 -4 -11 18 19 -5 25 21 -6 26 -14 -12 -25 -7 -13
right_child=2 9 8 17 7 6 11 -9 -10 14 23 16 22 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=-0.0051980499998607061 -0.0032524060670041412 -0.0017890890978076745 0.0071805177282553718 0.0062145529176317821 -0.007002348411075613 -0.0014895479627185953 -0.0019902947201366622 0.0014154334425948607 -0.0022733589490538412 0.0017176044651845588 -0.005642459566460937 0.0052914241101307711 -0.0063170829492957053 0.019761676293331445 0.0080045532885617329 0.0060227990145688961 0.017307815155521857 -0.001289015833867189 -0.0026720616599555823 -0.0048108975784383048 -0.0033484879246894186 0.0089866591433253804 -0.0012045731766679804 0.00045598931454771471 0.0059031054147156746 0.0029690321354674727 0.00080715224724777824
leaf_weight=412.12792231887579 1026.3726285435259 1093.5269100517035 867.41153813898563 1066.0062017329037 1864.2682244628668 646.78577417135239 288.8662951476872 461.6535648368299 158.871766269207 1475.4640118665993 121.99145231768489 832.26808350905776 377.20305179059505 68.15329185500741 295.03415305539966 194.91556112840772 52.152569714933634 179.00754092633724 1456.5412359163165 94.671194110065699 889.32956034690142 317.95999796316028 1056.3119433000684 793.62902779132128 356.38149283453822 702.20586412772536 542.14759466424584
leaf_count=6707 13949 18970 8423 10566 33446 8574 3312 6059 1970 20696 1924 8933 6397 528 3689 2383 583 1947 20034 1234 14730 3502 15806 12174 4715 8299 6450
internal_value=0 -0.00179091 0.00191476 0.00122117 -0.00306665 0.000429209 0.0011679 -0.00409888 0.00659493 0.00102682 -0.000211767 0.00356413 -0.00470909 0.00811084 0.00277121 -0.000528703 0.00444162 0.0051283 -0.000987533 0.00405911 -0.00582592 0.00456122 -0.00255692 0.00139715 0.00215272 0.000824634 0.00352961
internal_weight=0 9196.92 8494.34 7399.9 6332.9 6154.89 5128.51 4648.77 1094.44 2864.03 1684.13 2128.07 4187.11 935.565 1770.5 3000.45 1839.2 1245.01 2805.53 1787.05 2753.6 1692.38 1433.51 1272 1150.01 1348.99 1374.42
internal_count=246000 145313 100687 89766 101958 77253 63304 76438 10921 43355 25520 24014 70379 8951 24385 39290 20702 12513 36907 20119 48176 18885 22203 18813 16889 16873 15383
is_linear=0
shrinkage=0.0152673


Tree=98
num_leaves=28
num_cat=0
split_feature=20 21 411 10 19 21 130 7 8 391 391 6 19 1 143 14 10 8 6 7 7 391 143 19 119 135 118
split_gain=380.824 290.148 117.671 88.746 81.4117 80.0914 71.1982 59.7178 70.8179 65.9027 58.3431 60.0845 47.4292 44.3859 41.2729 38.6859 38.8133 38.3333 38.283 38.2396 38.2246 37.9983 36.7402 35.2484 33.7646 33.004 32.4795
threshold=-0.78572725661621623 -0.55092222074356589 1.0000000180025095e-35 -0.28409559126493605 1.0000000180025095e-35 0.38809800176773507 0.62500000000000011 -0.46140449088760332 1.0000000180025095e-35 -0.80185022711144738 0.12742144408804593 -0.40212197159565571 0.0052888466891881101 1.0000000180025095e-35 3.0555555555555558 -1.0000000180025095e-35 -0.39438263974728743 1.0000000180025095e-35 -0.028517126148705094 0.014554954282515397 0.02326304658829384 -0.92257102786474277 2.6111111111111112 0.19388630579008007 -0.16537544696066744 0.98936816524908877 -0.094604316546762574
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=5 6 3 13 10 7 12 24 9 21 11 -5 15 22 -10 -2 -17 20 -11 -20 -13 -9 -3 -8 -1 -7 -15
right_child=1 2 -4 4 -6 25 23 8 14 18 -12 17 -14 26 -16 16 -18 -19 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0034588890092596856 -0.0027084120577884952 -0.0067433036505299485 -0.0066463767054328942 -0.001229718746505945 -0.0059385223300620479 -0.0019579658903908629 0.0057870395898169799 0.0045962839273222568 0.0022527901671007427 0.0069779174037379772 -0.0027880040190817472 0.0023762457426606612 -0.0037209858183095924 -0.0052371247909499975 0.01152110757000166 -0.0020984372888066751 0.0032721362532157701 0.00039056381218072601 0.0013937311659493645 0.014547331441117493 0.0093320779077240516 -0.0081547991447427273 0.00026262995186816855 -0.0046580989726354889 0.0025476106505937543 0.0092145513274020426 0.001738320220146982
leaf_weight=274.54962211847305 440.20238744467497 1465.5453495532274 1819.2921687625349 981.00904068723321 606.93654016032815 770.04509994760156 1042.113903041929 142.20644655451179 1587.3781326375902 1077.2268645763397 1060.4467547088861 360.1682443395257 508.61954974010587 265.95278692990541 121.03415408730507 383.38001655042171 1679.1080859228969 466.39483550190926 62.548688139766455 341.94069916009903 386.61957646533847 87.945876397192478 195.19222611561418 80.043761409819126 1043.5347700305283 66.60773978382349 371.86271925270557
leaf_count=2791 4899 30900 38067 15049 12454 11158 10807 1166 14459 8035 18238 5145 7420 5361 1047 4721 17103 7235 523 2304 5165 982 3658 1194 8952 881 6286
internal_value=0 -0.00153139 -0.00323243 -0.00222251 -0.000805755 0.0032904 0.00175015 0.00405971 0.00512457 0.00732268 0.000148914 0.00157262 0.000523466 -0.00459841 0.00291605 0.00138995 0.00226929 0.00384603 0.00850332 0.0125376 0.00599115 -0.000239247 -0.00591442 0.00503313 0.00128921 -0.00105556 -0.00115663
internal_weight=0 12112.9 7979.42 6160.13 3861.57 5575.02 4133.47 4738.37 3420.28 1711.87 3254.64 2194.19 3011.31 2298.55 1708.41 2502.69 2062.49 1213.18 1481.72 404.489 746.788 230.152 1660.74 1122.16 1318.08 836.653 637.816
internal_count=246000 193702 147558 109491 63286 52298 46144 40259 28516 13010 50832 32594 34143 46205 15506 26723 21824 17545 10862 2827 10310 2148 34558 12001 11743 12039 11647
is_linear=0
shrinkage=0.0152673


Tree=99
num_leaves=28
num_cat=0
split_feature=20 19 10 20 19 391 391 7 8 140 391 391 391 391 119 119 109 19 391 7 8 10 109 130 11 128 1
split_gain=373.877 164.404 145.479 117.037 87.0326 82.0162 105.875 79.8286 65.4062 61.2593 61.1966 113.594 51.1146 50.5299 49.0398 47.7629 42.3846 41.2368 40.8433 35.7938 64.712 36.0633 35.1032 33.3129 32.6012 32.5732 32.2273
threshold=0.18705904504727433 0.036948907581812025 -0.58254360664743843 -1.055547744992388 -0.25593239003289309 0.12742144408804593 1.0000000180025095e-35 -0.63009267898239707 1.0000000180025095e-35 -0.14108910891089108 -0.66068996828538784 -0.63378138164839226 -0.035868283237475519 -0.80185022711144738 -1.0000000180025095e-35 -0.083730631704410002 1.4166666666666667 0.14515642090416706 1.4004253102747959 -0.44772034583566583 1.0000000180025095e-35 0.79913473423980241 -0.41666666666666657 0.79166666666666685 1.0000000180025095e-35 0.46224137931034487 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 14 13 -2 6 7 -5 25 15 -9 22 -13 -4 -1 -6 -17 24 19 -15 21 -21 -12 -3 -11 -8 -16
right_child=4 23 3 5 9 -7 8 10 -10 17 11 12 -14 18 26 16 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0047402465943291007 0.00435760523015747 -0.0045902756910880717 -0.001119560804952387 -0.0023254988919075873 -0.0051914907672103014 -0.0010566468850279555 0.012725333494223544 -0.0015612119480558032 0.00069822998450420415 -0.0064745964591937611 0.020267196784649836 0.0033896502860221987 -0.0062569328335330757 0.0031976853366413784 -0.0014813095918154186 -0.00089098477250194972 0.011517712141654314 -0.01036315258777481 -0.0056555649595979082 0.011187519344361595 0.0043264205994967622 0.0041106113839364054 0.0091111230110164903 0.00039611834963001704 -0.0027471164229933859 0.0038250241236368896 0.0042232179684343809
leaf_weight=797.87632202729583 296.62888257205486 1161.7500763088465 271.61290247365832 894.53666273504496 708.02325081825256 1932.5164837650955 422.00967589393258 547.70067209005356 215.47656482830644 1290.187983982265 96.610042665153742 1585.0736143253744 138.49106165766716 774.29251604154706 766.35482795536518 1113.175519540906 67.862839054316282 377.1067395620048 70.60532645881176 834.29074903205037 1026.2587224990129 216.11068814992905 226.36893865838647 422.55998915806413 969.65966947749257 128.43814906105399 329.8405889198184
leaf_count=13011 3793 18886 2443 11302 15015 26071 4073 7046 2454 27282 953 17627 1932 6345 10412 20045 1036 8885 622 5928 8714 1370 2272 6305 16987 1320 3871
internal_value=0 0.00134803 0.00199567 0.00277535 -0.00363661 0.00154804 0.00273325 0.00160128 0.00787563 -0.00416273 0.00295891 0.0041731 0.00260858 0.00515034 -0.00186074 -0.00205626 -0.000168393 -0.00566803 0.00573641 0.00602213 0.00707042 0.00974129 0.012487 -0.00325466 -0.00487964 0.0106674 0.000227261
internal_weight=0 12858.8 11274.5 9380.39 4822.64 6187.22 4254.71 3488.78 765.924 4526.02 2594.24 2046.54 1723.56 3193.17 1894.07 1889.06 1181.04 2636.95 2921.56 2850.95 2076.66 1050.4 322.979 1584.31 2259.85 550.448 1096.2
internal_count=246000 152957 127766 100472 93043 75050 48979 41132 7847 89250 29830 22784 19559 25422 27294 36096 21081 53154 22979 22357 16012 7298 3225 25191 44269 5393 14283
is_linear=0
shrinkage=0.0152673


Tree=100
num_leaves=28
num_cat=0
split_feature=20 19 10 411 135 7 8 6 19 140 7 391 143 171 19 118 109 1 112 19 172 391 388 10 143 261 11
split_gain=363.36 159.451 140.802 117.941 100.603 98.75 136.626 95.42 84.6665 60.0391 47.7081 47.6865 46.8618 41.6147 40.7676 39.3089 39.7855 39.2836 38.3733 37.6007 37.1712 37.0784 34.6277 33.7982 33.0992 32.5937 32.0185
threshold=0.18705904504727433 0.036948907581812025 -0.58254360664743843 1.0000000180025095e-35 0.47174969623329294 -0.44772034583566583 1.0000000180025095e-35 -0.017790309106098575 -0.25593239003289309 -0.14108910891089108 0.0055980593394289986 -0.80185022711144738 3.1666666666666674 -3.7499999999999996 0.14515642090416706 0.3140287769784173 1.4166666666666667 1.0000000180025095e-35 -0.55432517322474217 -0.3376378893188533 -27.249999999999996 -0.92257102786474277 -0.74057845158849911 0.84308474110699094 2.0555555555555558 12.875000000000002 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 12 4 5 -4 7 11 -2 15 -9 21 17 -6 26 -10 -17 -1 -12 -5 -15 -7 -14 -22 25 -3 -11
right_child=8 24 3 19 13 6 -8 10 9 14 18 -13 22 20 -16 16 -18 -19 -20 -21 23 -23 -24 -25 -26 -27 -28
leaf_value=-0.0040786715954318252 0.0042759463009629265 -0.0044379628155413351 -0.00067831546579624736 0.0083266173361996616 0.0013405151083897208 0.0033577599205488222 0.001123617970780009 -0.00098024780770202056 -0.0035225456724427484 -0.0064129086840636175 0.025275406481722822 0.0060246539921948623 0.041235180263139957 -0.00025434458653296704 -0.010302064994805085 0.00024538435712367061 0.017621814997307573 0.0010600610682281887 0.012132380117816569 -0.001504534729341394 0.0093259011954479557 -0.007512714651858556 0.0041664088986984055 0.0021480029957813909 0.0025012550701758881 0.010882382061964213 -0.0027116636029103284
leaf_weight=1226.991961337626 297.67417035251856 1343.6577469296753 1597.410147421062 95.795394241809845 289.60098296403885 199.39072269946337 2226.8508669510484 54.741571806371212 1293.0609712935984 1282.770690523088 61.719154912978411 1267.0137461125851 5.9557106643915168 123.6067564971745 373.57961914688349 560.15407934784889 32.377531263977289 479.68428579717875 392.35221701860428 1581.7710931189358 1213.1665541119874 115.00951700285077 178.41653824225068 179.03809791058302 203.63931856304407 32.648590367287397 967.35996394231915
leaf_count=18889 3793 21855 17772 829 3025 2107 26006 601 26343 27282 508 11757 65 1315 8885 9315 438 6160 3223 19559 10853 1561 2180 1356 2950 386 16987
internal_value=0 0.00132634 0.00196265 0.00272791 0.00352545 0.00255986 0.00376015 0.00656425 -0.00359302 -0.00411467 0.0123254 0.00470353 -0.00183535 0.00668299 -0.00561006 -0.00202868 0.00121596 -0.00262904 0.0139493 -0.000936753 0.00769734 -0.000591856 0.00545684 0.00840984 -0.00321385 -0.00406635 -0.00482615
internal_weight=0 12868.5 11288.5 9397.47 7719.9 5914.49 4317.08 2090.23 4806.98 4509.3 508.813 1581.41 1891.05 1805.41 2623.71 1885.59 592.532 1706.68 454.071 1677.57 1515.81 314.4 184.372 1392.2 1579.95 1376.31 2250.13
internal_count=246000 152957 127766 100472 80084 63535 45763 19757 93043 89250 4332 15425 27294 16549 53154 36096 9753 25049 3731 20388 13524 3668 2245 12209 25191 22241 44269
is_linear=0
shrinkage=0.0152673


Tree=101
num_leaves=28
num_cat=0
split_feature=20 19 20 20 19 130 155 141 149 130 387 128 19 392 140 7 122 90 154 118 152 111 109 154 7 7 119
split_gain=354.247 127.397 110.06 102.909 93.3789 85.614 84.3559 87.5561 77.7702 66.2093 59.7542 50.2921 48.7496 46.5336 38.569 36.3906 35.433 35.2149 34.871 34.2235 33.7784 37.5427 29.2802 29.1993 28.6978 28.3728 27.7016
threshold=-0.23944851334767706 0.066137329671330417 -1.6973680938911146 0.51688161336547822 -0.31528071226839544 0.37500000000000006 35028.247500000005 -0.16666666666666663 -0.58342319933459807 2.0416666666666674 -1.0000000180025095e-35 1.0000000180025095e-35 0.018489692726097188 -0.2309616026761426 -0.012376237623762375 -0.46140449088760332 0.32758620689655177 -1.0000000180025095e-35 0.35714285714285715 -0.0075539568345323735 3.6875000000000004 3268.9125000000004 -0.24999999999999997 2.0714285714285716 -0.49126080736455802 0.064564284381414455 0.72377830750893934
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=2 3 16 5 25 8 7 12 20 15 24 -8 14 -7 18 -9 -1 -15 -6 -12 21 -2 -16 -13 -10 -4 -5
right_child=1 -3 4 26 6 13 11 9 10 -11 19 23 -14 17 22 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.007551318675706244 0.0037983701208848786 -0.0063251659626621668 0.0049055525473576753 -0.0065990089832236379 0.0072100615502482049 -0.00055456638012613135 0.0080961879362388516 -0.0047862843249767669 -0.0040075516862258624 0.0052600818563203035 -0.0066267861587600433 0.0058986659857708686 -0.0032378882503255346 -0.00052054918288044975 0.0037147920836275426 -0.0010183561237631592 0.0018604921958496887 0.0063887024078392897 -0.0010466421659639986 -0.0025716449892847714 -0.0033534939168727131 0.018273886860910381 -0.00035781395368254993 -0.0030048732620285034 0.00061489602730390846 0.012536390330997028 -0.0010206985535998058
leaf_weight=1018.7442178241909 445.99414974451065 1455.9773555807769 305.46953785419464 965.45533928647637 677.0397214256227 677.96798929572105 565.27743148431182 817.07138499617577 404.29226990416646 320.62887609004974 842.62974908575416 147.58424508944154 323.23982552066445 224.71955277770758 827.9483311958611 2258.4694518707693 346.55185455083847 699.92547531053424 142.3670132085681 1170.7915722504258 136.61369422823191 46.457460723817348 810.41394134610891 203.74380894005299 1377.5935182273388 187.38003105297685 269.56524979323149
leaf_count=7267 6626 31261 2435 20265 6679 11501 5114 10499 5933 3565 16833 1333 4680 3455 8498 27316 2512 9623 1427 18964 2288 632 9016 2145 19776 1483 4874
internal_value=0 -0.00220195 0.00212179 -0.00137387 0.001402 -0.000549389 0.000953959 0.000310988 -0.00164577 -0.00133208 -0.00247124 0.00527605 0.00232075 0.00247153 0.00305574 -0.0020226 0.00611401 0.00469987 0.00576443 -0.00427379 0.00331914 0.00518944 0.00169489 0.000710453 -0.000429083 0.00782926 -0.00538922
internal_weight=0 8717.98 8951.93 7262.01 7586.63 6026.99 7093.78 6177.18 4424.37 3396.17 3795.31 916.605 2781.01 1602.61 2457.77 3075.54 1365.3 924.645 819.407 2013.42 629.065 492.452 1638.36 351.328 1781.89 492.85 1235.02
internal_count=246000 152031 93969 120770 84190 95631 80272 71680 71052 41380 61506 8592 30300 24579 25620 37815 9779 13078 8106 35797 9546 7258 17514 3478 25709 3918 25139
is_linear=0
shrinkage=0.0152673


Tree=102
num_leaves=28
num_cat=0
split_feature=20 1 391 2 392 135 19 411 140 130 141 10 19 119 7 8 158 19 149 149 139 389 7 8 143 20 391
split_gain=344.839 153.452 132.356 120.216 119.414 96.1451 82.0046 59.1443 58.7934 47.927 47.5567 57.0767 46.8604 46.0862 45.4809 48.4419 41.4529 39.9802 37.2822 35.1892 38.5935 34.6107 34.5392 58.0879 33.426 32.623 31.5965
threshold=0.18705904504727433 1.0000000180025095e-35 -0.81178185562575544 1.0000000180025095e-35 0.2600851730102921 0.6783110571081411 -0.25593239003289309 1.0000000180025095e-35 -0.14108910891089108 0.95833333333333337 0.16666666666666669 0.83017442658975427 0.19388630579008007 -0.083730631704410002 -0.2332524724762082 1.0000000180025095e-35 178.65000000000003 0.14515642090416706 -0.27498209239536847 -0.55593076250974105 0.44343181078167077 1.0044877317300249 -0.55072463768115931 1.0000000180025095e-35 2.1666666666666674 -1.4667066540297049 -0.93013883649556617
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 26 10 5 12 -2 19 13 21 11 22 14 -8 -4 -16 -7 -10 -15 -6 -21 25 -3 -24 -20 -5 -1
right_child=6 3 4 9 7 16 8 -9 17 -11 -12 -13 -14 18 15 -17 -18 -19 24 20 -22 -23 23 -25 -26 -27 -28
leaf_value=-0.0017800850237585839 0.0042185118213404638 0.0038037779597581709 -0.0035937246046169702 0.0057096892267818116 0.0088995402630527073 0.0019580567939692251 -0.0050644252913669453 -0.0011173349065494451 -0.0047423563711826867 0.0053022063686879155 0.0026488094571932019 0.0011866419399243519 -0.0071332960210645753 0.0044538019096432473 0.0054717070370954761 -0.00095271473618620077 0.010141164461198679 -0.010203048619042487 -0.0033507386750247295 0.0048648907120963135 -0.00051090808557324155 -0.0040627975767028044 0.012955470887465173 0.0057514693595912166 0.0038010781723799014 1.476807840600271e-05 -0.0090730797477770291
leaf_weight=209.64966532215476 298.3917677141726 283.28488723188639 1325.9975928887725 283.42799253761768 345.21320850402117 664.94121268391609 700.51120668277144 569.15167617052794 2234.9279263094068 500.76160445436835 761.45825553312898 297.62149956822395 363.1104383841157 306.96394134685397 320.49000496044755 1861.7846378274262 185.8121105208993 367.98209182173014 674.47221146523952 1232.3282289281487 412.43311149254441 389.13110517337918 613.08622161671519 465.63813652843237 195.53076777607203 1371.4607447311282 429.00092794746161
leaf_count=2582 3793 2956 18419 1981 3152 8143 15015 6812 44269 5407 8259 2361 6499 5191 3715 25921 1760 8885 12523 11898 4270 4572 5404 5039 3367 16815 6992
internal_value=0 0.0012876 -3.0526e-05 0.0033916 0.000552905 -0.000884919 -0.00351415 0.00320944 -0.00403135 0.00107006 0.00582769 0.00728018 -0.00190774 -0.00196421 -0.0013639 -4.60856e-06 0.00375805 -0.0055186 -0.000110685 0.00445153 0.00351141 2.83292e-05 0.00860463 0.00985595 -0.00173236 0.000996227 -0.00669466
internal_weight=0 12885.8 7919.91 4965.87 7281.26 4722.14 4778.78 2559.13 4480.39 2544.78 2421.09 1659.63 3871.38 1877.48 3508.27 2182.27 850.753 2602.91 1176.97 1989.97 1644.76 2044.02 1362.01 1078.72 870.003 1654.89 638.651
internal_count=246000 152957 100163 52794 90589 64457 93043 26132 89250 28775 24019 15760 54554 36096 48055 29636 9903 53154 21081 19320 16168 23368 13399 10443 15890 18796 9574
is_linear=0
shrinkage=0.0152673


Tree=103
num_leaves=28
num_cat=0
split_feature=21 19 21 14 409 7 8 19 11 7 391 135 140 19 52 141 164 391 391 391 390 387 129 135 164 19 113
split_gain=357.596 182.697 143.977 101.699 91.4345 62.8706 66.93 58.7752 55.1091 47.8844 47.6025 46.2329 40.2083 36.7243 36.5286 37.5812 34.59 33.1575 33.7123 36.3596 32.4339 32.2197 32.041 38.3837 30.0243 28.8153 28.7017
threshold=0.1746120078555157 1.0000000180025095e-35 -1.3229527277820539 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.46140449088760332 1.0000000180025095e-35 0.10232330998452184 0.37211221122112215 0.028239099334452948 -0.66068996828538784 0.47174969623329294 0.056930693069306933 -0.35101553262171653 3.5000000000003335 0.16666666666666669 928.42875000000015 -0.85064882944034903 -0.63378138164839226 -0.6485657192683002 -0.29304884983576107 1.6011447728316155 -0.58203222617731687 0.48754556500607543 39122.122500000005 -0.37481395413786084 9.357332671670493
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 14 25 13 12 9 8 16 -7 -11 -3 -6 -5 15 21 20 -15 19 -19 -2 -1 -20 -24 26 -4 -8
right_child=7 11 3 4 5 6 24 -9 -10 10 -12 -13 -14 17 -16 -17 -18 18 22 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.0082902228120452972 -0.0071436059893420761 -0.0042695826907127839 0.011195571085178518 0.0086128998338793651 0.0026288197842739133 0.0042133630338496856 0.00030323668579371611 -0.0082674874182882899 0.00020130853101695158 0.00227616967891394 0.011893014756439575 0.0010624762017282545 -0.0029267706484634322 -0.0056433083918053292 0.001392899190929804 0.0032675448703936806 0.00077796108901772134 0 0.0050840281625166789 0.012755149145412167 -0.0034585952618716373 -0.0019254230864397153 -0.0021712484970721501 0.0021525845603972919 0.0072195680767150501 -0.0034634540126137784 0.0065337557053715845
leaf_weight=1213.3631673529744 887.35159754753113 1564.1245118975639 31.645279966294765 105.3236637301743 688.24359462782741 944.90691476687789 1203.3810250796378 615.99754694104195 863.3246878311038 160.72449257224798 505.38755501434207 496.82012360915542 542.74811084195971 271.15958219021559 474.17924832552671 701.36077047139406 285.9713386259973 115.90312535315752 217.31919075921178 95.716593448072672 1543.5931926593184 74.9038922265172 1807.7998157739639 648.78039408102632 225.56770037859678 1172.1988438218832 201.72288810089231
leaf_count=8608 19373 25848 282 888 7714 9580 15211 14950 14731 1837 4554 7284 6228 4003 3773 5397 5206 1501 2686 1003 31279 607 25140 7886 2345 15672 2414
internal_value=0 0.00120152 0.00195813 0.00105608 0.00169932 0.00311702 0.00423252 -0.00390274 -0.00314879 0.00644211 0.00958772 -0.00297979 0.000171825 -0.000241814 0.00522661 0.00613545 -0.00421662 -0.000540684 -5.76446e-05 0.00580178 -0.00480796 0.00768894 -0.0005252 -0.00102552 0.00204342 -0.00306871 0.00120504
internal_weight=0 13463.3 11402.3 8938.53 7734.68 4472.68 3241.69 4196.24 3580.24 1611.02 666.112 2060.94 1230.99 3262 2463.81 1989.63 2716.92 3156.68 2885.52 211.62 2430.94 1288.27 2673.9 2456.58 1630.67 1203.84 1405.1
internal_count=246000 160461 127329 108944 92990 49883 35941 85539 70589 15971 6391 33132 13942 43107 18385 14612 55858 42219 38216 2504 50652 9215 35712 33026 19970 15954 17625
is_linear=0
shrinkage=0.0152673


Tree=104
num_leaves=28
num_cat=0
split_feature=20 19 20 164 387 391 119 7 8 20 391 6 19 143 391 154 164 141 111 391 391 390 8 388 150 387 49
split_gain=335.246 168.269 133.851 114.284 94.6334 72.6482 68.2071 65.6885 66.267 62.6717 61.9923 57.2102 54.4818 51.4051 48.6614 47.816 43.8508 44.0601 41.036 34.5466 50.1901 30.9527 42.1313 29.6547 28.6994 28.3149 27.4643
threshold=-0.78572725661621623 0.13144353264597256 0.47283405551091923 36029.92500000001 -0.085097128818110032 -0.80185022711144738 -0.1272348033373063 -0.43328979287180441 1.0000000180025095e-35 -1.8843834570786695 -0.63378138164839226 -0.0083500417710944009 1.0000000180025095e-35 2.6111111111111112 -0.93013883649556617 4.5000000000000009 10580.411250000003 -0.055555555555555546 1890.5850000000003 0.12742144408804593 0.032076008662947908 -0.50794380043825382 0.51063775510204101 -0.74057845158849911 0.25042348955392441 0.77127500994991716 0.012250000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=5 2 3 4 7 14 -6 -2 11 25 -11 -9 16 18 -1 -5 17 19 21 20 -12 -8 -23 -15 -18 -7 -13
right_child=1 -3 -4 15 6 9 13 8 -10 10 12 26 -14 23 -16 -17 24 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.002841289024608235 -0.0022416497926094027 -0.0065500637870234066 -0.0048440136659632961 0.0064546099896347379 -0.0047564724176801573 0.0092979805431428371 -0.0049537944954238132 0.00328639682475416 0.00023006371740635304 0.0089901682847356567 0.003719589780016888 0.013327592675894147 -0.0024147486562653589 0.043168585481215972 -0.006691843103843742 -0.00046757511393526625 0.0028311022170196759 0.00039648837562515871 0.0047096074704858302 0.00093428908252320435 0.011262858747521446 0.00046629314502000805 -0.0047567551717273455 0.0052287390823431293 0.010185921110030857 0.00013646656751819798 -0.0013311951188665426
leaf_weight=222.94104511663318 962.70942605659366 1339.521946746856 1624.7288351356983 804.52065240964293 1580.4492456279695 566.43512181192636 617.48346683010459 858.63869558274746 1409.6835691556334 365.68642369657755 824.39882278069854 229.76195831224322 477.90018194913864 4.7920596860349169 280.53676360845566 323.76337993890047 214.96046220511198 1432.0451443865895 231.90845460444689 554.95622707903385 277.110297344625 1292.9992766827345 497.38950337842107 226.32268974930048 305.49835489317775 93.674485385417938 32.901484187692404
leaf_count=1987 12839 28427 33110 8874 29642 3731 10223 10353 20058 2844 7102 2430 6065 64 3476 4448 1930 14615 3037 5603 2066 18529 8205 3104 2179 700 359
internal_value=0 -0.00144832 -0.000808551 -8.48343e-05 -0.000731561 0.00306885 -0.00220838 0.00114746 0.00244027 0.00361448 0.00296012 0.00521021 0.0024179 -0.000802213 -0.00245291 0.00446043 0.00306048 0.0023649 -0.00140966 0.00406085 0.00562729 -0.00200317 -0.00097998 0.00609165 0.00716807 0.0080122 0.011457
internal_weight=0 12037.6 10698.1 9073.32 7945.04 5616.14 4451.34 3493.7 2530.99 5112.67 4452.56 1121.3 4086.87 2870.9 503.478 1128.28 3608.97 3088.51 2639.78 1656.47 1101.51 2407.87 1790.39 231.115 520.459 660.11 262.663
internal_count=246000 193702 165275 132165 118843 52298 72804 46039 33200 46835 42404 13142 39560 43162 5463 13322 33495 29386 39994 14771 9168 36957 26734 3168 4109 4431 2789
is_linear=0
shrinkage=0.0152673


Tree=105
num_leaves=28
num_cat=0
split_feature=21 20 21 20 414 10 143 20 149 7 171 127 19 157 130 1 130 14 120 8 6 416 19 261 67 21 7
split_gain=343.889 202.536 139.775 96.345 85.3524 54.2724 50.6848 50.6153 50.321 49.2999 45.8005 41.8645 41.7293 40.689 38.4713 38.3845 37.355 33.8449 31.9736 31.8611 30.7518 30.1285 29.3959 29.055 28.436 28.095 26.5744
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 -1.126355914706455 -1.0000000180025095e-35 -0.5021975003433593 3.0555555555555558 0.46193093371152166 -0.013124371921925478 -0.44772034583566583 2.7500000000000004 -0.61504863766152051 0.0028346554504373738 191.25000000000003 0.62500000000000011 1.0000000180025095e-35 2.8750000000000004 -1.0000000180025095e-35 0.56078610603290679 0.022515306122448984 -0.0083500417710944009 -1.0000000180025095e-35 -0.37481395413786084 9.6250000000000018 1.0000000180025095e-35 -2.0621762643796608 -0.46140449088760332
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 14 -2 22 18 8 13 9 -1 19 -7 16 15 25 -5 17 -13 -6 20 -11 23 -4 -17 -10 -3 -19
right_child=3 2 4 7 5 11 -8 -9 24 10 -12 12 -14 -15 -16 21 -18 26 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0014780559128079618 0.0013309182524939291 0.0074132287730482175 0.0098651304764171711 -0.0056358300994879089 -0.0043563763113827645 0.0054286050158781586 0.0096807200277001185 -0.0087330043472609933 0.00082792231894377789 0.0073655583794225259 0 -0.0038643299113326041 -0.0040667698735123072 0.007423921180182186 0.0067693946416636959 0.0017623108936081202 0.0083158724535846457 -0.0017171286634418243 0.0022324535127896871 0.0044451647832267436 0.014101996256201224 -0.0034092010941945924 -0.0043958891551363274 0.032707738193346728 0.0059909290258714975 0.001119313865570512 0.0020969245132997868
leaf_weight=765.25720417499542 697.01654613763094 192.35837277024984 33.768444750458002 1766.223361056298 930.80710236355662 386.05884963274002 304.52588848769665 649.53886315226555 1869.247286926955 655.47403654828668 239.78838469460607 370.127147924155 475.21467100083828 70.240852668881416 547.98901799693704 241.35435830801725 147.04429997503757 570.07194428145885 208.35892242193222 608.16793592274189 214.89543862268329 743.95144435763359 1788.9537703357637 7.141781657934188 288.00785245746374 1216.7027910798788 1659.1823098249733
leaf_count=6460 9050 1517 335 38927 16294 5051 2414 17353 16278 4703 1995 5248 8718 1232 4804 4392 1833 7651 3340 5149 1421 14466 31418 119 2436 11749 21647
internal_value=0 0.00117534 -0.000249295 -0.00383923 -0.00131719 -0.000236746 0.00363342 -0.00487789 0.00323423 0.0047176 0.00615466 0.000678526 0.000106164 -0.00398893 0.00333059 -0.00428336 0.000831787 0.000404289 -0.00314303 0.00715833 0.00904217 -0.00186654 -0.00412561 0.0027141 0.00152196 0.00198596 0.00111741
internal_weight=0 13472 8526.64 4175.47 6569.59 4746.87 4945.36 3478.45 4640.84 2483.58 1718.33 3607.7 3221.64 2828.91 1957.05 2758.67 2746.43 2599.38 1139.17 1478.54 870.369 992.448 1822.72 248.496 2157.26 1409.06 2229.25
internal_count=246000 160461 119605 85539 101535 69782 40856 76489 38442 19728 13268 50148 45097 59136 18070 57904 36379 34546 19634 11273 6124 18977 31753 4511 18714 13266 29298
is_linear=0
shrinkage=0.0152673


Tree=106
num_leaves=28
num_cat=0
split_feature=21 20 21 20 411 128 391 392 20 19 7 64 19 168 130 165 7 119 135 13 112 165 0 21 409 111 130
split_gain=334.335 195.827 135.391 94.0591 90.8559 74.1528 52.8112 70.211 49.8994 47.9363 42.4934 41.2046 40.5307 37.2075 36.9765 36.0872 31.8754 31.2211 28.3677 27.8377 27.1835 26.2322 25.6885 25.3914 25.3172 29.8576 25.0609
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 -1.126355914706455 1.0000000180025095e-35 0.3172551724137932 -0.84913404291403738 0.13217439859692007 0.46193093371152166 0.039544982278674708 -0.44772034583566583 5.3281250000000115 -0.25593239003289309 1.0000000180025095e-35 0.62500000000000011 19410.075000000001 -0.19593207688001488 0.56168057210965439 0.86482381530984209 1.0699117618539711 -0.66228577742001671 20589.255000000001 1.0000000180025095e-35 -2.0621762643796608 -1.0000000180025095e-35 44823.375000000007 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 9 14 -2 5 6 -4 13 12 10 18 17 26 16 20 -14 -8 24 -1 -19 -3 -15 -6 -22 25 -12 -5
right_child=3 2 4 8 22 -7 7 -9 -10 -11 11 -13 15 21 -16 -17 -18 19 -20 -21 23 -23 -24 -25 -26 -27 -28
leaf_value=0.00078151879681607681 0.0013091649680469605 0.0098760071535314697 -0.0053669523424466079 0.00053223989403321248 -0.0038412317181993148 -0.0031087358260759755 -0.0038445842095795576 0.0041008258866348391 -0.0086697088168526323 -0.0013550792000008925 0.0021557866765630853 0.00056479011819138085 -0.0049602114975539364 -0.010212839839554913 0.0066338805179295282 0.0010117626089017585 0.00046340703455182959 0.0073930644429718029 0.0072423969792746743 0.018261212506948062 0.0067756247165669647 0.0088583585858257371 -0.0099214141427484241 0.00053484271875487853 0.0059758088877880844 0.039214999992100097 0.01617566776282927
leaf_weight=1128.0398612134159 697.77732907235622 94.354584857821465 287.26528263837099 120.06901013478637 1299.5814832933247 1549.4745262786746 630.16009506955743 1358.7638700157404 644.33343311026692 418.88438301533461 756.71635115891695 433.02822604775429 2410.0491888448596 18.482032861560583 550.62942481040955 258.60633246228099 1088.80228452757 719.88087271526456 185.10296703130007 60.909931976348162 175.98509518802166 141.24874744564295 187.96495201438665 1140.7010607235134 1249.3384245187044 4.9350330382585517 30.031928136944771
leaf_count=9750 9050 804 4550 1893 23357 23563 10208 16934 17353 4718 6586 3556 51940 273 4804 4841 17338 5143 1329 418 1391 1723 3589 11071 9319 37 462
internal_value=0 0.00115668 -0.000245607 -0.00379401 -0.0012987 -0.000323995 0.00089769 0.00145669 -0.00482491 0.00356971 0.00402636 0.00497058 -0.00394223 -0.000451039 0.00327209 -0.00437803 -0.00111081 0.00565058 0.00170019 0.00825708 0.00195297 0.00658439 -0.00461691 0.00137683 0.0046333 0.00241816 0.00374046
internal_weight=0 13480.2 8523.41 4160.87 6561.74 5074.2 3524.72 3237.46 3463.09 4956.84 4537.95 3224.81 2818.76 1878.69 1961.67 2668.66 1718.96 2791.78 1313.14 780.791 1411.04 159.731 1487.55 1316.69 2010.99 761.651 150.101
internal_count=246000 160461 119605 85539 101535 74589 51026 46476 76489 40856 36138 25059 59136 29542 18070 56781 27546 21503 11079 5561 13266 1996 26946 12462 15942 6623 2355
is_linear=0
shrinkage=0.0152673


Tree=107
num_leaves=28
num_cat=0
split_feature=21 20 21 20 411 135 390 20 141 155 36 1 1 149 119 165 124 14 52 7 13 141 416 261 154 21 141
split_gain=325.034 189.372 131.158 91.8202 88.5886 52.2737 51.3131 49.1876 48.9383 47.6787 42.8694 39.6093 39.1976 38.9546 37.2756 34.0217 33.3634 33.0424 32.6065 31.5503 31.0285 30.5689 29.9861 28.7307 28.5529 28.3626 28.2362
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 -1.126355914706455 1.0000000180025095e-35 0.457168894289186 0.2683214061971631 0.46193093371152166 -0.27777777777777773 181596.39750000005 0.0015999999999999905 1.0000000180025095e-35 1.0000000180025095e-35 -0.32493840571154203 0.78933253873659137 263242.77750000003 -1.0000000180025095e-35 -1.0000000180025095e-35 9.5000000000010001 -0.44772034583566583 1.1211092795500825 0.16666666666666669 -1.0000000180025095e-35 9.6250000000000018 2.0714285714285716 -2.0089485232886477 0.42592592592592599
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 17 26 5 6 11 12 10 14 16 -4 -5 -8 19 -7 20 -3 21 -10 -1 25 23 -14 -18 -19 -2
right_child=3 2 4 7 -6 15 13 -9 9 -11 -12 -13 22 -15 -16 -17 24 18 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0041779826461231812 0.0034315944958772404 -0.00097822044753115441 -0.0042121387226377845 -0.0052512620585361165 -0.0045650427767743888 0.0018226692210682473 0.0047410965833095736 -0.0086064156504697033 -0.002011591221341983 0.0099136828018955292 0.00023147395965381168 -0.00016977599107832129 0.0020845437479877021 -0.00062890311916370884 0.0053462325326832441 0.013678480248856666 0.010742979344285834 0.012638503330209659 -0.0014039532586691791 0.0020205107952537276 0.015162393018905243 0.0020596336276991704 -0.0030092579442888021 0.032071403234541218 0 0.0054279910321936254 -0.0031025489438506835
leaf_weight=1048.3480784632266 470.7762896232307 355.2854675874114 1416.7711293511093 1796.84942285344 1481.5714881271124 1183.3663646429777 456.06010474637151 639.20337621495128 623.03592920675874 179.05211264267564 320.64223843067884 947.79730286821723 247.04938201978803 1009.1276730783284 549.37748061865568 59.395172122865915 482.22264540195465 158.26490979641676 211.70417495444417 1636.0490867905319 64.243377521634102 526.39709759131074 757.30668253824115 7.546210501343011 64.922759931534529 714.53174308314919 227.75000305846334
leaf_count=8385 5944 3455 23714 39764 26946 16040 6038 17353 5786 1297 2675 13753 4488 14364 4281 680 3347 1172 2051 14121 496 4926 14762 122 468 6466 3106
internal_value=0 0.00113833 -0.00024202 -0.00374914 -0.00128053 -0.000319245 -0.00120372 -0.00477225 0.00350749 0.0022682 0.00537198 -0.00259585 -0.00389587 0.00103675 0.00177684 0.00239877 0.0063594 0.00321487 0.00414535 0.000904358 0.00482309 0.00499161 -0.00147947 0.00303378 0.00946376 0.00674857 0.00128779
internal_weight=0 13488.2 8520.27 4146.48 6554.09 5072.52 3829.76 3447.96 4967.89 2987.51 1980.38 2364.57 2808.75 1465.19 2808.46 1242.76 1659.74 1966.18 1610.9 2259.09 1112.59 1399.19 1011.9 254.596 547.145 872.797 698.526
internal_count=246000 160461 119605 85539 101535 74589 57869 76489 40856 25485 15371 37467 59136 20402 24188 16720 12696 18070 14615 19907 8881 12564 19372 4610 3815 7638 9050
is_linear=0
shrinkage=0.0152673


Tree=108
num_leaves=28
num_cat=0
split_feature=21 20 21 20 128 414 10 20 143 141 391 391 90 171 19 36 0 391 391 165 164 21 130 110 130 124 141
split_gain=315.993 183.126 127.043 89.6217 81.4569 66.4804 53.0317 48.4781 48.1911 53.1563 42.1505 54.0508 58.5368 44.3508 39.3566 37.8565 36.6342 40.3278 43.7225 35.3937 31.7184 32.7612 30.543 30.0484 28.0328 27.464 27.3468
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 -1.126355914706455 0.40982758620689658 -1.0000000180025095e-35 -0.5021975003433593 0.46193093371152166 3.0555555555555558 -0.27777777777777773 0.12742144408804593 -0.82711714898909583 -1.0000000180025095e-35 -2.2499999999999996 -0.25593239003289309 0.0015999999999999905 1.0000000180025095e-35 0.12742144408804593 -0.8538437260486903 19410.075000000001 171427.09500000003 -0.99172777905286968 0.62500000000000011 -3928.1624999999995 1.9583333333333337 -1.0000000180025095e-35 0.42592592592592599
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 16 26 5 -4 24 14 9 15 11 -8 -13 -14 -5 23 17 18 -3 -16 21 -11 -20 -1 -7 -25 -2
right_child=3 2 4 7 -6 6 10 -9 -10 20 -12 12 13 -15 19 -17 -18 -19 22 -21 -22 -23 -24 25 -26 -27 -28
leaf_value=-0.0014625220727312925 0.0033697368872851459 -0.002925777718773441 -0.0032292228216088733 0.003714052357227667 -0.0039138560172959254 -0.0041062591764349675 -0.0038710417223606118 -0.008543130144812618 0.0093094010900494021 0.0037399227165752892 -0.00075344443051170206 -0.00075830419801314311 -0.0023568200708734581 0.0071823051906789431 -0.0048631720615606288 9.7872988691047449e-05 -0.0033715434575963305 0.00075197247178261011 0.004840474757293883 0.0010606510200360743 0.0081848980797109578 7.3570655962689455e-05 0.010664215370188836 0.0051070477423103494 0.0023268977221266151 0.0096062211906774581 -0.0030631657393957179
leaf_weight=116.00088807567954 472.09226742759347 124.99072538688779 1218.65966508165 150.2819258607924 1912.1117149032652 612.13968088850379 209.62532310932875 634.14765760302544 307.92747371271253 846.34025071561337 861.60115721076727 383.9340597614646 126.32135872542858 1011.5527378618717 2390.7197830677032 310.0014440305531 180.28138595074415 645.16357791423798 715.68944830819964 257.91359271854162 165.26651087775826 1743.2439365647733 304.48144033178687 1018.1899079531431 210.62331166863441 471.93201606348157 227.16346909850836
leaf_count=925 5944 1202 21215 2355 30828 10733 3134 17353 2414 5530 13021 5405 1605 12231 51940 2592 1754 6401 6232 4841 1202 16843 2481 8083 3363 3267 3106
internal_value=0 0.00112026 -0.000238477 -0.00370474 -0.0012625 -0.000166492 0.000923646 -0.00471998 0.00344634 0.00305748 0.00199713 0.0033711 0.00437509 0.00611504 -0.00384995 0.00501269 0.00315858 0.00382157 0.00554249 -0.00428284 0.00169395 0.00127556 0.00658936 0.00595548 -0.00244811 0.00653921 0.00126654
internal_weight=0 13496.1 8517.18 4132.32 6546.57 4634.46 3415.8 3433.06 4978.9 4670.97 2593.03 1731.43 1521.81 1137.87 2798.92 1916.12 1970.61 1790.33 1145.16 2648.63 2754.85 2589.58 1020.17 1606.12 822.763 1490.12 699.256
internal_count=246000 160461 119605 85539 101535 70707 49492 76489 40856 38442 35396 22375 19241 13836 59136 14867 18070 16316 9915 56781 23575 22373 8713 12275 14096 11350 9050
is_linear=0
shrinkage=0.0152673


Tree=109
num_leaves=28
num_cat=0
split_feature=21 20 21 20 411 135 126 143 11 1 126 7 8 7 391 0 391 388 8 390 165 10 135 8 391 19 10
split_gain=307.187 177.114 123.067 88.4356 84.929 50.49 49.574 46.2355 47.7991 44.1259 43.5423 41.861 67.8739 38.7778 37.0993 35.4397 38.8249 43.4495 32.7359 36.5702 32.5626 29.9465 29.3706 28.3077 31.4853 28.1063 26.4552
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 0.040081323462308617 1.0000000180025095e-35 0.457168894289186 -0.46615500498768342 3.0555555555555558 -1.9969746974697469 1.0000000180025095e-35 -0.50322998310294975 0.028239099334452948 1.0000000180025095e-35 -0.44772034583566583 0.03816955897477646 1.0000000180025095e-35 0.12742144408804593 0.22610102890935133 0.51063775510204101 0.020474901307288299 263242.77750000003 -0.29288559263837383 0.72934386391251527 1.0000000180025095e-35 -0.80185022711144738 -0.070103378060431251 0.79913473423980241
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 15 9 5 6 -4 8 -1 21 -10 -8 14 -12 -13 16 17 -3 19 -11 -7 -2 -23 24 -15 -5 -26
right_child=3 2 4 25 -6 20 11 -9 10 18 13 12 -14 23 -16 -17 -18 -19 -20 -21 -22 22 -24 -25 26 -27 -28
leaf_value=-0.0040248142825132652 -0.0058221179914493756 0.0089730491436314265 0.0022967639781490074 -0.0013232886061295963 -0.0044742761335687716 0.001796721889271891 -0.0038258441683146696 0.0091116706900490826 0.0063335767526238153 -0.00057230345861739224 1.071152735628822e-05 0.0031074212726627522 -0.002112472903686699 -0.00069185438183514694 0.015768445442772901 -0.0033285817812332315 0.00074007354532270328 0.0029178118710439234 -0.0040687260398134468 0.0066288107160040917 0.013340129691837066 -0.0024494654917358687 0.0065759715305640067 0.0019249430756787891 0.007328321231720108 -0.0070320952479882059 0.0015449024505453121
leaf_weight=213.79298565909266 643.84766297414899 476.48360515013337 763.81653448194265 236.62776281684637 1471.242830850184 1184.7793301716447 1535.7106530703604 309.79627389460802 908.59656674787402 359.78595495596528 995.28473807871342 314.74216556549072 1142.9911244772375 182.08075422793627 65.833127379417419 179.82642735168338 645.5286326892674 673.08830411359668 223.33729780837893 299.21149575337768 60.004099547863007 748.3546878285706 94.06893664970994 1258.0487054921687 883.47344932332635 1513.1155827753246 238.48424158245325
leaf_count=2074 12984 3940 10985 5134 26946 16040 23551 2414 7002 5592 8690 4223 18351 1645 759 1754 6401 5975 3551 4076 680 12967 1454 11108 6388 39781 1535
internal_value=0 0.00110244 -0.000235088 -0.00366071 -0.00124484 -0.000305363 -0.00117651 0.00338652 0.00300519 -0.00173223 0.00334394 -0.00204677 -0.000247244 0.00257746 0.00532875 0.00310342 0.00375316 0.00543673 0.000964141 0.00268442 0.00236258 -0.00333903 -0.00142945 0.00357091 0.00515126 -0.00626553 0.00610765
internal_weight=0 13503.6 8514.05 4118.35 6539.12 5067.88 3823.09 4989.56 4679.76 2368.61 4465.97 3059.28 1523.57 3557.37 380.575 1974.93 1795.1 1149.57 882.335 658.997 1244.78 1486.27 842.424 2562.09 1304.04 1749.74 1121.96
internal_count=246000 160461 119605 85539 101535 74589 57869 40856 38442 40624 36368 46884 23333 29366 4982 18070 16316 9915 13219 9668 16720 27405 14421 20676 9568 44915 7923
is_linear=0
shrinkage=0.0152673


Tree=110
num_leaves=28
num_cat=0
split_feature=19 387 19 7 8 6 155 390 8 7 149 10 135 149 152 19 154 390 1 137 10 151 69 10 67 17 165
split_gain=249.488 178.936 89.9065 85.9364 142.908 112.458 80.7106 84.4146 84.6346 64.565 44.6384 43.1711 42.5683 41.8346 41.2006 37.4728 36.8805 36.5825 36.3964 34.9492 28.0263 27.6109 27.4477 27.241 26.8358 26.1802 25.7054
threshold=0.066137329671330417 -0.037632662431008129 -0.31528071226839544 -0.55072463768115931 1.0000000180025095e-35 -0.017790309106098575 104349.91500000002 -0.14311235152499666 0.51063775510204101 0.0055980593394289986 -0.26860095034936238 0.023142425491003985 0.62241798298906448 -0.56276057860585704 4.5625000000000009 0.19388630579008007 3.785714285714286 0.47519514834556914 1.0000000180025095e-35 -0.21428571428571425 -0.94114819392940519 0.61133032694475775 1.0000000180025095e-35 0.71247081444856486 1.0000000180025095e-35 -1.0000000180025095e-35 85727.835000000006
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 3 11 24 5 10 7 12 13 -7 21 -3 22 14 -9 20 -8 -15 -12 -6 -2 -5 -4 -20 26 -11 -1
right_child=15 2 6 4 19 9 16 8 -10 25 18 -13 -14 17 -16 -17 -18 -19 23 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0021555868145923598 0.010991708274158173 0.025281627903022054 -0.0049447748694815882 0.0060819573899223113 0.0028238789683483305 -0.001087469160307032 0.0067065876502662349 0.0073112115063738497 -0.003575419213773379 0.0026688718702878346 0 0.0049051841615872296 0.0003468625119672985 -0.00095767840294734325 -0.0045559243672127761 -0.0067636282451454671 -0.000881953360933647 0.0030699454034550794 0.006919222605406867 -0.0006448344268190862 -0.0032151809386047879 0.017001746564738986 0.00065550259486640416 0.00046685504291383087 0.0045529654464939642 0.014479889315679563 0.0058820647459008864
leaf_weight=1234.7727618142962 32.905441384762526 26.124324459582567 2286.1732370071113 807.14986443519592 1168.8458888195455 81.579921964555979 410.81544661894441 399.35425871238112 1254.4482680521905 50.323023218661547 713.39415490999818 360.39502873271704 517.10242637991905 1616.4538809992373 81.083801832050085 1117.3340014405549 231.26021446287632 777.85602217912674 484.08641242235899 1601.6476031951606 1079.6661223769188 58.937200155109167 220.79647129401565 227.25929652526975 191.5529163479805 484.94416877254844 99.570217087864876
leaf_count=14656 583 250 38521 7839 14114 929 4484 4998 20886 558 8129 3312 7437 23366 1195 23005 3018 9766 5252 21141 19559 447 3512 1993 2096 4051 903
internal_value=0 0.000681026 -0.00086308 0.00243596 0.00330065 0.00566531 -0.00122049 -0.00168684 -0.000265084 0.011459 0.00410039 0.00631845 -0.003625 0.0011764 0.00528827 -0.00478303 0.00395969 0.000347125 0.00242822 0.000815376 -0.00278487 0.00683938 -0.00444787 0.00487142 -0.000775751 0.013388 -0.00154815
internal_weight=0 15385.9 8181.86 7204.06 5678.17 2907.67 7795.34 7153.27 4129.2 616.847 2290.83 386.519 3024.07 2874.75 480.438 2229.91 642.076 2394.31 1424.74 2770.49 1112.57 866.087 2506.97 711.346 1525.9 535.267 1334.34
internal_count=246000 202853 120745 82108 64453 29198 117183 109681 60211 5538 23660 3562 49470 39325 6193 43147 7502 33132 15374 35255 20142 8286 42033 7245 17655 4609 15559
is_linear=0
shrinkage=0.0152673


Tree=111
num_leaves=28
num_cat=0
split_feature=21 20 21 20 143 1 19 2 391 391 20 119 390 112 8 157 1 8 390 391 135 139 7 391 7 231 90
split_gain=296.29 170.462 120.708 86.4598 85.8531 90.6131 76.5872 67.4201 54.0001 61.8954 47.2704 42.7142 42.5851 40.8917 39.228 38.5492 35.9791 34.459 39.2341 34.3837 32.651 31.7392 31.6732 31.5579 31.9015 31.4824 31.3662
threshold=0.1746120078555157 0.33014794124083729 -1.2291473454499886 -1.126355914706455 2.6111111111111112 1.0000000180025095e-35 -0.23674106267790407 1.0000000180025095e-35 -0.81178185562575544 -0.63378138164839226 0.46193093371152166 0.96215733015494653 -0.014720089120354104 -0.64902126047634823 0.51063775510204101 191.25000000000003 1.0000000180025095e-35 0.51063775510204101 0.2683214061971631 -0.6485657192683002 0.72934386391251527 0.50946219724703024 0.073023574049884951 -0.16577837173759505 -0.0240094545002177 -82.638849999996623 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 11 -2 5 6 -4 26 -8 19 15 13 -11 -1 23 16 -5 18 20 -10 -3 22 -6 -14 -25 -13 -7
right_child=3 17 4 10 21 7 8 -9 9 12 -12 25 14 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=0.010098598541694301 0.001275873278744405 -0.004040661984478471 0.0054827976735148717 -0.0053727951523677171 0.0046722891302942793 0.00093634505824569125 -0.0072190869753988376 0.00021859690330496237 0.00017213775268831223 -0.0033837099450226634 -0.0084179033758973211 0.0010444053917442349 -0.0024018060194703405 0.0027722375548129854 -0.003185750780803266 0.0073363344241198 -0.0016948358379090436 -0.0056036426533039177 0.0026271541478828089 0.011658561242280548 0.0028079174903004301 -0.00087535204134430225 0.01220230020522204 0.00033250858962572831 0.0056878144046152105 0.0092760019158681824 0.0059705915893352507
leaf_weight=196.98709014058113 698.75652707368135 977.73547730967402 401.80181980505586 1725.7384009882808 332.29672759026289 388.57050723955035 351.57519182190299 1541.9297668933868 114.24564195051789 1552.7982818856835 624.31547509506345 135.61129581183195 379.91057020425797 1917.2788279317319 639.6226192265749 70.478284068405628 981.25892410799861 686.9221462905407 399.49598951265216 133.64124443009496 192.76284354180098 120.56620033085346 221.18461185693741 587.94005707651377 469.23895632103086 594.80548891425133 1174.0221438966691
leaf_count=1319 9050 17705 3746 38927 3600 4397 5251 17435 1259 21809 17353 955 4287 14552 9035 1232 18977 13106 6495 1408 3087 1428 2464 6825 5334 4015 10949
internal_value=0 0.00108035 0.00184879 -0.00360503 0.00092775 0.000471022 -0.000880485 0.00248984 -0.00148747 -0.000965057 -0.00461032 0.00456807 -0.00147133 0.00346006 -3.6816e-05 -0.00375062 -0.00404318 -0.00274724 -0.00149109 0.00640605 -0.0029047 0.00615384 0.00770133 0.00135859 0.0027188 0.00776094 0.00472487
internal_weight=0 13510.9 11254 4100.55 8409.34 7735.3 4630.77 3104.52 4228.97 3877.4 3401.79 2844.68 3629.51 2114.27 2076.71 2777.48 2707 2256.92 1569.99 247.887 1170.5 674.048 553.481 1437.09 1057.18 730.417 1562.59
internal_count=246000 160461 120068 85539 99227 91735 58954 32781 55208 49957 76489 20841 47290 15871 25481 59136 57904 40393 27287 2667 20792 7492 6064 16446 12159 4970 15346
is_linear=0
shrinkage=0.0152673


Tree=112
num_leaves=28
num_cat=0
split_feature=21 21 411 128 130 19 155 154 149 390 151 387 155 391 391 19 411 391 120 391 391 390 391 0 390 391 388
split_gain=288.164 140.533 110.061 89.0319 80.7571 77.4372 67.6441 69.9569 70.1796 60.567 47.3731 46.1688 45.8608 45.1452 50.0866 43.8582 39.8901 36.8195 36.5446 32.9995 32.6504 32.2999 31.3669 30.9673 30.5593 30.4114 47.4453
threshold=1.0000000180025095e-35 -1.3471229168525309 1.0000000180025095e-35 1.0677241379310347 2.0416666666666674 1.0000000180025095e-35 36011.441250000011 0.35714285714285715 -0.58342319933459807 0.10148339268756748 0.28776775648252545 -0.037632662431008129 89006.220000000016 0.18591861150593089 -0.81178185562575544 -0.4294617065977519 1.0000000180025095e-35 -0.64052006669616957 -0.58912248628884811 -0.64538777289892335 1.0000000180025095e-35 -0.40394244617340014 0.12650512597654215 1.0000000180025095e-35 -0.43750805970333967 0.12742144408804593 0.45678925033826762
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 16 3 4 6 9 7 8 21 12 -8 -10 -2 14 -11 -4 23 19 -6 -16 -19 -3 -23 25 -13 26 -1
right_child=5 2 15 -5 18 -7 10 -9 11 13 -12 24 -14 -15 17 -17 -18 20 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0094830652234361799 -0.0045886158786688693 -0.00032685628217006286 0.029816303764248032 -0.0027902282638340515 -0.003110138506663375 -0.007015199854585763 0.0013440393102638879 -0.0029094557920259453 0.0024944815166286385 -0.0051018905029962328 0.0084562557563950709 -0.0039242375737374661 0.0038968808749441485 -0.0029174471969801745 0.0052025101195160971 -0.0030793721284171518 0.00087083471502763076 0.00057646143342305863 0.0089593158612330456 0.023872755313194459 0.0081800997407020064 0.011872202408396827 0.0024192395112712715 -0.0010021848278478707 0.000335234087705766 0.0029963040557937047 0.0036470250271338663
leaf_weight=781.66649980843067 1951.6204235181212 110.27289446815848 9.2449832260608655 1153.8827869705856 65.410620603710413 983.01076260209084 405.82593871280551 1032.0662179663777 1920.9674768224359 184.24657138809562 481.36177268251777 540.2228875644505 159.35791609436274 749.56851767376065 58.174183215945959 1940.3297827355564 654.32321644574404 530.60970790684223 472.32055887952447 37.25895157828927 176.27340807393193 268.5077814720571 121.6439630202949 170.97096079960465 1424.0645685680211 654.9984310567379 567.13406062498689
leaf_count=5236 40427 1410 78 14715 839 23664 4613 13075 20399 3637 4239 8238 2714 14648 896 30092 5715 9172 5323 551 2797 2638 1520 1367 18562 5269 4166
internal_value=0 0.00119053 0.000335485 0.00112931 0.00179167 -0.00318704 0.00130541 0.000663446 0.00150643 -0.00220617 0.00521428 0.000810466 -0.0039434 -8.83778e-05 0.00205196 -0.00291564 0.0041931 0.00370707 0.00747353 0.0126222 0.00248729 0.00688902 0.00895111 0.00518828 -0.000831833 0.00572109 0.00703686
internal_weight=0 12775.2 9946.12 7996.55 6842.66 4830.12 6304.93 5417.75 4385.68 3847.11 887.188 3885.25 2110.98 1736.13 986.563 1949.57 2829.09 802.316 537.731 95.4331 706.883 500.425 390.152 2174.77 1964.29 2003.8 1348.8
internal_count=246000 147494 125741 95571 80856 98506 74694 65842 52767 74842 8852 47199 43141 31701 17053 30170 21753 13416 6162 1447 11969 5568 4158 16038 26800 14671 9402
is_linear=0
shrinkage=0.0152673


Tree=113
num_leaves=28
num_cat=0
split_feature=20 1 391 392 14 135 19 6 391 86 130 149 411 10 416 130 125 19 7 391 168 118 147 124 391 6 149
split_gain=283.406 133.574 120.397 98.289 93.0796 82.8709 73.7873 55.2369 57.3287 53.7362 53.263 51.3947 50.7611 50.2829 77.2193 51.0076 47.0608 41.6631 36.746 36.7659 35.7034 34.0727 32.5322 32.2981 32.1468 30.7416 30.5478
threshold=0.18705904504727433 1.0000000180025095e-35 -0.81178185562575544 0.2600851730102921 -1.0000000180025095e-35 0.6783110571081411 -0.25593239003289309 -0.61766499582289047 0.95255065921527249 1.0000000180025095e-35 0.87500000000000011 -0.10758206668188493 1.0000000180025095e-35 0.77853316852080767 -1.0000000180025095e-35 1.7916666666666667 -0.6986335678197656 -0.11065271382399237 -0.48528954406916708 0.12650512597654215 1.0000000180025095e-35 -0.18669064748201436 0.98648648648648662 2.8750000000000004 -0.84913404291403738 -0.325563909774436 -0.55593076250974105
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 -1 5 -3 9 -2 -6 13 17 11 18 26 14 16 -16 -9 -4 -8 24 23 -12 -18 -7 -20 -19 -5
right_child=6 4 3 12 7 20 10 8 -10 -11 21 -13 -14 -15 15 -17 22 25 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0065023287110454464 0.0040785939363299079 -0.0011603565891648733 0.0031229701328208456 0.0080871851801262596 -0.00077303608767942899 0.0011526632928769887 -0.0070181325861877163 0.021081715680377342 -0.00044638432011071504 0.0055358330789600212 -0.0043545924181924598 -0.0062638664870012534 -0.0011561359222907459 0.0012505101067938841 0.0034673581853813364 0.01073750312070198 0.010317046179095188 -0.0053662370605463885 -0.0071401278616675728 -0.0039004946368383095 0.0092867016465887787 0.0013426119082195203 0.0012449953271322632 0.020705103754533372 0.0034013080125056675 -0.0019152482266727926 0.0031215104259233618
leaf_weight=626.36685234308243 299.84482707455754 960.52461381629109 306.13687264174223 353.60337682068348 472.09794490039349 649.79670609533787 308.82980676181614 84.788271237164736 429.47869512438774 218.31397412344813 384.84969493374228 1965.7139923963696 568.60418374836445 546.93104123696685 1511.0832531414926 266.37260490655899 629.73565080016851 798.22145754098892 78.713140156120062 519.5995700545609 189.94782244414091 667.92709859460592 110.73839044198394 20.198836352676153 449.70263959653676 2514.8297166489065 1666.9329485148191
leaf_count=9574 3793 11356 3431 3152 5137 7940 6296 728 5100 2679 8353 41988 6812 4326 16333 2681 6024 12002 1680 10824 1754 11993 1109 209 8116 36442 16168
internal_value=0 0.00115479 -7.93015e-05 0.000471739 0.00310502 -0.000843191 -0.00323157 0.00411859 0.00476637 -0.00180471 -0.00373479 -0.00468346 0.00286082 0.00548006 0.00636517 0.00456311 0.0102333 -0.00225031 -0.00238654 -0.00101188 0.00343635 -0.000731772 0.00897339 0.0017618 0.00181161 -0.00274974 0.00399577
internal_weight=0 12924.7 7912.95 7286.59 5011.75 4697.45 4675.18 4051.23 3579.13 3837.5 4375.34 3322.56 2589.14 3149.65 2602.72 1777.46 825.262 3619.19 1356.85 1048.02 859.943 1052.78 740.474 669.996 528.416 3313.05 2020.54
internal_count=246000 152957 100163 90589 52794 64457 93043 41438 36301 54554 89250 68904 26132 31201 26875 19014 7861 51875 26916 20620 9903 20346 7133 8149 9796 48444 19320
is_linear=0
shrinkage=0.0152673


Tree=114
num_leaves=28
num_cat=0
split_feature=21 20 21 20 411 128 391 392 20 67 21 19 157 19 130 141 21 168 17 7 8 141 19 10 429 416 141
split_gain=278.331 162.483 112.456 83.6255 79.1281 67.4883 48.9373 61.0147 46.0268 44.6506 43.3499 41.0022 37.0095 34.0378 33.7638 35.9436 33.7244 33.4988 31.3554 30.1597 38.305 28.3794 26.8275 26.4526 26.6519 26.7187 26.085
threshold=0.1746120078555157 -0.69501558637790939 -1.2483043297940404 -1.126355914706455 1.0000000180025095e-35 0.3172551724137932 -0.84913404291403738 0.13217439859692007 0.46193093371152166 1.0000000180025095e-35 -1.6426344058948754 1.0000000180025095e-35 191.25000000000003 -0.24962301927574029 0.62500000000000011 0.12962962962962965 -2.0621762643796608 1.0000000180025095e-35 1.0000000180025095e-35 -0.19593207688001488 1.0000000180025095e-35 1.0000000180025095e-35 0.10232330998452184 0.79913473423980241 1.0000000180025095e-35 -1.0000000180025095e-35 0.42592592592592599
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 9 14 26 5 6 -4 17 12 10 -1 18 13 -5 15 16 -3 19 23 -8 21 -21 -15 24 25 -12 -2
right_child=3 2 4 8 -6 -7 7 -9 -10 -11 11 -13 -14 22 -16 -17 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0065203170842177529 0.0033360731951145263 0.010574640188381267 -0.0052182310121896914 0.0029485052982568946 -0.0043468919734304303 -0.0029800255011592628 -0.0037112702186795988 0.0038308479044279653 -0.0082948911844783688 0.0068717465538429513 0.0051619946241954423 -0.0026929305112666693 0.0071662170208065708 -0.0036987484699064679 0.0061182960383802422 -0.0016050011984674883 0.0022526171715872229 0.0062235692288570531 0.0050909034583011019 0.01397297072258126 -0.00057328830949442827 -0.00013462960713949795 -0.0080949786195422344 -0.0017792511967116582 -0.0040323069644675521 0.0014639144591385973 -0.0029599542205636809
leaf_weight=585.2625303119421 472.62250445783138 133.54949679970741 283.70921848714352 155.45876982808113 1456.4542706385255 1535.3014860637486 623.86874608322978 1374.0338265970349 614.92727222107351 678.87494310364127 741.42135109379888 380.86740653961897 70.956689964979887 2144.4257765598595 560.44374784082174 500.05722587928176 793.11064306646585 161.90831789746881 865.42242902889848 79.161735985428095 952.32211638614535 54.991475842893124 386.87429700046778 418.79248692840338 138.23534343764186 1206.7610984407365 225.54427670314908
leaf_count=3226 5944 1007 4550 2446 26946 23563 10208 16934 17353 5392 6328 4443 1232 45599 4804 4855 7404 1996 6779 1041 15487 810 9859 3137 1207 10344 3106
internal_value=0 0.00104312 -0.000240672 -0.00351022 -0.00121051 -0.000306741 0.00085346 0.00138721 -0.00450638 0.0032228 0.00264919 0.00204251 -0.00365774 -0.00394752 0.00293747 0.00168087 0.00346389 -0.000401493 0.00258044 -0.00103466 0.000494258 0.00813027 -0.00437486 0.00170921 0.00241392 0.00287638 0.00128875
internal_weight=0 13524.5 8508.91 4070.81 6521.75 5065.3 3530 3246.29 3372.64 5015.64 4336.76 3751.5 2757.72 2686.76 1987.16 1426.72 926.66 1872.25 3370.63 1710.34 1086.48 134.153 2531.3 2505.21 2086.42 1948.18 698.167
internal_count=246000 160461 119605 85539 101535 74589 51026 46476 76489 40856 35464 32238 59136 57904 18070 13266 8411 29542 27795 27546 17338 1851 55458 21016 17879 16672 9050
is_linear=0
shrinkage=0.0152673


Tree=115
num_leaves=28
num_cat=0
split_feature=20 1 19 2 130 19 149 19 390 67 119 130 141 164 141 141 90 129 118 7 64 19 389 0 125 416 20
split_gain=270.121 128.537 104.744 104.384 82.4791 71.2 68.8366 51.998 51.3593 48.621 44.0184 43.1943 41.1767 40.4971 36.0175 35.7022 35.1281 38.4927 35.0098 34.439 39.5514 32.5812 31.5193 28.714 28.2736 27.67 26.9437
threshold=0.18705904504727433 1.0000000180025095e-35 -0.23999248241935275 1.0000000180025095e-35 1.0000000180025095e-35 -0.25593239003289309 -0.21757018075529433 0.14515642090416706 0.15922494036477824 1.0000000180025095e-35 0.21364719904648394 0.95833333333333337 0.16666666666666669 79189.863750000004 0.055555555555555559 -0.27777777777777773 -1.0000000180025095e-35 -0.56525182483528991 1.1212230215827341 -0.46140449088760332 4.1406250000000071 -0.0026085327808550436 1.0044877317300249 1.0000000180025095e-35 -0.39650825075464791 -1.0000000180025095e-35 -1.4667066540297049
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 -1 12 6 -2 8 9 -4 10 -7 22 16 15 -10 18 -3 -18 -8 -6 -21 -19 26 -12 -13 -23 -5
right_child=5 3 4 11 19 7 13 -9 14 -11 23 24 -14 -15 -16 -17 17 21 -20 20 -22 25 -24 -25 -26 -27 -28
leaf_value=0.0058318598869184961 0.0040017563087895065 0.0028287273173568171 -0.001958074714526083 0.005031861100620004 -0.0012111376065696467 -0.0049538648762279232 -0.0025544872276240874 -0.0077851948160724462 0.0050375383471984257 0.0020086208515754178 -0.00054985816371227829 -0.0042858292075794845 0.0023317907423864559 0.0026052278770759816 -0.0008168249166091026 -0.0053928421854573154 0.014518652201724271 0.0029174618055381445 0.0074908246910014194 0.0040716425547986414 -0.0021903600577250922 0.012092346220176863 -0.0040374438128050905 -0.0083206750087359803 0.0062692293564044089 0.0060204527199360569 -8.7344947797040283e-05
leaf_weight=639.95354534685612 300.81094611436129 433.63201704248786 1056.1340627335012 289.1561925560236 630.58200372382998 2077.6070592906326 1127.7368876449764 615.08149868994951 646.10692232102156 403.47204592078924 1131.9804511554539 67.105582140386105 770.23357704654336 252.23453648388386 390.46057419478893 1451.2852908819914 178.49297188222408 348.46287844702601 86.537399299442768 1348.5996612086892 282.55873259156942 314.02121668681502 387.24434335157275 123.16324825584888 440.96955470368266 419.16895131394267 1376.3022609055042
leaf_count=5552 3793 4664 14045 1981 8082 44022 15490 15273 6918 7589 20034 741 8259 2685 4946 21355 1521 2851 846 16497 3747 2633 4572 2332 4666 4091 16815
internal_value=0 0.00112425 -8.73851e-05 0.00303388 -0.000609682 -0.00316531 -0.001703 -0.00366305 0.000406131 -0.0029816 -0.00358856 0.000870955 0.00527777 -0.00321878 0.00282371 -0.00377348 0.00661159 0.0079054 -0.00182993 0.00180827 0.00298115 0.00680314 -0.000111313 -0.00132088 0.00485598 0.00863609 0.000796447
internal_weight=0 12937 7912.19 5024.79 7272.24 4652.12 5010.5 4351.3 2092.7 3736.22 3332.75 2560.78 2464.01 2917.79 1036.57 2665.56 1693.78 1260.15 1214.27 2261.74 1631.16 1081.65 2052.7 1255.14 508.075 733.19 1665.46
internal_count=246000 152957 100163 52794 94611 93043 66285 89250 25909 73977 66388 28775 24019 40376 11864 37691 15760 11096 16336 28326 20244 9575 23368 22366 5407 6724 18796
is_linear=0
shrinkage=0.0152673


Tree=116
num_leaves=28
num_cat=0
split_feature=21 21 1 14 128 130 10 90 11 16 14 119 0 10 15 130 8 7 130 149 157 11 70 11 125 150 389
split_gain=268.41 139.603 102.052 79.766 72.9275 69.0438 62.0233 57.24 53.7615 43.8996 41.4704 38.9793 35.1242 33.86 57.0194 32.1676 30.8367 43.7535 30.0803 34.9854 28.7655 31.1959 28.5613 27.4356 27.1997 26.9708 26.1584
threshold=0.1746120078555157 -1.3471229168525309 1.0000000180025095e-35 -1.4999999999999998 1.0677241379310347 2.0416666666666674 -0.16446916632330721 -1.0000000180025095e-35 0.36441144114411445 1.0000000180025095e-35 -1.0000000180025095e-35 0.73808104886769976 1.0000000180025095e-35 0.77853316852080767 -1.0000000180025095e-35 0.62500000000000011 0.51063775510204101 0.064564284381414455 0.29166666666666669 -0.40073939384398222 1743.7500000000002 0.38531353135313534 0.58494208494208511 -1.5316281628162816 -0.13463835588750933 0.61857707509881432 0.060216466451617524
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 4 -4 5 6 11 -5 18 16 -1 -3 15 14 24 -12 17 25 19 26 21 -16 -10 -11 -9 -8 -2
right_child=8 2 3 7 -6 -7 9 13 22 23 12 -13 -14 -15 20 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.00018563167788507483 0.00069589042597850248 -0.0040909290579023228 -0.0025202354112763806 -3.9492523317902434e-05 -0.0048840520864942283 0.0051549934359143238 -0.001585897913194415 0.015144271612920656 -0.0014653564834087235 -0.0071971157626486842 0.0042131832376233625 0.0020199461509449543 -0.0012744364783153393 0.00020307082473952179 0.0019190721567145213 0.0083446629909754381 -0.003836267978419241 0.0037254804108987688 -0.0019591923901673626 -0.0064616758493119507 0.01319812598762988 0.0063967277681720516 0.0056502720507402892 0.0047068970260491392 0.0066254091135133364 0.0077595339598188718 -0.0059938328231371636
leaf_weight=453.31906558945775 330.33553335629404 1512.8022388145328 720.05104861035943 983.81444297730923 947.5590487793088 492.24260296300054 1395.3558746874332 168.16218571737409 807.2394132707268 47.82283866032958 1569.9463896043599 287.63670328259468 198.82410868629813 396.73136439919472 1057.3381567113101 621.56366421282291 514.40864282101393 623.19428591802716 841.91625031642616 1688.3219165615737 74.835448425263166 559.43561349064112 156.70506002008915 635.51852354034781 194.76332350075245 75.441932983696461 229.2334033921361
leaf_count=3752 6938 24260 9887 12520 14228 6294 17642 1617 15041 628 11888 4232 1638 3431 12676 4475 7932 7758 18313 37861 674 5481 2456 6558 2118 772 4930
internal_value=0 0.00102218 0.000221311 0.00209252 -0.00096763 -0.000301304 -0.000830725 0.00306219 -0.00345626 0.000412972 0.00402859 -0.00310946 0.00483159 0.00431068 0.00509931 0.0053898 -0.000486405 0.000332434 -0.00443846 -0.00536271 0.00391177 0.00347469 -0.000298161 0.00385855 0.010604 -0.00109932 -0.00202942
internal_weight=0 13530.8 10687.1 4155.13 6531.98 5584.42 5092.18 3435.08 4053.75 3291.74 2843.65 1800.44 2390.33 2451.27 2054.53 2191.51 2608.4 2093.99 3089.81 2247.89 1691.61 1616.77 963.944 683.341 362.926 1470.8 559.569
internal_count=246000 160461 138708 48404 90304 76076 69782 38517 85539 41290 21753 28492 18001 25997 22566 16363 34104 26172 68042 49729 18831 18157 17497 7186 3735 18414 11868
is_linear=0
shrinkage=0.0152673


Tree=117
num_leaves=28
num_cat=0
split_feature=20 1 391 2 10 19 19 143 2 90 14 119 141 10 416 391 20 19 20 7 20 61 19 143 143 391 19
split_gain=260.494 121.883 115.841 98.9139 92.3282 86.0843 68.819 60.4641 59.5436 53.3575 51.139 54.9601 39.3877 53.3701 59.6427 37.5552 36.1817 35.3052 35.9181 35.0984 34.5105 33.667 33.1483 31.3327 29.9578 29.5074 26.5196
threshold=0.18705904504727433 1.0000000180025095e-35 -0.81178185562575544 1.0000000180025095e-35 -0.16446916632330721 0.0052888466891881101 -0.25593239003289309 2.7222222222222228 1.0000000180025095e-35 -1.0000000180025095e-35 -1.4999999999999998 0.72377830750893934 0.16666666666666669 0.83017442658975427 -1.0000000180025095e-35 0.12742144408804593 0.58088299576300051 -0.11065271382399237 -1.1812398945549447 -0.63009267898239707 -1.38831710370246 0.0081499999999999993 0.081652381945261435 2.5000000000000004 2.7222222222222228 -0.93013883649556617 -0.25593239003289309
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 25 12 7 8 -2 17 9 -6 -8 16 13 14 -3 21 22 -4 -19 -5 -21 -11 23 -12 -22 -1 -9
right_child=6 3 4 19 5 -7 10 26 -10 15 11 -13 -14 -15 -16 -17 -18 18 -20 20 24 -23 -24 -25 -26 -27 -28
leaf_value=-0.0016545156456857317 0.0039153866184073642 0.011579104986439626 0.0093396572850755321 -0.0036403456769222905 -0.00082074316854957282 -0.0031084750987842554 -0.0073066077570085874 0.042688641951257052 -0.00075137470413319659 0.0069038591408277609 -0.0026143831573072545 0.00087685775803421524 0.0022556325218469533 0.00060064095281154228 0.0051076145394427265 0.0019741068155627478 -0.0069778815744704565 0.00028275164799558794 -0.0040951506037445445 0.0054446189531672795 9.634309225500303e-05 0.00078029311457187016 -0.0069192691182063896 0.004541577411286535 0.0081783532824509612 -0.0087712157760977856 0.003543667467110212
leaf_weight=207.49782383814454 301.9053257741034 557.54064036533237 55.060909949243069 349.01134902238846 499.00265965238214 708.31838897615671 728.07054722495377 3.9311073981225482 902.60573042556643 1393.0530611909926 1678.2400350328535 728.58286369219422 772.623086925596 303.88891531527042 842.38297571614385 830.85810079053044 652.65239966288209 582.55477128177881 1701.0870053060353 430.3878931812942 1668.8210481405258 250.38363203033805 390.58974480256438 154.82761353999376 114.21925494074821 413.50262457504869 357.87230937555432
leaf_count=2582 3793 4917 610 4201 5617 10846 15320 31 9770 12628 33158 13130 8259 2361 8482 9658 15358 6315 28183 2965 20343 2461 9482 2802 1266 6992 4470
internal_value=0 0.00110187 -7.97391e-05 0.0029575 0.000458742 0.00177892 -0.00311599 -0.00177889 0.00267456 0.00371764 -0.00360818 -0.00285831 0.00513401 0.00643346 0.00769281 0.00463661 -0.00380763 -0.00267981 -0.00297441 0.000850239 0.00156271 0.00597669 -0.00287248 -0.00200454 0.000620062 -0.00640932 0.00401764
internal_weight=0 12944.6 7905.73 5038.88 7284.73 4584.22 4634.87 2700.51 3875.9 2973.3 4332.96 3604.89 2476.44 1703.81 1399.92 2474.29 2876.31 2338.7 2283.64 2562.44 2213.43 1643.44 2223.66 1833.07 1783.04 621 361.803
internal_count=246000 152957 100163 52794 90589 50980 93043 39609 40134 30364 89250 73930 24019 15760 13399 24747 60800 35108 34498 28775 24574 15089 45442 35960 21609 9574 4501
is_linear=0
shrinkage=0.0152673


Tree=118
num_leaves=28
num_cat=0
split_feature=21 19 21 409 14 130 149 411 10 164 19 163 90 129 130 14 70 1 416 10 130 165 13 141 6 115 147
split_gain=259.969 163.071 125.706 105.265 71.7659 62.7164 54.6412 40.982 55.0098 40.9328 40.2713 39.5939 42.3046 39.2784 43.8054 37.8602 37.6235 33.8688 34.7791 41.1984 33.052 31.6971 30.9515 27.3016 27.2714 26.6388 26.3857
threshold=0.38034479682904804 0.13144353264597256 -1.2291473454499886 -1.0000000180025095e-35 -1.0000000180025095e-35 0.95833333333333337 0.42616163285868341 1.0000000180025095e-35 0.045117428924598274 168537.81375000003 -0.38103144053362498 -0.078749999999999973 -1.0000000180025095e-35 -0.58203222617731687 2.5416666666666674 -1.0000000180025095e-35 -0.3169884169884169 1.0000000180025095e-35 -1.0000000180025095e-35 0.78512566955088603 0.62500000000000011 91800.956250000017 1.2021720159022595 -0.16666666666666663 -0.58470760233918118 4169.2500000000009 0.7702702702702704
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 15 9 -5 6 11 8 21 10 -4 -6 -13 -12 23 -1 -10 22 19 26 24 -2 -14 -15 -17 -26 -19
right_child=7 -3 3 4 5 -7 -8 -9 16 -11 13 12 17 14 -16 20 -18 18 -20 -21 -22 -23 -24 -25 25 -27 -28
leaf_value=0.00013215911074690339 -0.0053981178146418288 -0.0045357765178483493 0.0098494696537537989 -0.0024193749432526307 -0.0019167438080642054 0.0058569461685595665 -0.0016928056106987716 -0.007258625335509597 -0.0039875759039119472 0.005127152202615344 0.0032634290464188627 -0.0005508750493293358 0.0021785818593527194 -0.001278191539919265 0.0030292693541662738 -0.0011593602755181833 0.0021406129433936593 0.015220168355361116 0.003925475483554387 0.0018727820987278778 0.0075612462586334851 0.0040961572384849319 0.016019834669985595 -0.004075077073196493 0.004275545577664526 0.041052365290815344 0.0011653023908149431
leaf_weight=492.40104800835252 1435.3946504611522 1193.9436477031559 69.312124036252499 787.65084916353226 391.22679422982037 1048.2738842591643 882.11017203517258 688.41666093841195 379.89510059729218 218.22883689031005 319.7422241717577 538.49704300425947 1240.2762315496802 1480.4275918677449 324.94537229835987 233.15131890028715 604.62289827875793 229.3786342702806 520.92888624966145 104.97219234332442 720.87270987778902 85.675185887143016 38.909329097718 1839.3306767288595 1663.5156188234687 4.4660506919026366 37.715105921030045
leaf_count=4041 32456 21925 583 10768 5040 12167 11273 16341 7648 2503 4289 6868 15128 21356 4447 1826 10433 2147 5596 882 5149 1647 454 27976 12637 27 393
internal_value=0 0.000865013 0.00135478 0.000524788 0.0018595 0.00253111 0.00165347 -0.00395001 -0.00303679 -0.00129995 -0.00165017 0.00260807 0.0032646 -0.00185402 -0.00230563 0.0040358 -0.000215093 0.00421467 0.0065031 0.0100834 0.00476533 -0.00485686 0.00260919 -0.00283073 0.00369967 0.00438442 0.0132722
internal_weight=0 14380.3 13186.3 10071.9 5819.94 5032.29 3984.01 3194 2505.59 4251.99 4033.76 3101.9 2710.68 3964.45 3644.7 3114.41 984.518 2172.18 892.995 372.066 2622.01 1521.07 1279.19 3319.76 1901.13 1667.98 267.094
internal_count=246000 177475 155550 131870 70716 59948 47781 68525 52184 61154 58651 36508 31468 58068 53779 23680 18081 24600 9018 3422 19639 34103 15582 49332 14490 12664 2540
is_linear=0
shrinkage=0.0152673


Tree=119
num_leaves=28
num_cat=0
split_feature=21 20 21 128 20 20 143 90 391 391 391 90 8 122 135 8 391 163 119 390 126 10 130 141 21 50 20
split_gain=252.831 171.349 112.486 83.0772 63.8666 63.2724 55.2963 53.177 52.1115 88.2663 45.0337 40.5506 41.8226 51.5866 39.7224 37.8225 35.2935 34.9238 34.4803 33.197 32.2258 30.3321 30.2795 34.1502 32.0197 28.0021 25.3615
threshold=0.38034479682904804 -0.69501558637790939 -1.2483043297940404 0.40982758620689658 0.48343955505166164 0.03385880314723428 2.2777777777777781 -1.0000000180025095e-35 0.12650512597654215 -0.80185022711144738 -0.82711714898909583 -1.0000000180025095e-35 1.0000000180025095e-35 3.7068965517241383 0.92132442284325655 -0.15245408163265303 -0.93013883649556617 -0.52874999999999983 -0.057508939213349215 0.42140107963884327 -0.59905132224506819 -0.54216453783820895 0.62500000000000011 0.12962962962962965 -2.0621762643796608 -0.023650000000000001 -1.8843834570786695
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 22 4 6 14 7 -4 9 -9 16 20 13 15 19 -13 -1 -11 -8 -2 25 -19 23 24 -3 -12 -21
right_child=5 2 3 -5 -6 -7 18 8 -10 17 11 12 -14 -15 -16 -17 -18 21 -20 26 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0024994757486138121 -0.003971405627693339 0.010205035695769533 -0.003174961327448299 -0.0039050859048274937 -0.004433375381301596 -0.006404541303736435 -0.0012887224418671323 -0.0052950451009227545 -0.00167273799775383 -0.0021165002090604242 0.022628166859318039 0.0050329139722336373 0.0022732951809940356 -0.00080365356977399154 0.0052957865500892903 0.0097338780649302535 -0.0063450863251507499 -0.0018382885916918598 0.0078497615460451468 0.019015658788797841 3.2285504964495579e-05 0.0058391464507740309 0.0057677748850641876 -0.0016198301147469698 0.0021349930557104596 0.0045937087981237088 0.00018045393458801238
leaf_weight=216.59922490268946 1255.5254768952727 134.96615180373192 1008.53567783162 2060.0228041540831 731.57948862574995 1356.4186254125088 130.69907046109438 276.70198096334934 1102.0184673015028 181.19652488455176 24.307790573686361 1342.4783152937889 1505.1747441589832 256.41021903976798 156.25550778210163 579.02825943380594 202.5086667239666 132.30006667226553 347.98758563771844 17.248401440680027 1044.5348015204072 1118.8499368093908 567.28684587404132 500.23840774968266 796.78013769164681 126.24903330206871 397.20169845595956
leaf_count=1793 22818 1007 16476 34960 15601 36472 2046 4529 17986 2570 209 10101 13236 2019 2463 3848 2291 2197 4627 169 9849 13974 4804 4855 7404 1093 6603
internal_value=0 0.000851414 -0.000419719 -0.00132251 -0.000262865 -0.00390378 0.000445009 -0.000165797 0.000910701 0.0025819 0.00303411 0.00344734 0.00424099 0.00559635 -0.00204084 0.00645514 -0.00175327 0.0041105 0.00533599 -0.00273335 0.00099347 0.00501983 0.00277703 0.0015852 0.00331573 0.00759234 0.000995215
internal_weight=0 14386.5 9089.16 7089.89 5029.87 3182.65 4298.29 3819.6 2811.07 1709.05 5297.29 4878.18 3683.09 2177.92 1826.23 1921.51 419.108 1432.35 478.687 1669.98 1195.09 1251.15 1999.27 1431.98 931.746 150.557 414.45
internal_count=246000 177475 133036 114966 80006 68525 64405 57732 41256 23270 44439 40355 29204 15968 32053 13949 4084 18741 6673 29590 11151 16171 18070 13266 8411 1302 6772
is_linear=0
shrinkage=0.0152673


Tree=120
num_leaves=28
num_cat=0
split_feature=20 21 109 19 21 7 8 6 130 149 149 135 69 20 38 6 8 6 32 124 152 20 19 118 109 390 7
split_gain=246.017 165.735 147.924 77.1573 72.9757 66.6595 77.4045 81.5771 48.2959 42.9532 36.5892 36.3031 35.4554 35.0553 32.5648 31.2192 42.7386 31.6384 30.7706 30.1698 36.8127 28.7433 28.0963 26.6166 34.8676 28.9718 26.2612
threshold=0.29935720544807254 -0.73924480687859639 -0.58333333333333315 0.042042249439647579 -0.45447813724047786 -0.46140449088760332 1.0000000180025095e-35 -0.14897243107769423 0.62500000000000011 -0.21135171585026369 -0.57728082535034619 0.81318347509113009 1.0000000180025095e-35 -2.0097992159524432 0.00074999999999997302 0.069586466165413544 0.51063775510204101 0.55931495405179621 -0.030299999999999997 2.8750000000000004 0.93750000000000011 -1.805970119445869 -0.25931946189574345 0.19172661870503599 0.41666666666666669 -0.072572643482163343 -0.60098277041736636
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 9 5 18 11 7 -7 10 26 -1 -4 -6 -11 21 -8 17 -17 -2 -15 -21 -12 -20 25 -25 -10 -3
right_child=4 2 3 -5 12 6 15 -9 23 13 14 -13 -14 19 -16 16 -18 -19 22 20 -22 -23 -24 24 -26 -27 -28
leaf_value=0.0059199859966830018 0.0081951875197587495 0.00092746289483081978 -0.0042040563597849244 -0.0053214488910617169 -0.0057702690982238585 -9.0566605966906278e-05 -0.0057315576670735995 0.0063316111690497239 -0.00078242990982754724 0.016688741190101917 0.0080221638637124389 0.0026460380167401191 0.0016142779719483418 0.00075269284700179412 -0.0016099545128909121 0.00073637382943372138 -0.0025602983305394547 0.010178226276903098 0.0071142563568016431 0.008448999361755298 0.055348006766298939 0.0019001501359954948 -0.0019784101003637736 0.0050991159102428399 0.011786701079625237 0.0072235869986133185 0.0072081861081447337
leaf_weight=552.040043476969 85.946046520024538 206.38326084241271 1440.5694309622049 982.31114797480404 2122.7737151887268 1093.9761942513287 343.98011832684278 793.17303046956658 235.82072763517499 34.312618911266327 197.5843899846077 204.28846438229084 161.07577736862004 1405.8365647234023 577.61924799159169 882.95499176159501 1346.416768707335 91.486664403229952 85.322594083845615 27.060978207737211 4.5613466165959826 2000.6488304436207 1024.3417023941875 514.22124253958464 288.8188442401588 187.63269488140941 671.74084457755089
leaf_count=4358 1206 2205 22211 20015 51973 14854 5220 9406 2180 199 1058 2559 3733 16265 5252 13014 21277 1286 830 327 51 17305 15076 3757 2165 1580 6638
internal_value=0 0.000888184 -0.000255933 -0.00134511 -0.00364519 -0.00071316 0.00023685 0.00260422 0.00328391 0.00306754 0.00232467 -0.0033475 -0.00524534 0.00146445 0.00160599 -0.00143628 -0.000795275 0.00163414 -0.000580552 0.0010924 0.0158071 0.00245526 -0.00126986 0.00587839 0.00751809 0.00274516 0.00574302
internal_weight=0 14083.4 9529.05 7179.16 3479.46 6196.85 4551.99 1887.15 4554.39 2349.9 3327.89 1644.86 2283.85 1471.77 2775.85 2664.84 2320.86 974.442 1195.61 1437.46 31.6223 2198.23 1109.66 1226.49 803.04 423.453 878.124
internal_count=246000 173182 135527 109842 72818 89827 65057 24260 37655 25685 27973 24770 55706 16842 23615 40797 35577 14300 17112 16643 378 18363 15906 9682 5922 3760 8843
is_linear=0
shrinkage=0.0152673


Tree=121
num_leaves=28
num_cat=0
split_feature=21 411 119 10 8 7 21 149 150 90 411 10 17 17 11 143 21 155 67 139 8 6 392 143 6 143 149
split_gain=241.322 153.791 114.806 100.658 79.4707 138.383 48.7562 47.9872 42.2697 40.7139 40.1955 53.5177 35.7965 35.6195 35.0229 33.6904 32.8155 31.543 31.5004 33.2279 31.3206 39.7607 34.6718 30.2334 28.9055 26.4419 28.805
threshold=0.38034479682904804 1.0000000180025095e-35 0.72377830750893934 -0.53433594286499098 0.51063775510204101 0.064564284381414455 -0.45447813724047786 0.46660264534021834 0.61857707509881432 -1.0000000180025095e-35 1.0000000180025095e-35 0.045117428924598274 1.0000000180025095e-35 -1.0000000180025095e-35 -1.0085258525852583 2.9444444444444451 -1.3229527277820539 93348.045000000013 1.0000000180025095e-35 0.51458020144747574 1.0000000180025095e-35 0.4091938178780285 0.67965469915672316 2.3888888888888897 0.55931495405179621 2.1666666666666674 0.29484182271864989
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 15 5 8 13 20 16 -3 11 17 -8 -4 -11 -1 -5 -2 19 -18 22 -22 -7 -9 -6 26 -16
right_child=10 9 6 4 24 7 12 23 -10 14 -12 -13 -14 -15 25 -17 18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=-0.0031163495348779935 -0.0052730100451329536 -0.0049375456165450995 -0.00073361764359796777 0.003444787666981663 -0.0072904769085322223 0.011994973157295134 0.00023449297921322758 0.0004580656685915232 0.0080407932370413857 -0.0056056881584825979 -0.0071282341172419061 -0.00013433773926971486 0.00838527779021387 0.0067765306240249951 0.00061489957719285603 0.0034581647361499606 0 0.0042323014056068467 0.0038483013827052622 -0.0042084722246223932 0.0017513401592121581 0.0095470883406157357 0.0050610945158822054 0.012147844256461612 -0.00080643126288685923 0.005513960177975682 -0.0038952648289527258
leaf_weight=1625.7528433054686 1419.890362598002 924.31036873720586 160.84047839418054 669.1282253228128 187.43337451480329 462.84877023659647 750.97275933623314 459.91219107620418 176.38167713955045 330.45453797653317 679.09938078932464 979.72944882698357 151.2582394182682 1493.6063322424889 1036.1527679841965 203.08549010567367 2064.8299201652408 85.099046710878611 373.61489789187908 553.59790570475161 397.22588466666639 251.26223106309772 273.58186664059758 58.189269568771124 1135.2127123009413 171.07096413336694 482.55817812308669
leaf_count=25074 32465 14575 1702 4850 2481 4173 10739 5179 1603 5556 16341 18081 1735 12528 14071 2620 24241 1638 4226 6918 4481 2853 2553 618 15330 2149 7220
internal_value=0 0.000829358 0.00163017 0.000809079 0.0016364 0.00241439 0.00448203 0.005781 0.000742307 -0.00228108 -0.00382746 -0.00292113 0.00161267 0.00604088 -0.00106077 -0.00238097 0.000387771 -0.00472896 -0.000293011 -0.000887668 0.0072659 0.004788 0.00943357 0.00179283 -0.00173318 -0.000165988 -0.000812462
internal_weight=0 14393.3 11448.7 8892.06 7063.22 5740.57 2556.68 1903.02 3837.55 2944.55 3163.82 2484.72 902.231 1654.45 2020.24 1828.84 3661.17 1504.99 2992.04 2618.43 1384.92 648.488 736.431 518.101 1322.65 1689.78 1518.71
internal_count=246000 177475 133904 107200 79506 61695 26704 19857 41838 43571 68525 52184 12474 14230 28996 27694 40235 34103 35385 31159 14060 7334 6726 5797 17811 23440 21291
is_linear=0
shrinkage=0.0152673


Tree=122
num_leaves=28
num_cat=0
split_feature=20 21 109 19 409 14 21 21 6 141 130 38 1 143 389 149 124 164 2 6 128 391 391 149 111 141 32
split_gain=237.569 168.65 139.996 79.797 63.4788 63.6678 59.6643 46.4298 44.2552 44.1566 51.9554 40.4682 40.4064 39.6305 36.3786 34.8304 35.7271 33.5815 31.4868 29.8527 36.3086 29.6283 54.8064 28.6434 28.3684 26.9239 26.7852
threshold=0.33014794124083729 -0.73924480687859639 -0.58333333333333315 0.042042249439647579 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.45447813724047786 -1.8821381414301499 -0.57618629908103591 -0.16666666666666663 2.0416666666666674 0.001749999999999974 1.0000000180025095e-35 1.3888888888888891 -0.79257087832410578 0.40272300543394141 0.37500000000000006 202059.87750000003 1.0000000180025095e-35 -0.4797911445279866 1.1512068965517244 0.049180694651566131 1.0000000180025095e-35 -0.028395032574785664 2475.2250000000004 -0.16666666666666663 -0.030299999999999997
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 9 4 17 -6 26 25 -7 15 -11 13 23 19 -12 16 -3 24 -14 -9 21 22 -21 -10 -4 -1 -2
right_child=6 2 3 -5 5 8 -8 11 12 10 14 -13 18 -15 -16 -17 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0094559768424182043 0.0076714082398953217 0.0053982776053345446 -0.0033280979662166656 -0.0053468949351405479 -0.0044658821017650461 -0.0030438441820117516 -0.0053211837676029822 -0.00076576016895987223 0.0025570582500842364 -0.0001972383893748118 0.043544594412846901 -0.00079125661727252807 0.0065671299079476907 0.0071195906898570529 0.0084560698687989148 0.00041852251516427848 0.015557333364745978 0.0068501278883986725 0.0014397262314802615 0.0045120854802983409 -0.0019022659954343526 0.0019995722126378737 0.015510789756472363 -0.0016229697889451051 0.0019980974543305596 0.0038476862930362432 -0.0015681650597948705
leaf_weight=387.74925781041384 78.447073876857758 818.37167580425739 2369.6295504532754 1012.7878573201597 498.64873716980219 444.64300918579102 2072.8264695052058 523.83846436440945 784.19961770623922 1082.6828519366682 7.4443296417593947 704.5002144947648 641.23712780326605 517.03818943351507 94.431370031088591 303.32378747686744 90.816219244152308 86.033118568360806 504.03865812718868 841.06344589218497 270.37398953363299 863.48488998413086 121.80844875052571 742.79783529415727 256.15869835391641 428.23444103449583 1005.5885521508753
leaf_count=2334 1103 8328 38416 20973 7483 6271 51407 4725 10791 12762 74 6628 7325 4109 1051 3404 811 1001 6457 6841 2511 8002 835 11141 3910 2746 14561
internal_value=0 0.000822025 -0.000320087 -0.00136707 -0.000728452 0.000593862 -0.00380254 0.00321137 0.0014065 0.00288197 0.000776101 0.00250481 0.0021506 0.00324781 0.0111901 0.00493126 0.00642631 -0.00249473 0.00431919 0.00247992 0.00329518 0.00406975 0.00591592 0.000517767 -0.0028049 0.00652559 -0.000889796
internal_weight=0 14395.3 9737.24 7340.17 6327.39 3615.56 3156.86 4658.09 3116.92 2397.07 1184.56 3842.11 2672.27 3137.61 101.876 1212.51 909.188 2711.82 1145.28 2620.57 2096.73 1826.36 962.872 1527 2625.79 815.984 1084.04
internal_count=246000 178929 140198 113768 92795 49468 67071 38731 41985 26430 13887 33651 35714 27023 1125 12543 9139 43327 13782 22914 18189 15678 7676 21932 42326 5080 15664
is_linear=0
shrinkage=0.0152673


Tree=123
num_leaves=28
num_cat=0
split_feature=20 391 391 90 391 391 391 391 19 391 391 391 391 391 391 391 391 391 14 119 391 165 391 164 20 7 20
split_gain=231.147 114.043 156.484 106.928 127.592 112.672 85.5408 76.3853 64.6706 63.1874 83.3225 54.3628 151.937 51.8877 51.8027 79.454 79.2577 66.5864 49.888 51.978 48.2715 41.9216 41.9177 37.521 34.6554 34.1678 33.1545
threshold=0.18705904504727433 -0.80185022711144738 -0.63378138164839226 -1.0000000180025095e-35 0.12742144408804593 1.0000000180025095e-35 0.049180694651566131 -0.92257102786474277 -0.25593239003289309 0.48751167347278374 0.51300508801153255 -0.47078515063125309 -0.45016581085748902 -0.65476695674678731 -0.16577837173759505 -0.25263403589260863 -0.13637983244433508 -0.31654866915794927 -1.4999999999999998 0.72377830750893934 0.10767533198381948 86467.668750000012 -0.54098017844301649 59136.232500000006 0.58088299576300051 -0.50569136032841933 -2.0097992159524432
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 13 21 5 11 -7 -1 -2 -6 -11 22 25 -3 15 17 -16 -14 -10 24 -8 26 -5 -12 -20 -13 -4
right_child=8 2 3 4 9 6 20 -9 18 10 23 12 14 -15 16 -17 -18 -19 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.00043296209661471721 0.0038470113701528693 0.0023457381418656251 0.0093280571741244794 0.000231588602001108 -0.0038063134486063686 0.012005107329439881 0.00089613494734688858 -0.0073286177361589688 -0.0071302118957016136 0.012464274357056292 -0.00051698458886696231 0.0074973098162738148 -0.00068257792788192155 0.009941779952118153 0.0089956100142388438 -0.0074814760498794174 0.0011750421294744145 0.0089681508350268301 -0.0027147848225032079 0.00093737409511871622 0.0087178666935324375 0.0058010272647004528 -0.0096280924094718466 0.0050846189368591171 -0.006770918638975036 0.020486899029859791 -0.0022643172284524367
leaf_weight=580.71484890952706 302.57585616409779 318.3519697971642 58.296044535934925 327.32199381664395 902.37281430140138 540.2792798653245 460.51410717889667 597.22979448363185 714.75410108268261 137.11239890009165 2076.9927331358194 80.628047212958336 660.27862785384059 634.98334871977568 460.32747017592192 288.95161217823625 887.82689014077187 222.07642061635852 2198.0894113797694 725.64216238819063 309.42578559741378 169.36651182919741 143.75289921090007 321.53928342834115 638.97169630974531 125.26141769811511 2662.6820271722972
leaf_count=6652 3793 3030 408 3327 12425 4382 4937 9550 15320 1389 27820 730 6819 5586 4147 3934 9786 2021 45442 13130 2653 1713 1932 3336 15358 946 35434
internal_value=0 0.00103179 0.00148496 0.000962146 0.00187746 0.00356749 0.00734038 -0.00349504 -0.00295799 -0.000335281 0.000896563 0.00201775 0.00284718 0.00741583 0.00181195 -0.000529831 0.00385311 0.00173748 -0.00344165 -0.00269872 0.0040529 -0.00155056 -0.00276056 0.00023049 -0.00363196 0.0154567 -0.00201192
internal_weight=0 12966.3 11788.3 10835 7944.66 4506.64 1310.22 1177.94 4580.03 3438.02 2535.64 3196.43 2725.35 953.335 2519.46 1171.31 1348.15 882.355 4277.46 3562.7 769.94 2890.34 471.075 2398.53 2837.06 205.889 2720.98
internal_count=246000 152957 136755 128139 90584 45614 11972 16202 93043 44970 32545 33642 28383 8616 26707 12774 13933 8840 89250 73930 7590 37555 5259 31156 60800 1676 35842
is_linear=0
shrinkage=0.0152673


Tree=124
num_leaves=28
num_cat=0
split_feature=21 20 19 130 149 20 7 8 7 387 7 149 135 19 147 390 143 21 128 119 19 10 389 167 12 8 7
split_gain=227.812 156.007 108.205 93.0047 73.1876 60.1498 52.9301 57.7092 53.9982 43.4213 40.4142 45.8835 38.036 36.0562 33.6862 31.7709 31.716 30.9673 30.3502 27.7132 27.3765 27.7537 27.0779 25.9967 25.1426 27.7075 26.799
threshold=0.38034479682904804 -0.78572725661621623 0.13144353264597256 0.54166666666666685 -0.028395032574785664 0.03385880314723428 -0.60098277041736636 1.0000000180025095e-35 0.057349007899483738 -0.075764727887288719 -0.46140449088760332 -0.0060715307131818932 0.92132442284325655 -0.29070757998552249 0.6351351351351352 0.42140107963884327 2.7222222222222228 -2.0089485232886477 1.125689655172414 -0.16537544696066744 -0.27656332852295634 0.87096552671336369 0.068263792211535682 0.75000000000000011 -0.82350255661066463 0.51063775510204101 0.29769235553896878
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 3 4 6 12 -3 8 -8 17 19 14 15 -5 -12 -2 -13 -6 22 -1 21 -19 24 -24 -15 26 -26
right_child=5 2 -4 13 9 -7 7 -9 -10 -11 11 16 -14 18 -16 -17 -18 20 -20 -21 -22 -23 23 -25 25 -27 -28
leaf_value=-0.0035614052296780154 -0.0038227719968690435 -0.0029976991945789436 -0.0052620305457221871 0.010616017380887049 0.010500301128958011 -0.0062031677268779778 0.0020375982093351979 -0.00036203669970941323 0.0088165282983982754 -0.0040069432013080143 0.0068056844409431719 0.0013855420624114827 0.0052535218351480008 -0.0008156526363515545 0.0020481475809080467 0.0010485891672588131 0.0082699451900331185 0.0094067376680549257 -0.0023840060878793316 0.0018708202034603083 -0.0016291379239114631 -0.0043717335896732816 0.00064543080855375358 0.012763019770532505 0.0057870727586508842 0.002071549007269493 0.013570634724230927
leaf_weight=274.59116489812732 1241.5729634165764 642.96379940398037 936.89716519601643 134.52224833145738 57.628574080765247 1329.9036037363112 860.65297162532806 1294.5696337688714 405.28949304111302 1714.6862431038171 1344.1949970424175 1558.1383987851441 156.50475827232003 139.60362274572253 476.07226400822401 413.14602950960398 174.1457225009799 108.83216430991888 263.0060652308166 1065.0143383853137 1284.3776399772614 48.382943358272314 837.72446759417653 43.380284316837788 323.03208608180285 254.46789217740297 157.21552392840385
leaf_count=2779 22818 8908 18988 1175 410 36472 10455 18631 4376 27845 9910 13204 2463 2022 3924 6772 1383 1073 3754 8923 17929 478 11346 454 3954 3714 1840
internal_value=0 0.00080305 -0.000336041 0.000201502 -0.000718561 -0.00373474 0.000912438 0.00189804 0.00421615 -0.00234707 0.00301851 0.00387121 -0.00191673 0.00294804 0.00556679 -0.00260099 0.00208379 -0.000442258 0.00243145 0.000750125 -0.000887443 0.00510805 0.00315833 0.00125518 0.00506505 0.00619483 0.00835878
internal_weight=0 14399.4 9507.23 8570.34 6417.38 3141.13 3203.48 2560.51 1265.94 3213.91 4892.16 3552.55 1811.22 2152.95 1820.27 1654.72 1732.28 1499.22 2018.43 1339.61 1441.59 157.215 1755.42 881.105 874.319 734.716 480.248
internal_count=246000 177475 137352 118364 90105 68525 42370 33462 14831 47735 40123 28421 32053 28259 13834 29590 14587 19890 27084 11702 19480 1551 23330 11800 11530 9508 5794
is_linear=0
shrinkage=0.0152673


Tree=125
num_leaves=28
num_cat=0
split_feature=21 411 119 10 391 391 7 391 112 391 391 391 391 411 10 21 70 130 16 86 143 21 168 7 128 155 391
split_gain=221.523 145.676 108.459 93.9077 72.2838 82.6939 71.5377 60.7288 47.7654 45.2416 52.5892 49.9162 48.5299 39.244 51.4152 38.897 36.1534 34.9737 35.8029 32.8164 35.0517 32.3946 31.4914 37.1591 30.6276 30.4971 29.8356
threshold=0.38034479682904804 1.0000000180025095e-35 0.72377830750893934 -0.53433594286499098 0.12742144408804593 1.0000000180025095e-35 -0.44349070100143057 0.049180694651566131 12.176752371482237 -0.035868283237475519 -0.80185022711144738 -0.92257102786474277 -0.64052006669616957 1.0000000180025095e-35 0.045117428924598274 -1.034174758399736 -0.3169884169884169 0.95833333333333337 1.0000000180025095e-35 1.0000000180025095e-35 2.9444444444444451 -0.15186092134132381 1.0000000180025095e-35 -0.016296572743671078 0.38593103448275862 93348.045000000013 0.10767533198381948
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 19 5 6 -5 -7 17 10 11 -8 -12 14 25 -3 -16 18 21 20 -1 -4 23 -6 -14 -2 -9
right_child=13 15 8 4 22 7 9 26 -10 -11 12 -13 24 -15 16 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0034585204577800058 -0.0051216890366063946 0.00028969119248155567 0.0037533885785485791 -0.0011466180599027636 -0.0042664912135859327 0.011214931422306096 0.0028774118682376696 0.00016242547253807576 -0.0076838298205886254 -0.0078479999061027775 0.0088318526788569943 -0.0078288101178536091 0.0045444813983025901 -0.006979105644262548 -0.0037925197682949089 -0.0034586558935528876 0.0022505506209948129 0.0075003844049726402 0.0081559991548724176 0.0091387826716582635 0.0033317291764047852 -0.0016230961919401785 0.0046381800073297041 0.00016599958785278425 -5.6065099412427156e-05 0.0042282923832052104 0.007541640693171826
leaf_weight=1566.83397150971 1401.4661732558161 949.44486986100674 1101.5904985740781 1404.170932110399 684.61751202121377 397.14811001345515 250.66316254064441 306.67987088114023 74.139207767322659 84.114185899496078 466.26006275229156 169.6565228831023 1176.6059527397156 668.67862390726805 374.20962171442807 1985.7639329843223 601.02555340714753 735.20572734065354 318.69739463925362 55.896569209173322 198.27224238216877 339.56555044651031 222.94328252598643 1227.0803343243897 467.33517078869045 85.093402625992894 221.91562190651894
leaf_count=24374 32465 9073 10456 16062 8731 3299 2768 3213 924 1209 4192 2507 11563 16341 7648 34498 10433 7368 2876 767 2553 5080 2305 16590 5124 1638 1943
internal_value=0 0.000790464 0.00156764 0.000768669 0.00156482 0.00257888 0.00162807 0.00669535 0.00433157 0.00312168 0.00349052 -0.0014239 0.00447378 -0.00369035 -0.00279284 -0.00224313 -5.91602e-05 0.00469285 0.00351404 -0.00232121 -0.0026903 0.00248018 -0.000779796 -0.00141685 0.00323123 -0.00457982 0.00327938
internal_weight=0 14404.6 11469.4 8900.19 7079.19 4944.55 4018.81 925.744 2569.2 2614.64 2530.52 420.32 2110.2 3130.47 2461.79 2935.21 975.235 2495.06 1759.85 1821 1765.11 1441.16 2134.64 1911.7 1643.94 1486.56 528.595
internal_count=246000 177475 133904 107200 79506 51880 43425 8455 26704 27363 26154 5275 20879 68525 52184 43571 18081 25780 18412 27694 26927 15536 27626 25321 16687 34103 5156
is_linear=0
shrinkage=0.0152673


Tree=126
num_leaves=28
num_cat=0
split_feature=20 21 109 19 119 391 391 14 10 21 143 141 52 20 112 109 388 143 143 387 149 8 154 143 149 161 60
split_gain=220.084 154.88 131.933 75.8601 60.7216 59.152 75.528 57.7766 57.346 56.6346 47.5836 42.0039 40.9689 39.6552 38.0806 35.3163 34.2204 47.6537 33.5508 30.9794 30.3032 30.1639 27.191 27.1691 27.156 32.8013 26.3317
threshold=0.33014794124083729 -0.73924480687859639 -0.58333333333333315 0.042042249439647579 0.56168057210965439 -0.80185022711144738 -0.64052006669616957 -1.0000000180025095e-35 -0.56647438538662265 -0.45447813724047786 2.3888888888888897 -0.2407407407407407 3.5000000000003335 -1.417518363968721 -0.58588632668844787 1.0000000180025095e-35 -0.77607244876232973 3.1666666666666674 1.0555555555555558 0.84250630998422127 0.40272300543394141 0.54582142857142868 2.785714285714286 -1.0000000180025095e-35 -0.043796884470367906 4997.0362500000001 -0.028849999999999997
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 11 5 14 -4 -7 -8 -9 26 13 20 15 -10 -1 -6 17 -13 -16 24 21 22 -3 -17 -15 -26 -2
right_child=9 2 3 -5 12 6 7 8 10 -11 -12 16 -14 19 18 23 -18 -19 -20 -21 -22 -23 -24 -25 25 -27 -28
leaf_value=0.0057316682812423268 0.0073408344483118192 0.0081713247338956897 -0.0051793640304144172 -0.0052319805108158356 0.0043540832582474043 0.0067081424280286605 -0.0047695868902989146 -0.0032728352549470361 0.0039044634485974556 -0.005174711000204126 0.0067379243797186386 0.005178482848903221 0.00030833913641445333 0.0020488472631975032 -1.1096175974221311e-05 0.0048525381003488698 0.00063570194561109975 0.06786125070121346 0.0045844086571453701 -0.0035514200134248407 0.00051600153733636213 -0.0017362863702835251 -0.0037113422437297697 0.011611350065346346 -0.0021491536113963225 0.0080041795166611897 -0.0015427495241263495
leaf_weight=448.77314953505993 83.922599922865629 702.30149368569255 621.93855509161949 1002.7619807459414 920.21371920034289 344.26205323636532 695.75032883882523 1009.4029826000333 592.51351850107312 2046.1963241919875 293.0341405980289 9.9120588526129705 330.63256252929568 1120.401002060622 1910.7183730714023 226.50974439829588 1274.8829800486565 4.0024993307888499 457.9556570649147 589.43440692871809 274.13974538818002 92.659727729856968 46.742392484098673 384.52245139330626 969.56698666885495 79.825126726180315 996.91025753319263
leaf_count=3500 1176 6752 10459 20973 6842 3940 10918 18044 4939 51407 3724 126 2783 15290 17135 1785 14791 37 3814 10074 3075 1160 489 2872 14449 958 14488
internal_value=0 0.000787644 -0.000309795 -0.00133001 0.00306997 -0.000708925 -0.000218876 -0.000666568 -5.10632e-05 -0.00368066 0.000838809 0.00279142 0.00521155 0.00031996 0.00165121 0.00626411 0.000904925 0.0245642 0.000873836 -0.00044668 0.00496156 0.00639812 0.00741679 0.00912325 0.000392765 -0.0013667 -0.000843268
internal_weight=0 14402.9 9723.53 7318.89 4679.33 6316.13 5694.19 5349.93 4654.18 3127.03 3644.78 2404.64 1861.88 3351.74 2817.45 1531.25 1288.8 13.9146 2368.67 2759.23 1115.84 841.704 749.044 611.032 2169.79 1049.39 1080.83
internal_count=246000 178929 140198 113768 38731 92795 82336 78396 67478 67071 49434 26430 14282 45710 24449 11499 14954 163 20949 40771 11476 8401 7241 4657 30697 15407 15664
is_linear=0
shrinkage=0.0152673


Tree=127
num_leaves=28
num_cat=0
split_feature=20 21 19 20 7 8 6 119 21 52 149 13 149 11 7 389 130 130 20 60 155 19 154 137 6 19 19
split_gain=214.002 149.855 101.129 84.6452 66.3895 99.8231 81.971 58.5205 55.414 39.4299 34.0239 33.5163 32.6198 32.907 29.4148 27.6622 28.6396 26.4005 26.051 25.4311 24.2424 24.1411 23.7513 23.7459 23.6482 25.6735 23.2764
threshold=0.33014794124083729 -0.73924480687859639 1.0000000180025095e-35 -1.6973680938911146 -0.46140449088760332 1.0000000180025095e-35 -0.11691311612364243 0.56168057210965439 -0.45447813724047786 3.5000000000003335 -0.26291118615250192 -0.30931833608067483 -0.44132996434222038 -1.5316281628162816 -0.20389376127386946 0.48048471629757566 0.62500000000000011 0.29166666666666669 0.5674867089269362 -0.028849999999999997 103184.55 -0.26283576276536469 1.3571428571428574 1.0000000180025095e-35 0.034761904761904765 -0.38103144053362498 0.19388630579008007
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 3 -3 11 6 10 15 19 23 22 -5 -7 -14 -8 16 -1 20 -10 -2 -12 -21 -6 -9 -15 -26 -4
right_child=8 2 26 4 5 12 14 9 18 -11 17 -13 13 24 -16 -17 -18 -19 -20 21 -22 -23 -24 -25 25 -27 -28
leaf_value=0.0015726934781301971 0.0071850563241389409 0.0050211688482958835 -0.0025375002656976963 -0.0053702104351217436 0.0060554679144271253 0.0019316482071027232 -0.0021109725899877648 0.007580244667158802 -0.0037831322773018029 0.00030357092279899306 -0.0025276166911526012 -0.0011560984278684064 -0.0068746851916043471 -0.0062095260304781174 0.008551794595894821 -0.00062477972194346346 0.0058904878835985709 0.0035445475103680771 -0.0073897109224083796 0.0068513501483276756 0.0078048052892111894 -0.0022008199316416585 -0.0007581897534107802 0.003588218040379581 0.013058952922909392 -0.0009765258206410498 -0.00659430693495619
leaf_weight=1469.1905487291515 84.433419659733772 812.31785057857633 898.67258649133146 657.7140139117837 433.00645029172301 649.41193583607674 65.251082088798285 981.7988522015512 1284.5371356233954 330.70125367492437 744.23891434073448 1352.2455579936504 276.84464002028108 205.08662234991789 618.70507214590907 873.36138791963458 477.90915989130735 296.1950028128922 752.02727160789073 73.604768585413694 56.431137647479773 922.02370925620198 161.34625827893615 555.4289463981986 30.592018712311983 1928.7396233603358 532.23044499196112
leaf_count=12683 1176 6146 16577 10775 5095 9343 955 7282 31146 2783 10309 18835 4913 3043 6685 7853 3913 3869 20261 711 606 13777 1951 4217 298 29294 11504
internal_value=0 0.00077534 -0.00030526 0.000340842 -0.000166615 0.000704545 0.00305901 0.00301729 -0.0036367 0.00511543 0.00124849 -0.00254003 -0.00110197 -0.0019128 0.00752083 0.00162423 0.00263768 -0.000337951 -0.00512 -0.000830881 -0.00178618 -0.00152117 0.00419075 0.00614446 -0.00127333 -0.000751398 -0.00405356
internal_weight=0 14407.4 9719.03 8288.13 7475.81 5465.85 2375.17 4688.39 3116.63 1867.93 1691.22 2009.96 3090.67 2441.26 683.956 2820.46 1947.1 1096.87 2036.56 1080.06 800.67 995.628 594.353 1537.23 2164.42 1959.33 1430.9
internal_count=246000 178929 140198 112117 105971 76361 29470 38731 67071 14282 21830 29610 46891 37548 7640 24449 16596 14784 51407 15664 10915 14488 7046 11499 32635 29592 28081
is_linear=0
shrinkage=0.0152673


Tree=128
num_leaves=28
num_cat=0
split_feature=20 19 155 387 7 8 7 20 119 391 171 391 391 111 149 141 143 391 411 389 152 10 63 128 6 8 162
split_gain=208.95 129.953 105.951 88.0646 61.0659 60.8184 62.9685 57.0668 56.5216 50.3001 49.4207 43.7341 43.4917 43.446 41.5448 38.0454 37.3389 31.838 30.569 29.2281 34.5375 28.9991 28.9056 28.0952 27.2334 28.0105 26.5202
threshold=-0.78572725661621623 0.14515642090416706 36011.441250000011 -0.085097128818110032 -0.46687814890837837 1.0000000180025095e-35 0.085712508552590674 -1.8843834570786695 -0.1272348033373063 -0.81178185562575544 11.250000000000002 -0.63378138164839226 -0.66068996828538784 1175.2425000000003 -0.0060715307131818932 -0.2407407407407407 2.6111111111111112 -0.92257102786474277 1.0000000180025095e-35 0.29204001360924364 6.1875000000000009 -0.18067573135558299 0.060350000000000001 1.641396551724138 -0.35500417710944021 1.0000000180025095e-35 1238.6250000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=7 2 3 4 -2 6 -6 -1 -5 17 26 -11 -8 16 15 19 18 -9 21 20 -13 -10 -14 -7 -17 -26 -4
right_child=1 -3 10 8 5 23 12 9 13 11 -12 14 22 -15 -16 24 -18 -19 -20 -21 -22 -23 -24 -25 25 -27 -28
leaf_value=0.0063350266943588869 -0.0028427535487933141 -0.0060276657390782619 0.0095248067877342409 -0.0046885163904392835 0.0012514751482221743 0.00030280571982324508 0.00071675830667582358 0.00066290380518565692 -0.0037024189618041475 0.0071133834774605685 -0.0012740569798610248 0.0084969182021779437 0.011496876993984682 0.0039034898149795183 0.00020082659347153437 -0.001883914431231529 0.0036293969455895394 -0.0076392614452207783 -0.0054929180032485267 0.0015118212702033452 -0.0062709652318414409 -0.00012182154811451867 -0.006949941312961466 -0.0058013756783925566 0.0066425121329324573 0.001016500464623957 0.0036819598890742672
leaf_weight=741.86712250486016 983.66095338575542 1159.1010076589882 246.07284577377141 1844.4826868567616 831.71907067857683 1482.9710247702897 145.18414227850735 228.27033507451415 899.34953443147242 396.39674987643957 384.96845378167927 574.24124039709568 379.80490866675973 328.70536417886615 1995.3637473322451 374.12744244560599 256.37965072877705 200.50559730827808 603.24526035785675 274.85354585573077 38.583284214138985 1287.2464494965971 20.129632297903299 198.91592706553638 319.64985512569547 595.08863238245249 727.46936550363898
leaf_count=4896 13988 26573 2604 38182 10655 22669 2065 2118 16842 2974 5709 4631 3990 4529 19858 3774 3768 2750 11580 2279 368 18411 239 3279 2600 6050 8619
internal_value=0 -0.00117316 -0.000642375 -0.00122714 0.000462576 0.00152865 0.00390844 0.00237943 -0.00253753 0.00179012 0.00333715 0.00226059 0.00794358 -0.00135904 0.00179698 0.00325591 -0.00193012 -0.00319978 -0.00244453 0.00569178 0.00755045 -0.00159892 0.0105425 -0.000414291 0.00157053 0.00299351 0.00516986
internal_weight=0 11779.4 10620.3 9261.79 4042.39 3058.72 1376.84 5738.95 5219.41 4997.08 1358.51 4568.3 545.119 3374.93 4171.91 2176.54 3046.22 428.776 2789.84 887.678 612.825 2186.6 399.935 1681.89 1288.87 914.738 973.542
internal_count=246000 193702 167129 150197 56885 42897 16949 52298 93312 47402 16932 42534 6294 55130 39560 19702 50601 4868 46833 7278 4999 35253 4229 25948 12424 8650 11223
is_linear=0
shrinkage=0.0152673


Tree=129
num_leaves=28
num_cat=0
split_feature=21 20 19 130 126 20 387 391 135 9 67 21 19 7 8 7 8 61 7 138 21 7 8 391 391 70 20
split_gain=205.657 139.206 99.6443 87.5354 70.2876 56.9047 50.6536 39.3619 36.4656 36.3011 35.4691 38.5944 34.198 33.8905 43.3859 30.5472 44.1643 30.5417 35.7287 30.39 30.0857 28.9846 35.1339 27.6436 26.8452 26.7797 26.7101
threshold=0.38034479682904804 -0.78572725661621623 0.13144353264597256 0.54166666666666685 -0.36265548339813924 0.03385880314723428 -0.094444699905398458 -0.80185022711144738 0.92132442284325655 0.70188133140376296 1.0000000180025095e-35 -1.7794007366397382 -0.29070757998552249 0.085712508552590674 1.0000000180025095e-35 -0.21608509050195931 1.0000000180025095e-35 0.0042499999999999977 -0.46140449088760332 1.5000000000000002 -2.1181404424088144 -0.046899297132549596 1.0000000180025095e-35 -0.92257102786474277 -0.66068996828538784 -0.21737451737451732 -1.6199246107459455
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 3 4 13 8 20 23 26 12 11 -9 -5 25 -15 -14 19 18 -13 -17 -6 -22 24 -1 -23 -3 -2
right_child=5 2 -4 9 6 -7 -8 10 -10 -11 -12 17 15 14 -16 16 -18 -19 -20 -21 21 22 -24 -25 -26 -27 -28
leaf_value=0.0016918860243548199 0.0030636439188646797 -0.0027441906345705611 -0.0050870553271386912 0.011643768106957294 0.011963933113155741 -0.0060047809623278775 -0.0033977314832032649 0.0073237929230834204 0.0052058526067267092 -0.0018861039720673163 0.0066427666693791507 5.0828071396277272e-05 0.00050872348135492574 0.0090560484244605385 0.0015590097714985424 0.0065924429374204924 0.0025173006502142575 -0.0010518586022238527 0.0038452891293773851 0.017279227608708748 -0.0024420485338963994 -0.0012304795380787543 -0.00060981191479471148 -0.0063677925987667356 0.0079661127398141674 0.0017291801190589162 -0.0031655290382289324
leaf_weight=232.19222845882177 178.58179308846593 506.08420337364078 923.03013845905662 118.12345903739333 47.169743165373802 1304.6920948605984 2273.8332394957542 381.99218308180571 156.77647120133042 318.94090402312577 623.26558134704828 797.69980901107192 654.68062764406204 264.66213729418814 574.0747085865587 269.46140350773931 716.38219396024942 561.21534634381533 2152.2877839207649 83.089198969304562 859.3863066714257 102.64864020049572 716.31739704497159 171.41880602389574 250.22738584503531 812.32565723918378 1462.3728960007429
leaf_count=1906 2038 7300 18988 1007 327 36472 36326 1975 2463 4689 4858 7039 8687 2810 8133 2946 9986 5024 17346 944 11127 1359 10124 1975 2570 10029 27552
internal_value=0 0.000758391 -0.000321174 0.000191327 -0.00070374 -0.00357482 -0.00184402 0.00284258 -0.00180573 0.00284939 0.0032515 0.00270592 0.00367454 0.00153834 0.0039372 0.00312179 0.00471323 0.00220053 0.00282242 0.00914544 -5.11067e-05 -0.000350933 0.00132142 -0.00170994 0.00526578 4.93131e-06 -0.00248175
internal_weight=0 14410.5 9490.44 8567.41 6406.73 3102.42 4249.58 4920.07 1797.73 2160.68 4516.46 3893.2 1841.74 2157.15 838.737 1723.61 1068.93 3511.2 2949.99 352.551 1975.75 1928.58 1069.19 403.611 352.876 1318.41 1640.95
internal_count=246000 177475 137352 118364 90105 68525 61833 40123 32053 28259 36242 31384 23570 28272 10943 22563 13876 29409 24385 3890 25507 25180 14053 3881 3929 17329 29590
is_linear=0
shrinkage=0.0152673


Tree=130
num_leaves=28
num_cat=0
split_feature=20 21 109 1 2 391 119 21 391 141 52 112 19 7 8 7 109 388 143 143 69 391 112 149 8 387 111
split_gain=201.808 141.028 124.788 71.2184 68.6799 56.8422 55.7422 53.3296 45.1454 39.7508 37.5626 36.3015 36.2699 37.4116 42.9963 40.7463 33.6515 32.5722 42.8953 31.762 31.289 31.1384 30.7034 28.4954 28.5188 26.1954 30.0754
threshold=0.33014794124083729 -0.73924480687859639 -0.58333333333333315 1.0000000180025095e-35 1.0000000180025095e-35 -0.80185022711144738 0.56168057210965439 -0.45447813724047786 -0.64052006669616957 -0.2407407407407407 3.5000000000003335 -0.58588632668844787 0.19388630579008007 -0.47409342539030908 1.0000000180025095e-35 0.035454375816383658 1.0000000180025095e-35 -0.77607244876232973 3.1666666666666674 1.0555555555555558 1.0000000180025095e-35 -0.30850937633859199 -0.53640371229698369 0.40272300543394141 0.54582142857142868 -0.31105068881099635 10125.472500000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 9 5 25 -4 11 -2 -7 23 16 -1 13 -10 15 -15 -8 18 -11 -13 -9 -17 -23 24 -3 26 -5
right_child=7 2 3 4 -6 8 10 20 12 17 -12 19 -14 14 -16 21 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0055317611098426277 -0.00079364554059077304 0.0071825621870081529 -0.0079619071260615092 0.0051164532400492886 -0.001584736402415925 0.0051886456042194882 0.0041036371663658285 -0.0055343553509173849 -0.0044495077107014848 0.0050715854482748556 0.00026621340882893501 -6.0036589202263733e-05 -0.0071819568324097346 -0.00015124500029032738 -0.0022734407482058938 0 0.0087357564041291545 0.00060869144118371745 0.063594781248852997 0.004399375565681438 0.0018700938369794276 0.026960417679210862 0.008228468278570468 0.00049914093894395093 -0.0017188932129682001 0.0014796820514170275 0.022793548544138943
leaf_weight=451.51691792160273 1077.4722313396633 754.58353759348392 401.92905806750059 469.97856372222304 1495.015418453142 196.34367250651121 927.72867980226874 1876.2962891813368 952.59300247207284 9.954372648149727 331.07061143219471 1913.6886338442564 325.98297920264304 630.44323538430035 1784.4293487295508 86.557920407503843 617.90968844294548 1275.8301444388926 4.2114838398993006 460.85895549505949 141.14074386656284 25.090568907558918 125.87801591679454 274.16695598512888 92.496168814599514 780.27316075749695 23.770980082452297
leaf_count=3500 15664 7241 8018 5159 21804 2490 6842 48007 15731 126 2783 17135 7480 9075 30439 1122 4657 14791 37 3814 3400 282 1475 3075 1160 10446 247
internal_value=0 0.000750422 -0.000299787 -0.00129549 0.000630686 -0.0024751 0.00292059 -0.00354629 -0.0019382 0.00271005 0.00496244 0.00156116 -0.00229674 -0.00185208 -0.000915514 0.00186553 0.00596227 0.000873569 0.0237512 0.000801899 -0.00501166 0.00725262 0.0114338 0.00481422 0.00619959 0.00323743 0.00599493
internal_weight=0 14412.3 9709.53 7298.29 2769.04 4529.25 4702.77 3094.91 4127.32 2411.24 1876.71 2826.06 3930.98 3604.99 2652.4 867.97 1545.64 1290 14.1659 2374.55 2017.44 237.527 150.969 1121.25 847.08 1274.02 493.75
internal_count=246000 178929 140198 113768 37656 76112 38731 67071 68094 26430 14282 24449 65604 58124 42393 11954 11499 14954 163 20949 51407 2879 1757 11476 8401 15852 5406
is_linear=0
shrinkage=0.0152673


Tree=131
num_leaves=28
num_cat=0
split_feature=21 411 21 17 128 130 10 2 90 411 10 70 11 10 11 163 149 120 162 140 67 434 143 149 13 390 149
split_gain=196.114 135.778 93.4329 78.2599 68.0816 55.8253 42.2705 51.0344 38.0962 38.0505 49.0306 34.5916 32.4439 32.1299 31.348 30.3427 30.8971 26.9889 25.0592 24.8814 24.7727 24.6231 26.5606 26.1025 24.4529 24.373 27.4785
threshold=0.38034479682904804 1.0000000180025095e-35 -1.3471229168525309 1.0000000180025095e-35 0.93792931034482774 2.0416666666666674 -0.49368218651284163 1.0000000180025095e-35 -1.0000000180025095e-35 1.0000000180025095e-35 0.045117428924598274 -0.3169884169884169 -1.0085258525852583 -0.53433594286499098 -1.2059955995599558 -1.0000000180025095e-35 -0.58342319933459807 -0.47212065813528331 900.31500000000017 -0.042079207920792068 1.5000000000000002 1.0000000180025095e-35 2.1666666666666674 0.29484182271864989 -0.45321438960535243 -0.62624219311346196 -0.36876546416773598
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 25 4 5 6 24 15 -3 10 18 -12 -10 -5 -15 -8 -17 -7 -2 -18 -16 22 23 -14 -4 -1 -27
right_child=9 8 3 13 -6 17 7 -9 12 -11 11 -13 21 14 20 16 19 -19 -20 -21 -22 -23 -24 -25 -26 26 -28
leaf_value=0.0011918078279473038 -0.0049605122446004235 -0.0047882928172253139 -0.0058019435176763371 -0.00047716849393765107 -0.0030350333229319996 -0.0024465848084110065 -0.0016984625564017944 -0.0012049242157624145 -0.005432647139378537 -0.006777117130860915 -0.0036235358804642876 0.0023157924239201855 -2.6420115763751346e-05 -0.0018561904805313963 0.0052763165338647723 0.0065994645366574912 0.0039247097836336148 0.0071884999150955333 0.0024712979053458503 0.00064170209265169802 0.019552537840754235 0.0051851790454034439 0.005126501586038737 -0.0045816079559279042 -0.00085013985134587485 0.0078240689042047389 0.0037500914230397687
leaf_weight=474.27893936261535 1349.3399073667824 912.21232694759965 317.29450871422887 327.06728503294289 1297.6090143173933 78.854038950055838 399.92557407170534 1542.7818706519902 325.19417110085487 654.89397174492478 369.36710243485868 598.74584979563951 915.72728630155325 143.88169317692518 1178.7445798460394 421.33740109205246 957.27250255458057 427.14691087603569 112.91954116895795 1247.2011225000024 29.393466509878635 178.8588049095124 156.90601122565567 433.99862605705857 890.99979836679995 588.66746198013425 1171.1561405062675
leaf_count=3783 31817 14575 5499 4660 18303 1125 5349 19429 5556 16341 7648 10433 12630 1864 11149 4466 11204 5152 2286 15021 251 2207 1983 6620 14394 3941 8314
internal_value=0 0.00073857 0.00148622 0.000808814 0.000146937 0.000805653 0.000377939 0.00105093 -0.00219818 -0.00350242 -0.00261576 4.00018e-05 -0.00101817 0.0037911 0.00483033 0.00220419 0.00280216 0.00566852 -0.00438009 0.0020717 0.00563441 -0.000160474 -0.000801763 -0.00149837 -0.00215879 0.00428941 0.00511879
internal_weight=0 14416.5 11493.6 9259.51 7580.42 6282.81 5776.81 4568.52 2922.9 3085.27 2430.37 968.113 2010.68 1679.09 1352.02 3025.74 2625.81 506.001 1462.26 2204.47 1208.14 1685.49 1506.63 1349.73 1208.29 2234.1 1759.82
internal_count=246000 177475 133904 117866 99942 81639 75362 55469 43571 68525 52184 18081 28996 17924 13264 36040 30691 6277 34103 26225 11400 23440 21233 19250 19893 16038 12255
is_linear=0
shrinkage=0.0152673


Tree=132
num_leaves=28
num_cat=0
split_feature=21 19 14 7 8 6 149 143 7 6 8 6 164 411 168 6 19 164 69 86 143 124 7 387 390 390 149
split_gain=190.667 133.485 105.944 89.9202 137.26 111.098 58.8996 42.5663 40.3907 38.128 50.5048 40.2232 37.8143 37.3336 36.371 36.2424 33.7379 36.2534 32.7851 28.8459 27.6607 27.8823 27.3116 27.2698 27.6219 26.866 26.2167
threshold=0.38034479682904804 1.0000000180025095e-35 -1.0000000180025095e-35 -0.46140449088760332 1.0000000180025095e-35 -0.017790309106098575 -0.26291118615250192 2.6111111111111112 0.0055980593394289986 0.050467836257309946 0.51063775510204101 0.55931495405179621 72003.240000000005 1.0000000180025095e-35 2.7500000000000004 0.40024227234753557 0.19388630579008007 36029.92500000001 1.0000000180025095e-35 1.0000000180025095e-35 3.5000000000000004 1.6250000000000002 -0.0240094545002177 1.9319924473288361 0.42140107963884327 -0.50794380043825382 -0.33729530886354286
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 -1 12 5 6 -5 9 -7 -6 15 -12 18 14 23 19 17 -3 20 -11 25 -22 -17 24 -2 -4 -26
right_child=13 16 3 4 7 8 -8 -9 -10 10 11 -13 -14 -15 -16 22 -18 -19 -20 -21 21 -23 -24 -25 26 -27 -28
leaf_value=-0.0022153472413178653 -0.0032862742618127252 -0.0023627559706445676 -0.0037254892691147325 0.006304340320089627 -0.003922581143647328 0.0012392626899669266 0.0017468722468102018 0.0057935251378608008 0.011090071046100906 0.00016097942907312515 -0.0064573318700458949 8.4710326632950132e-05 0.0050164890149998831 -0.0067151139241331476 0.010696300202700633 -0.002937124841170975 -0.0053236111122326197 0.0046121382957498135 0.0042457827536607875 0.00905448200615485 0.0022869975590754077 0.022737100128612027 0.0071695252669619442 -0.0082684610454150723 0.0060331112514355033 -0.00032987665343055912 -0.001523390516005272
leaf_weight=1679.7690178155899 1678.1294569578022 1180.8442252594978 1048.2002805806696 1057.0288038048893 433.0242156162858 114.42903850413859 1785.9781501032412 365.51965675130486 729.07424857839942 843.90994683280587 255.98308805003762 1494.3794200047851 269.32848505303264 650.88285805471241 46.672754703089595 69.508274054154754 775.84046620130539 202.7689829878509 250.09455159679055 94.636641101911664 102.41963337734342 18.467901952564716 509.84671534225345 199.31751209869981 154.09633252769709 1140.4537798482925 346.39023428596556
leaf_count=21072 36991 19339 13869 9566 5280 1287 18916 4078 5933 10129 3369 19999 2443 16341 781 928 15170 2705 2821 973 1108 191 5801 4736 2855 12498 6821
internal_value=0 0.000726942 0.00134385 0.00190971 0.00275995 0.00489396 0.00344488 0.000823108 0.00976519 0.000329495 0.000895876 -0.000867431 -0.000417321 -0.00346009 -0.00258202 0.00293511 -0.00277162 -0.00133344 -0.000993 0.00106924 -0.00156458 0.00551919 0.00594058 -0.00284737 -0.00234648 -0.0019605 0.000786389
internal_weight=0 14421.5 12262.1 10582.3 7753.32 3686.51 2843.01 4066.81 843.503 3701.29 3268.26 1750.36 2828.96 3075.49 2424.61 1517.9 2159.45 1383.61 2559.64 938.547 2309.54 120.888 579.355 2377.93 2178.62 2188.65 500.487
internal_count=246000 177475 140261 119189 86259 35702 28482 50557 7220 46479 41199 23368 32930 68525 52184 17831 37214 22044 30487 11102 27666 1299 6729 51403 46667 26367 9676
is_linear=0
shrinkage=0.0152673


Tree=133
num_leaves=28
num_cat=0
split_feature=20 1 391 392 14 135 10 416 141 414 149 11 7 387 168 7 8 391 393 391 8 17 163 149 124 7 135
split_gain=192.751 121.819 111.915 86.0451 85.5777 71.3101 52.8179 94.3896 54.2315 51.359 41.9648 41.8848 38.7843 37.4015 34.7092 33.8471 41.7971 35.204 30.312 29.8922 29.7793 29.206 28.5395 28.0076 27.6404 26.2161 25.3964
threshold=0.33014794124083729 1.0000000180025095e-35 -0.80185022711144738 0.2600851730102921 -1.0000000180025095e-35 0.6783110571081411 0.78512566955088603 -1.0000000180025095e-35 0.055555555555555559 -1.0000000180025095e-35 -0.56276057860585704 0.093784378437843804 -0.18075511600422964 0.77127500994991716 0.75000000000000011 -0.67014990358897797 1.0000000180025095e-35 -0.82711714898909583 -0.9189655172413792 -0.93013883649556617 0.51063775510204101 -1.0000000180025095e-35 -0.078749999999999973 -0.17130952474660419 2.6250000000000004 0.26435280213970275 0.457168894289186
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 19 5 -3 10 7 8 -6 -5 18 23 -12 15 24 -9 17 -17 -4 -1 25 -13 -11 -2 -7 -14 -24
right_child=11 4 3 9 6 14 -8 13 -10 22 12 21 20 -15 -16 16 -18 -19 -20 -21 -22 -23 26 -25 -26 -27 -28
leaf_value=-0.0016251684007571822 -0.002313787971250657 -0.0013498578868320198 0.037965935858060781 -0.00087771493328437896 0.010169404399129028 0.00060157040560792989 -0.00027019109322328448 -0.0022020624325740745 0.0033890851709837584 -0.0016801066448476859 -0.0044570753901427796 -0.005167092501387709 -0.0010145169966033105 -0.0013058387255771207 0.0082770820930886634 -0.00084508591751902037 0.0017359472987624491 0.0075367884824290802 0.0015571276637091178 -0.0084025203070403637 -0.0029161611612411897 0.00027988648278472986 0.0031747273987380144 -0.0062168971464122954 0.015765183786820319 0.0040876765682310474 0.0074291450314945134
leaf_weight=228.03833943419158 666.16805682331324 1086.2489027883857 5.2068493179976931 847.3325497508049 759.68400771915913 743.43563831225038 750.40920154377818 223.19397213310003 438.88976679742336 210.6750435680151 1430.2658520136029 312.81808139011264 747.87874772772193 485.19631610997021 204.69104759395123 134.28223590739071 920.28265962377191 806.17105989158154 578.73418099619448 476.47576043382287 1184.904930466786 849.1911160312593 1342.1821555513889 1250.0396899078041 29.019669070839882 341.01121202856302 440.06055998057127
leaf_count=2969 15001 13765 65 10049 7212 9494 6267 2711 4835 2272 22012 6130 10621 6330 1936 1679 11070 7740 8216 8635 18939 15835 13396 30105 309 4842 3565
internal_value=0 0.000731625 -0.000386917 0.000119352 0.00249153 -0.00103479 0.00341713 0.00415394 0.00769523 0.002262 -0.00188422 -0.00347687 -0.00248497 0.00249778 0.002683 0.0033878 0.00406339 0.00633032 0.00191035 -0.0062229 -0.00124017 -0.00117922 0.00360148 -0.00486515 0.00118703 0.0005754 0.00423106
internal_weight=0 14414.3 8809.91 8105.4 5604.36 5265.15 4518.11 3767.7 1198.57 2840.25 4288 3078.22 3704.06 2569.13 977.146 2083.93 1860.74 940.453 583.941 704.514 2273.79 1162.01 1992.92 1916.21 772.455 1088.89 1782.24
internal_count=246000 178929 117320 105716 61609 76434 47844 41577 12047 29282 64695 67071 56414 29530 11739 23200 20489 9419 8281 11604 34402 21965 19233 45106 9803 15463 16961
is_linear=0
shrinkage=0.0152673


Tree=134
num_leaves=28
num_cat=0
split_feature=20 21 109 149 119 20 130 1 10 416 21 391 387 20 154 10 6 155 25 141 414 9 35 140 149 390 111
split_gain=187.689 166.571 87.7425 58.7785 52.2159 51.5864 45.2905 42.0155 46.2848 51.4639 35.1309 34.7682 34.3309 33.928 32.9094 29.6251 28.6413 29.1272 31.3219 28.225 28.0552 27.553 26.9588 30.9191 29.0578 26.8171 25.7186
threshold=-0.8326318653753304 -0.4706364644200467 -0.41666666666666657 -0.36876546416773598 0.72377830750893934 -1.8843834570786695 0.29166666666666669 1.0000000180025095e-35 0.72043675319324285 -1.0000000180025095e-35 -1.811377762099047 -0.81178185562575544 -0.085097128818110032 0.58744417577269659 2.785714285714286 -0.32941903584672433 -0.62222222222222212 37060.897500000006 -0.1938 0.46296296296296297 -1.0000000180025095e-35 0.70188133140376296 0.00095 -0.22524752475247523 0.11333086693797016 0.30932035181648104 18803.430000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=5 4 3 14 10 -1 12 11 9 -9 19 -7 26 -5 16 -13 -3 18 -18 -2 -6 -22 23 -12 -25 -14 -4
right_child=1 2 6 13 20 7 -8 8 -10 -11 22 15 25 -15 -16 -17 17 -19 -20 -21 21 -23 -24 24 -26 -27 -28
leaf_value=0.0060614320004311519 0.0060632804496118763 -0.0044684674449311798 -0.0030084864220178724 -0.00098041584410637345 0.0004580547360897825 -0.0054486838197235028 -0.0013007945206507485 0.009106226528586156 -0.00063082009765330898 0.0028766753746830966 0.0026147769893961085 -0.0014402485469072696 -0.0070036852414594253 -0.008126123807815808 -0.0027137096964688768 0.0020963208194913797 0.043574511020602627 0.016321736300331621 0.0046512553711553443 -0.0017779892277354709 0.0060968295770612285 -0.00098755983128636705 -0.0036562040520135299 0.00028962171148035401 -0.0046373218628727566 -0.0032067695050206672 0.013206580562312293
leaf_weight=747.00219297409058 361.69117451831698 58.546007150784135 1295.7245549932122 1889.5932123120874 459.98177707195282 207.93977929279208 1292.9490063432604 454.11694285273552 476.00021713599563 990.86893049255013 760.10845547169447 786.88994111120701 1480.9206990879029 169.18547217734158 145.13586096279323 1832.3984458521008 4.7472989484667769 64.671048555523157 386.62374980933964 149.56154884397984 850.73990084975958 148.0096359141171 541.43936102837324 874.13188914209604 407.54886101186275 628.85149090178311 22.817549332976341
leaf_count=4896 2749 919 24565 30510 5255 2761 27020 3514 3350 8720 9040 9825 35477 4326 2392 16346 67 708 5694 1211 7936 1622 7112 10624 5314 13620 427
internal_value=0 -0.0010796 -0.00248757 -0.000298868 0.00121897 0.00232755 -0.00374582 0.00173796 0.00348103 0.00484177 9.33436e-05 0.000550218 -0.00466513 -0.00157281 0.00366208 0.00103033 0.00547848 0.00677693 0.0051688 0.00375169 0.00360021 0.0050378 -0.000627377 0.000171597 -0.00127038 -0.00587671 -0.00271898
internal_weight=0 11993 7439.77 2718.5 4553.21 5495.22 4721.26 4748.21 1920.99 1444.99 3094.48 2827.23 3428.31 2058.78 659.724 2619.29 514.588 456.042 391.371 511.253 1458.73 998.75 2583.23 2041.79 1281.68 2109.77 1318.54
internal_count=246000 196588 145725 44616 50863 49412 101109 44516 15584 12234 36050 28932 74089 34836 9780 26171 7388 6469 5761 3960 14813 9558 32090 24978 15938 49097 24992
is_linear=0
shrinkage=0.0152673


Tree=135
num_leaves=28
num_cat=0
split_feature=21 19 14 10 130 149 7 8 152 130 6 414 143 11 1 388 19 147 138 14 109 1 164 391 248 409 7
split_gain=180.874 127.181 100.658 99.1793 78.0011 65.4164 47.4462 64.7691 46.1944 43.7863 40.8793 37.3647 36.5546 35.7214 35.3281 34.5 31.8857 30.7387 29.4929 28.2326 27.3184 26.0634 25.3935 25.0915 24.4715 24.0808 23.737
threshold=0.38034479682904804 1.0000000180025095e-35 -1.0000000180025095e-35 -0.58254360664743843 0.29166666666666669 -0.036521018148996602 -0.55072463768115931 1.0000000180025095e-35 0.31250000000000006 0.79166666666666685 -0.017790309106098575 -1.0000000180025095e-35 3.1666666666666674 0.37211221122112215 1.0000000180025095e-35 -0.74057845158849911 0.2162404761205379 0.12162162162162164 1.5000000000000002 -1.0000000180025095e-35 1.2500000000000002 1.0000000180025095e-35 35341.492500000015 0.22477087513936686 0.47222222222222227 -1.0000000180025095e-35 -0.0240094545002177
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 -1 12 5 6 -5 10 25 22 24 -7 14 19 -4 -14 -11 18 -13 -2 -10 -21 -3 -12 -8 -6 -9
right_child=13 9 3 4 8 11 7 26 20 16 23 17 15 -15 -16 -17 -18 -19 -20 21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0021690652864552475 -0.0084014492325821758 -0.0048282659594330937 -0.0035587200670955418 -0.00014626028308713175 0.0039143636530539223 -0.0027981308664375296 0.0063117115503801826 -0.0028007216196238292 0.0019775428390848004 0.0033662234648732686 0.012485820050564535 0.0014935416366743974 0.040439577735374564 -0.00039671467276825983 0.0016173324970281437 0.0035575609153811545 -0.0041741808405726154 -0.0016417193389114278 0.0082850190609088242 -0.0047515484265324686 0.010267440138667348 -0.00093693359717206813 0.00078057984353987629 -0.0011238993691026614 0.0014878907742311731 0.0086325781348862707 0.0025020231481089313
leaf_weight=1674.6911256425083 337.76068843901157 1349.7379266116768 1170.5567420870066 809.93729186989367 386.29479605704546 805.94098106585443 812.1947546992451 246.21814215928316 1034.6174248289317 390.05219096317887 288.12201813980937 1355.0545097794384 5.9721401631832114 720.77316637523472 413.87606476806104 190.70235674455762 195.74877780303359 682.59098515100777 168.41546372137964 1392.9856776818633 102.47489438951015 605.58888284116983 215.37816883437335 34.053348526358604 359.14588090777397 779.54421612992883 954.42997716739774
leaf_count=21072 8407 24668 18438 8651 4131 10593 7294 2867 10721 5744 2170 14276 56 13674 5364 2288 3604 7787 1749 34254 1019 12190 3198 356 3287 7360 10782
internal_value=0 0.000705937 0.00130653 0.00185652 0.00252056 0.00166475 0.00308295 0.00405707 0.0049377 -0.00271704 0.00618114 1.17229e-05 -0.00142618 -0.00338214 -0.00220085 0.00476398 0.000830357 0.00104256 0.00225132 -0.00429912 0.00273436 -0.00360047 -0.00405057 0.0110191 0.004841 0.00707802 0.00140667
internal_weight=0 14425.8 12274.8 10600.1 8819.03 6516.1 3504.1 2694.16 2302.93 2150.92 1493.52 3012 1781.11 3057.11 1584.43 196.674 585.801 2206.06 1523.47 2336.34 1137.09 1998.57 1565.12 322.175 1171.34 1165.84 1200.65
internal_count=246000 177475 140261 119189 93043 69812 35407 26756 23231 37214 13107 34405 26146 68525 23802 2344 9348 23812 16025 54851 11740 46444 27866 2526 10581 11491 13649
is_linear=0
shrinkage=0.0152673


Tree=136
num_leaves=28
num_cat=0
split_feature=20 1 19 391 391 14 135 149 7 8 10 387 10 391 391 391 11 16 130 168 390 391 29 209 164 67 391
split_gain=183.069 114.832 108.704 101.037 80.5695 79.5094 71.6751 54.791 50.8629 68.034 62.0107 48.0745 45.3381 41.1457 55.1918 39.2976 36.3366 35.0022 32.8942 31.2051 30.4376 29.2779 34.1369 27.9852 26.9023 29.5074 25.5131
threshold=0.33014794124083729 1.0000000180025095e-35 -0.23999248241935275 -0.80185022711144738 -0.63378138164839226 -1.0000000180025095e-35 0.5653098420413124 -0.31246867809080014 -0.55072463768115931 1.0000000180025095e-35 0.69653893695920899 0.42612580082725582 0.75738222771597319 -0.84913404291403738 -0.64052006669616957 -0.65476695674678731 0.093784378437843804 -1.0000000180025095e-35 0.70833333333333337 1.0000000180025095e-35 0.25024646407256618 0.12742144408804593 0.12750000000000006 2406.7943018056217 30463.627500000006 1.0000000180025095e-35 -0.66068996828538784
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 12 -4 15 -3 7 20 24 10 11 26 -1 -2 -15 -5 -16 -18 -9 -8 -6 22 23 -22 25 -7 -10
right_child=13 5 3 4 6 8 19 18 9 -11 -12 -13 -14 14 16 -17 17 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.00873501557402976 -0.0090854697690747471 -0.0012951514527058631 -0.0066360948982328522 -0.00058747653124066504 -0.0010911872122161255 -0.0020820766298834678 0.0010037288578664623 -0.0034328062698147734 0.0044471261047936816 0.0018526406520627955 0.0017271495855392441 0.0023754875695995853 0.00088556987121021378 0.0054866657924814563 -0.0047886406238437209 0.0088535166590004918 -0.0059056673260242812 0.0006545497007751916 -9.1899440701975722e-05 0.0063667769199273359 0.0094518230480048308 -0.00025930364902919005 -0.0073861435735017916 -0.0012994271819568816 0.0075426334461039619 0.0072153904620961586 0.01041381471148084
leaf_weight=401.66234324499965 271.68162905052304 1082.6214298419654 653.20694672875106 150.03757189586759 975.1887569129467 678.54824349656701 1180.7291265148669 2851.2932878751308 214.07902537845075 1708.2504492998123 562.72884062305093 307.42179589346051 304.20389495790005 172.91614238731563 1638.0271489620209 314.13002496957779 256.09026141837239 721.5379114896059 912.44013534858823 323.88268542475998 287.10915697738528 336.72614900767803 40.024380153045058 68.371550124138594 96.964527264237404 89.665198635309935 878.78683454915881
leaf_count=3579 6506 13765 11129 1620 13808 7966 14471 42545 2442 19986 4407 3471 2571 3259 38721 3043 5058 13527 12806 2925 2870 4724 454 775 839 969 7764
internal_value=0 0.000710973 -0.000376947 -0.000879117 -0.000372274 0.00241615 -0.000783322 -0.00159585 0.00330389 0.00408865 0.0060294 0.0077513 0.00536636 -0.00340027 -0.00284249 0.00578314 -0.00339699 -0.00105539 -0.00262535 0.00216496 0.00066821 0.00302355 0.00584038 0.00735865 -1.57113e-05 -0.000983368 0.00925442
internal_weight=0 14418.1 8799.01 8093.14 7439.93 5619.07 6975.77 5471.15 4536.44 3671.27 1963.02 1400.29 705.866 3060.25 2788.57 464.168 2615.66 977.628 3763.73 1504.61 1707.42 732.231 395.505 355.481 865.178 768.213 1092.87
internal_count=246000 178929 117320 111170 100041 61609 95378 77982 47844 38070 18084 13677 6150 67071 60565 4663 57306 18585 55351 17396 22631 8823 4099 3645 9774 8935 10206
is_linear=0
shrinkage=0.0152673


Tree=137
num_leaves=28
num_cat=0
split_feature=20 21 109 149 14 20 128 411 391 67 29 392 21 70 6 391 0 20 19 19 141 119 391 391 135 152 155
split_gain=177.971 157.173 87.1336 58.5778 51.1097 48.6708 46.5023 42.0447 44.6139 40.9148 40.6213 36.9435 34.2695 33.997 33.6778 46.996 35.6542 33.0414 31.5317 29.9223 29.3304 28.9241 27.8136 27.4951 26.7471 24.7462 24.1019
threshold=-0.85099376108228075 -0.4706364644200467 -0.41666666666666657 -0.36876546416773598 -1.0000000180025095e-35 -1.8843834570786695 0.054610344827586213 1.0000000180025095e-35 -0.84913404291403738 1.0000000180025095e-35 0.014350000000000017 0.063469190079650975 -1.7794007366397382 -0.30540540540540534 -0.48520467836257303 0.12650512597654215 1.0000000180025095e-35 0.58744417577269659 1.0000000180025095e-35 -0.39580668621267479 0.94444444444444453 1.046781883194279 1.4004253102747959 -0.16577837173759505 0.457168894289186 4.6875000000000009 178195.20750000005
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=5 4 3 13 -2 -1 10 8 -4 12 14 21 -7 -3 24 16 -16 -5 20 -17 22 23 -14 -10 -6 -15 -13
right_child=1 2 7 17 6 9 -8 -9 11 -11 -12 26 18 25 15 19 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0059065673904986349 -0.0023825551582348334 -0.0010760073392129068 -0.0082432417532418006 -0.00093292217526419539 -0.0026731413345459703 0.0059826550440517951 -0.00019941504824042521 -0.0062666968286338443 -0.010746478822119853 0.0053390606011856113 -0.0010538176045646718 -0.00069292714342931842 0.0020503016503120503 0.0072585487973237809 0.0083243147362250351 0.029511130162734604 -0.00265149299890057 -0.0080217289448272239 -0.0032562165454207061 0.001576830026605661 -0.0023239931581154295 0.0014501385461781478 -0.0077095527272616569 -0.0036883591323309292 0.0061694366707411886 -0.0056393896992267363 0.010097971648170443
leaf_weight=750.01711139455438 777.45769465342164 227.48682781308889 327.50367634929717 1905.6481666620821 256.96176819503307 314.47868318855762 1484.1929506398737 1111.7259122431278 141.17764709144831 627.25125359743834 416.26349494978786 1206.2219239939004 2772.6425531059504 404.69792223535478 833.14774373173714 8.9156522527337057 73.780634637922049 167.12577974610031 410.32225996628404 629.67596924677491 463.91410030052066 232.02442331425846 69.214275669306517 1659.6699173990637 115.33781693130732 36.964088469743729 50.011783132329583
leaf_count=4896 9383 3835 7525 30701 2863 1650 16975 27216 3463 5610 4883 21059 25056 5431 7678 67 907 4326 5447 7343 5003 4582 719 37044 1056 575 707
internal_value=0 -0.00104036 -0.00240745 -0.000238565 0.00117984 0.0022926 0.00190768 -0.00366317 -0.00286003 0.00170848 0.00325137 -0.00232076 0.00114096 0.00368429 0.0041906 0.00518352 0.00742092 -0.00150962 0.000728463 0.00199029 0.00122599 -0.00359296 0.00180885 -0.0042479 4.35252e-05 0.00615628 -0.000254502
internal_weight=0 12066 7470.26 2741.92 4595.73 5407.84 3818.28 4728.34 3616.61 4657.82 2334.08 3289.11 4030.57 669.149 1917.82 1545.52 906.928 2072.77 3716.09 638.592 3305.77 2032.87 2841.86 1800.85 372.3 441.662 1256.23
internal_count=246000 197619 146464 44868 51155 48381 41772 101596 74380 43485 24797 66855 37875 9841 19914 15995 8585 35027 36225 7410 30778 45089 25775 40507 3919 6006 21766
is_linear=0
shrinkage=0.0152673


Tree=138
num_leaves=28
num_cat=0
split_feature=21 411 119 141 165 10 109 389 8 130 10 0 143 112 411 10 11 10 7 13 155 29 124 21 135 149 388
split_gain=171.172 123.175 93.5745 78.0506 55.0768 48.7057 48.2671 46.3488 52.9276 43.6859 41.6194 38.1661 37.6753 37.1892 35.8523 46.0624 32.8693 34.6325 32.7808 29.7547 28.8338 27.2196 25.8953 25.506 24.6585 24.0413 23.3134
threshold=0.38034479682904804 1.0000000180025095e-35 0.72377830750893934 0.055555555555555559 159038.95500000005 -0.58254360664743843 0.25000000000000006 -0.049701400783668102 0.51063775510204101 2.2916666666666674 -0.10719681362450212 1.0000000180025095e-35 0.27777777777777785 12.176752371482237 1.0000000180025095e-35 0.045117428924598274 -0.78685368536853673 0.78512566955088603 0.085712508552590674 0.93687578784058967 93348.045000000013 0.10285000000000001 0.37500000000000006 -0.91949617505527348 0.72934386391251527 0.86906589211356999 0.45678925033826762
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 5 9 -1 13 8 18 10 -5 16 26 -4 15 20 -3 19 -7 -18 -2 -14 -9 -12 -17 -20 -8
right_child=14 11 6 4 -6 7 12 22 -10 -11 23 -13 21 -15 -16 24 17 -19 25 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0016109081127335355 -0.0047136013907966255 -0.0051285452703420682 0.0031807313204591241 -0.0040739826882295587 0.0051922521346023237 0.0032697258992669606 0.0069346558784202884 5.8371394316797314e-05 -0.00030797235937122462 0.0037096601038648829 0.0020452781370252165 -0.0069482431324691014 0.01345508574630818 -0.0079158960475816682 -0.0065254529486240657 -0.00065166751163449972 -0.00054768090887916772 -0.0051099576132806884 0.0087404073600406314 0.0054407870472603865 0.0044322571316830241 0 0.0042096740522658879 -0.0017187360237707003 0.0076335818687783405 0.0013634394512950729 -0.0016634042387604229
leaf_weight=759.12015251629055 1353.3806639220566 471.1832663025707 1906.5359350517392 1341.690926939249 314.5009576138109 798.07503799535334 216.01875694468617 1621.9606132451445 468.9321000892669 344.36443147808313 596.52007512375712 338.41137057542801 255.87528524175286 72.46553035825491 638.5687706656754 869.93883363157511 1534.3747528474778 341.06675327010453 700.37548296898603 220.94747090898454 84.233330186456442 40.707018170505762 448.17433989234269 1405.1195885315537 92.398660456761718 124.36127411574125 108.9876144900918
leaf_count=11547 32465 8147 19599 20809 3232 7637 2261 17948 6153 4206 4998 5589 2385 909 16341 16516 22816 3917 6526 3102 1638 475 4372 18454 1565 1318 1075
internal_value=0 0.000684657 0.00139348 0.000649502 -0.000932244 0.00193777 0.00394246 0.00258729 0.0041913 -0.0014573 -0.00199243 -0.00212295 0.00766161 0.00276902 -0.00330219 -0.00244028 -0.00148291 -0.000658736 0.00549695 0.000201421 -0.00417081 0.0116116 0.000961853 -0.000592332 0.000135743 0.00763975 0.00402397
internal_weight=0 14429.8 11523.8 8923.19 4002.2 4921 2600.59 4161.88 2091.74 3687.7 3343.33 2905.98 621.589 1979 3038.52 2399.95 2567.57 2096.39 1622.81 1755.32 1437.61 296.582 2070.13 2001.64 962.337 824.737 325.006
internal_count=246000 177475 133904 107200 51699 55501 26704 43954 21634 48467 44261 43571 6196 20508 68525 52184 37982 29835 15481 25918 34103 2860 22320 23452 18081 7844 3336
is_linear=0
shrinkage=0.0152673


Tree=139
num_leaves=28
num_cat=0
split_feature=20 391 391 21 109 391 119 19 391 20 124 21 38 166 19 21 128 128 109 70 10 60 13 10 147 126 109
split_gain=173.987 125.209 152.076 119.037 94.2231 84.1733 64.4641 58.0426 57.6933 48.2537 43.0547 38.9152 36.8383 36.0906 33.6093 33.5919 32.2043 30.9641 30.1894 29.439 29.1037 27.708 26.0774 24.1555 24.0381 27.2002 23.3833
threshold=0.41281381511244647 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.58333333333333315 -0.92257102786474277 0.51281287246722307 0.042042249439647579 -0.65476695674678731 -1.417518363968721 2.8750000000000004 -0.32426629406169244 0.001749999999999974 207618.10875000004 -0.31528071226839544 -1.0000000180025095e-35 0.73794827586206913 0.34483620689655181 1.0000000180025095e-35 0.41891891891891897 0.77853316852080767 -0.029699999999999997 1.0908562009114713 0.44176624090097522 -0.25675675675675674 -0.33249865977212728 2.4166666666666674
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 8 6 10 -1 14 9 -3 -6 19 21 18 16 -4 23 22 -16 -8 -5 -17 -2 -11 -10 25 -21 -20
right_child=11 2 3 4 7 -7 12 -9 15 13 -12 -13 -14 -15 17 20 -18 -19 26 24 -22 -23 -24 -25 -26 -27 -28
leaf_value=4.3634562224200785e-05 0.0081253118064145494 0.001510788910190602 0.00711262520309226 0.00073357962586742629 0.0024547916026798943 -0.0075306167772908944 0.0037405079919328125 -0.0052803463100151828 0.0098562347005418105 -0.0015207605303986626 0.018501296566560584 -0.0054886050832327555 0 0.0057695262021999604 0.0014696719698446183 0.015535744556005822 -0.0045936657229967417 -0.0023279076896332712 0.0075494499770923538 0.014931612214588398 0.0027524806686039772 -0.0021621385179152399 0.0045941832537388459 0.0027329087116069236 0.0017966597841425609 0.0046408096989262069 0.029771724817563568
leaf_weight=665.59989518858492 65.512957474216819 369.38119592890143 190.53887882828712 1410.9246698059142 809.53294396400452 698.06071162596345 993.67276436835527 846.37221825681627 227.6179495677352 3095.9660355467349 37.180862206965685 1419.8250871803612 351.45222551003098 148.26283807680011 1892.6288087777793 226.19291965849698 817.66071779839694 679.05475579947233 671.54757055267692 91.660515494644642 53.179273407906294 811.15442847646773 170.71753554604948 225.59969426319003 298.59307833388448 184.85931758210063 11.352151941508053
leaf_count=8194 986 3718 1272 16385 7460 12445 7904 18986 1884 52018 435 38225 3224 1902 17791 2624 14600 6922 5444 821 475 12645 2734 1674 3105 2036 91
internal_value=0 0.000584147 0.00102067 0.000547837 -0.000601266 -0.00382746 0.00244759 -0.00157879 0.00646145 -0.000955444 0.00223913 -0.0039249 0.0045156 -0.00160994 0.000925727 0.00894405 -0.00188033 0.000463254 0.00545761 0.00192824 0.0131389 -0.00138124 -0.00119813 0.0063334 0.00484189 0.00809342 0.00794088
internal_weight=0 15167.6 13803.9 12702 7911.73 1363.66 4790.25 5888.51 1101.97 5042.14 2023.22 2296.49 2028.02 4232.61 2762.22 732.59 4084.34 2571.68 1676.57 1986.04 279.372 876.667 3266.68 453.218 575.113 276.52 682.9
internal_count=246000 194144 173505 163130 120482 20639 42648 97700 10375 78714 22782 51856 16663 71254 25985 6657 69352 24713 13439 22347 3099 13631 54752 3558 5962 2857 5535
is_linear=0
shrinkage=0.0152673


Tree=140
num_leaves=28
num_cat=0
split_feature=20 21 109 130 129 21 19 20 21 19 7 67 135 38 13 69 143 149 390 130 416 11 149 129 111 165 60
split_gain=169.444 116.476 107.307 57.7192 55.7759 46.6411 42.5964 41.5687 39.8373 38.3525 34.935 34.6109 34.2274 33.7644 33.07 30.9186 29.7891 29.5291 29.4957 28.652 33.1047 25.5081 24.2607 23.9975 39.8544 24.4159 23.8606
threshold=0.33014794124083729 -0.73924480687859639 -0.41666666666666657 0.20833333333333334 -0.5108175359488899 -0.45447813724047786 -0.37481395413786084 -1.6973680938911146 -1.8821381414301499 0.1584827775435044 -0.44772034583566583 1.0000000180025095e-35 0.92132442284325655 1.0000000180025095e-35 1.1668767574905461 1.0000000180025095e-35 1.3888888888888891 2.0348680084906978 0.70381212032294349 1.0000000180025095e-35 -1.0000000180025095e-35 -0.85836083608360825 -0.57728082535034619 -0.4711702806277725 25323.367500000004 179479.27125000002 -0.028849999999999997
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 4 6 -3 26 -4 -6 -1 10 -8 13 18 16 19 -7 22 21 -5 20 -9 -12 -10 24 -23 -25 -2
right_child=5 2 3 12 7 15 9 14 11 -11 17 -13 -14 -15 -16 -17 -18 -19 -20 -21 -22 23 -24 25 -26 -27 -28
leaf_value=0.0056750186054633986 0.0070209257371820072 0.0059818871411831728 0.0084228915369165564 -0.00059569847242355056 0.0060589241321507897 -0.0052174936306008746 -0.0046772331188780231 0.0011981566251620696 0.0050732934232468746 -0.0076665779179812396 -0.0040269587631595778 0.0055376986603650593 0.0060503132122193591 -0.001496179157787689 0.0075489931326807314 0.0022169687137105639 0.0058503359730591722 -0.0079269893962571145 0.0089256746598996867 0.0023384110290693757 -0.0029593999468615255 0.0019954169768555273 0.00075443645957882696 -0.0016896065690023758 0.043840852635643267 0.0063944084234608227 -0.0013931438993894088
leaf_weight=834.27303276956081 84.930576480925083 611.92861621640623 81.542304575443268 1328.1543755382299 328.72091019898653 1823.6582674290985 1025.9428112953901 790.12940416671336 365.41667056083679 332.60252789966762 531.07728329673409 552.2645236775279 252.49641579203308 728.54250010475516 139.4427560120821 138.5202051885426 438.48084747418761 152.7829800285399 80.217954022809863 794.43378396891057 1019.3825784064829 560.84013409540057 1826.6564249433577 1552.2305827904493 5.1821532547473899 91.677053362131119 987.17573662847281
leaf_count=5080 1176 6474 768 21523 2197 48007 16948 9842 2939 7857 9448 4607 3406 6767 1669 3400 3387 2727 1108 9998 13721 7746 15951 23669 61 1036 14488
internal_value=0 0.000681173 -0.000278636 -0.00153964 0.00177079 -0.00328792 -0.00246756 0.000928668 0.00264058 -0.00267894 -0.00225301 0.00199075 0.00087617 0.00140458 0.00031021 -0.00468782 0.00221149 -0.00139012 -4.56873e-05 -7.44632e-05 -0.001139 -0.00102186 0.00147896 -0.000295254 0.00241006 -0.00123248 -0.000716867
internal_weight=0 14424.4 9678.78 5994.75 3684.04 3034.28 4333.88 3072.11 4745.63 4252.34 3919.73 3911.36 1660.87 3359.1 2743.39 1962.18 2630.55 2893.79 1408.37 2603.95 1809.51 2741.01 2192.07 2209.93 566.022 1643.91 1072.11
internal_count=246000 178929 140198 96297 43901 67071 70260 37427 38731 69492 61635 33651 26037 29044 35230 51407 22277 44687 22631 33561 23563 41960 18890 32512 7807 24705 15664
is_linear=0
shrinkage=0.0152673


Tree=141
num_leaves=28
num_cat=0
split_feature=20 21 109 149 14 20 119 391 7 149 387 149 70 20 21 141 171 143 143 140 119 392 506 391 109 111 157
split_gain=165.643 142.514 81.4613 55.5833 48.9331 45.6371 42.1529 40.6601 40.2145 41.6434 37.5554 34.3062 32.1333 31.3225 30.5788 30.082 28.7935 28.5801 27.6822 26.6309 26.4723 25.7673 24.6614 24.254 28.128 23.0481 22.6703
threshold=-0.85099376108228075 -0.4706364644200467 -0.41666666666666657 -0.36876546416773598 -1.0000000180025095e-35 -1.8843834570786695 0.72377830750893934 -0.84913404291403738 -0.55072463768115931 -0.057167895928611136 0.82392560611211862 -0.043796884470367906 -0.30540540540540534 0.58744417577269659 -1.811377762099047 0.092592592592592601 2.7500000000000004 1.5000000000000002 2.6111111111111112 2.8044554455445545 -0.19398092967818828 0.32399005994036206 1.0000000180025095e-35 -0.66068996828538784 0.91666666666666685 31263.221250000006 956.25000000000011
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=5 4 3 12 -2 -1 14 -4 20 16 11 21 -3 -5 15 -6 19 -11 -13 -10 -7 26 -16 -8 -25 -23 -9
right_child=1 2 7 13 6 8 23 10 9 17 -12 18 -14 -15 22 -17 -18 -19 -20 -21 -22 25 -24 24 -26 -27 -28
leaf_value=0.0056963384689602036 -0.0023873828128475457 -0.0010487686734800541 -0.008065772067400806 -0.00090648297133973435 0.0079124140152018688 -0.005133330787983852 -0.0034678918631216795 -0.002248716674660299 0.0057677896845242859 -5.1428619595702249e-05 -0.0057594099375264792 -0.0044140215258557458 0.0059782318237255978 -0.0078663200265058318 0.0015238575132082868 -0.00016311572068094672 -0.0004405982550790686 0.0049116533169971093 0.0014591869841481054 -1.6624339537168908e-05 0.0004260256634262315 0.0023822171652164987 -0.0017347420780551475 0.0039705873771377093 0.012381554948599428 0.049554245849516169 0.0094855482752422404
leaf_weight=754.18158220499754 777.33057689666748 227.03458284214139 423.24180911667645 1902.0754920132458 246.11065262928605 268.16355775296688 89.121062040328979 1055.0747182182968 1269.7281563468277 1545.6720255576074 955.75282122567296 1597.9951203428209 444.61747799627483 164.15709052048624 1130.5016924887896 186.92680580914021 272.42117657139897 326.71608704701066 209.21751771494746 213.56306403875351 770.61327833682299 401.07525750249624 1038.2011382132769 1039.2359783574939 103.10564039647579 2.2519014421850434 39.369504613801837
leaf_count=4896 9383 3835 10176 30701 1808 3367 908 22787 10547 15001 22318 35042 6006 4326 13136 1466 2525 2979 4108 1904 7162 6497 13239 10197 1018 37 631
internal_value=0 -0.00100689 -0.00231684 -0.000221148 0.00109985 0.00220724 0.0018095 -0.00353981 0.00164121 0.00240027 -0.00308771 -0.00231202 0.0035897 -0.00146457 0.000703667 0.00440689 0.00409057 0.000810128 -0.00372894 0.00492889 -0.00100104 -0.000595984 -3.18915e-05 0.0041379 0.0047398 0.00269272 -0.00181659
internal_weight=0 12032.4 7421.86 2737.88 4610.53 5421.06 3833.2 4683.98 4666.88 3628.1 4260.74 3304.98 671.652 2066.23 2601.74 433.037 1755.71 1872.39 1807.21 1483.29 1038.78 1497.77 2168.7 1231.46 1142.34 403.327 1094.44
internal_count=246000 197619 146464 44868 51155 48381 41772 101596 43485 32956 91420 69102 9841 35027 29649 3274 14976 17980 39150 12451 10529 29952 26375 12123 11215 6534 23418
is_linear=0
shrinkage=0.0152673


Tree=142
num_leaves=28
num_cat=0
split_feature=20 19 130 141 149 155 19 135 7 7 21 152 109 8 6 19 21 111 21 124 20 134 414 10 46 390 143
split_gain=162.962 121.011 105.062 102.158 72.9099 56.0168 54.8386 51.2819 59.928 48.8332 41.7303 40.9689 44.4108 40.6871 39.0927 38.4389 37.2579 37.2385 36.6347 34.443 31.299 28.2664 28.1748 27.9925 25.7293 25.0442 24.9528
threshold=0.41281381511244647 0.19388630579008007 1.0000000180025095e-35 0.055555555555555559 -0.028395032574785664 104349.91500000002 -0.31936837048240385 0.86482381530984209 -0.47409342539030908 -0.6171549418423834 -2.0089485232886477 3.9375000000000004 -0.41666666666666657 1.0000000180025095e-35 -0.017790309106098575 -0.38840974305326348 -1.0130370759385332 4026.9375000000005 -0.32426629406169244 1.1250000000000002 -1.7685268741381348 0.43492343934040051 -1.0000000180025095e-35 0.10335118802362314 -0.044499999999999998 0.71270649600295433 5.0555555555555562
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 4 9 16 -4 8 -8 -1 -6 12 -11 14 -10 -14 -5 -17 24 20 -12 25 -22 -24 -2 26 -15
right_child=18 -3 6 5 10 -7 7 -9 13 11 19 -13 15 21 -16 17 -18 -19 -20 -21 22 -23 23 -25 -26 -27 -28
leaf_value=-0.00085892921617927145 0.0096315274808349179 -0.0053282525186936734 0.010477875293079452 0.00031238747494123116 0.0086921606740430514 0.0032726834934354797 -0.0020853093429709655 0.0062197161917477029 0.0035309276124089661 0.0073220017041006396 0.0044291848218318474 -0.0025065274696651632 0.016874987003922797 0.0011805492460294606 0.01066684288354945 0.0016403128859442157 -0.0034463803098223385 0.0091216038266711003 -0.0053485865475309908 0.0070439591945444498 -0.0039309644511944337 -0.0026235577513097079 -0.0025392194399402883 0.0011800440139785422 -0.0019817647308839519 0.0099715377777660121 0.015497937196375454
leaf_weight=666.41688184812665 46.586372999474406 770.74116631038487 214.26656423509121 797.34044134616852 112.58219861239195 429.74142994917929 746.02016106620431 717.23915660753846 805.63158624060452 785.99802994914353 219.68576659634709 220.91723050177097 44.529733821749687 906.6872839499265 233.06147039309144 1400.769665421918 2620.2810033708811 175.23958856798708 1402.1402978319675 125.84458777867258 813.00039917975664 347.30274417065084 872.18210965767503 1023.4372052904218 828.39616437628865 93.006836768239737 29.248662643134594
leaf_count=7931 693 15665 1602 6618 679 4593 9833 7466 8953 7450 1499 2860 299 12504 2156 16009 41346 1790 38225 1339 12560 4749 13501 11275 12938 1118 349
internal_value=0 0.000563111 0.000879134 5.65307e-05 0.00123027 -0.00191203 0.00294874 0.00252988 0.0016894 0.00282083 -0.00042133 0.00375763 0.00433664 0.00285935 0.00514264 0.0028823 -0.0025668 0.00247904 -0.00381676 -0.000760819 -0.00109982 0.00112892 -0.00155193 -0.00052646 -0.00135092 0.00240468 0.00164098
internal_weight=0 15171.2 14400.4 10308 6460.6 3847.36 4092.46 3878.2 3160.96 3293.87 3166.73 2627.45 2406.54 2414.94 1038.69 1620.54 3417.62 1576.01 2277.12 3054.15 2928.31 1376.25 2708.62 1895.62 874.983 1028.94 935.936
internal_count=246000 194144 178479 129749 77192 52557 48730 47128 39662 36339 40853 28408 25548 29829 11109 18098 47964 17799 51856 40174 38835 18720 37336 24776 13631 13971 12853
is_linear=0
shrinkage=0.0152673


Tree=143
num_leaves=28
num_cat=0
split_feature=21 128 90 391 391 391 391 391 391 391 141 164 130 30 391 21 70 164 172 67 126 389 130 11 67 148 391
split_gain=154.867 109.369 94.1986 96.2155 152.818 69.6679 70.1891 55.3927 63.4565 54.4277 48.6107 46.1415 40.7564 35.0882 34.6092 41.3783 32.8989 38.4894 34.6105 32.8651 32.6788 31.7201 28.4332 27.8998 26.0598 25.5171 25.1965
threshold=0.39583775539690874 1.0677241379310347 -1.0000000180025095e-35 0.12742144408804593 -0.80185022711144738 1.0000000180025095e-35 0.049180694651566131 0.45527790155677295 0.51300508801153255 -0.92629748585859206 0.24074074074074076 127003.45500000002 1.2083333333333337 0.012149999999999982 0.10767533198381948 -2.0089485232886477 0.58494208494208511 82596.30750000001 6.7500000000000009 1.5000000000000002 -0.58173734248081266 -0.36312272686057057 1.0000000180025095e-35 0.16639163916391642 2.5000000000000004 -0.75435796269727373 1.5250622576103898
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 11 4 9 10 -7 -5 -9 -4 21 13 -12 19 -8 -16 17 22 -19 20 -1 -6 -2 -18 -23 -13 -10
right_child=16 -3 3 7 5 6 14 8 26 -11 12 25 -14 -15 15 -17 23 18 -20 -21 -22 24 -24 -25 -26 -27 -28
leaf_value=0.0031488473814048814 -0.0054543347550691833 -0.0025548056390071079 0.00081971485288727234 -0.0036003981395495242 0.0069176081595709645 0.011309576647563617 0.0013299170922767807 0.010212234697475953 0.00075026918579098863 -0.0071897622648636776 -0.00080340303580463243 0.042464735840206477 0.0056783726945452209 -0.0062492840344715644 0.031252358363142267 0.0066417476262513623 -0.0021161216415908624 0 0.018273057814233277 0.0097209616287156075 -0.0018893377719023672 0.0030194121006467552 -0.0016162304737825336 0.0059229007515366368 0.026765381730229985 0.0058350348077583639 -0.0060278515800232498
leaf_weight=345.20726757496595 1684.5890723988414 2131.0711249709129 398.04036444239318 806.11026155762374 753.89469102397561 549.0570866484195 440.92084756866097 162.804104199633 2211.5574552547187 389.23449960909784 1007.9522516094148 4.4759866856038562 290.83093853108585 326.65117172710598 16.975937083363533 281.74893552809954 297.37077827006578 146.22804027050734 28.60549939610064 65.367689795792103 2237.4062199629843 1794.5737846437842 624.3832491915673 151.46607613563538 10.745229985564945 150.58167975768447 135.31561723724008
leaf_count=4320 40072 29037 4583 11461 7248 4520 4814 1741 29934 6220 11688 41 3128 5066 90 2491 6530 2842 495 808 30530 17597 14519 2468 91 1668 1998
internal_value=0 0.000638302 0.00118875 0.00196377 0.00312776 0.00408677 0.00716534 -0.000116616 0.000998926 -0.00312942 0.00305573 -0.00109886 0.000641632 -0.00152479 0.00407436 0.00809094 -0.00320823 -0.00389607 0.00297671 -0.000938099 -0.00121217 0.00427714 -0.00442065 0.000577785 0.00316877 0.00700475 0.000355074
internal_weight=0 14510.5 12379.5 9249.76 5933.97 5146.7 1288.7 3315.79 2509.68 787.275 3858 3129.69 1298.78 2974.63 739.646 298.725 2932.64 2483.81 174.834 2647.98 2582.61 2559.21 2308.97 448.837 1805.32 155.058 2346.87
internal_count=246000 179074 150037 107604 62470 51667 11915 45134 33673 10803 39752 42433 14816 40724 7395 2581 66926 57928 3337 35658 34850 24936 54591 8998 17688 1709 31932
is_linear=0
shrinkage=0.0152673


Tree=144
num_leaves=28
num_cat=0
split_feature=19 409 14 7 8 6 19 13 7 135 143 149 6 8 19 149 498 7 10 387 135 67 6 149 111 7 6
split_gain=157.591 120.103 90.4041 66.3148 88.2573 67.7854 56.9265 46.3996 43.8935 41.3736 33.4234 32.6536 30.8752 46.9624 30.0536 29.7672 29.5557 28.8199 28.693 28.3931 27.0817 27.6675 24.556 23.9401 23.9165 23.6775 23.0339
threshold=0.066137329671330417 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.46687814890837837 1.0000000180025095e-35 -0.017790309106098575 -0.35101553262171653 -0.36749733346261992 0.0055980593394289986 0.49605103280680446 2.6111111111111112 -0.1987258706506824 0.075944026733500439 0.51063775510204101 0.19388630579008007 -0.26291118615250192 1.0000000180025095e-35 -0.016296572743671078 -0.94114819392940519 0.52077873246429163 0.83748481166464173 1.0000000180025095e-35 -0.34504594820384288 -0.26291118615250192 26225.921250000003 -0.22354916962119795 0.49949874686716794
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 19 20 5 15 -1 22 -7 11 12 24 -6 17 18 -5 -17 -14 -2 -3 21 -4 -8 25 -9 -20 -19
right_child=14 2 3 4 10 8 7 9 -10 -11 -12 -13 13 -15 -16 16 -18 26 23 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0069395595250427164 0.012100381827800584 -0.0007005801947433971 -0.0015421404807743763 0.0059936764508560616 -0.0034102013922801132 -0.0012688810528217356 -0.0057421205583596162 0.00059004890105372255 0.01097221077873636 0.002203268510810008 0.0070085601790547828 -0.0023649702024437715 -0.00057560317579372056 -0.00055312951412876362 -0.0058265806340510881 0.002143152372478919 0.031227667107055785 0.0037569279130576071 -0.0046341246812566976 -0.0058826724838855291 0.0044346510995964305 0.0041893490860065424 -0.0020497321058047481 -0.0042325013927400649 0.023835747410300746 0.003713784105190718 0.0098975188299151601
leaf_weight=200.68601810187101 31.585739674046636 891.24815657176077 1504.5634744632989 862.35287692397833 356.89270851761103 76.316015036776662 643.02152994088829 1133.0839039031416 554.3945649061352 1043.7974504455924 216.04049254395068 2201.1335420515388 250.96789991483092 1249.7969319671392 1020.3588157650083 1318.0200316980481 8.0470364764332754 559.01669271290302 123.15655986778438 343.28346054442227 266.55725877918303 224.99235968850553 1247.5672526992857 686.23760070838034 10.239442992955444 219.60557908564806 195.81784758903086
leaf_count=1608 583 11294 19061 8225 4643 902 11281 15517 4602 12779 2554 33725 3439 18115 23005 14437 80 6708 2300 5613 2610 2631 20609 13348 118 3911 2302
internal_value=0 0.000525919 0.0016797 0.00229942 0.00314486 0.00505755 -0.0010536 -0.00131075 0.00947659 -0.000446826 0.00123506 -0.00127674 0.000753615 0.00141674 -0.00395092 0.00377903 0.00233124 0.00387321 -0.00213701 -0.00214969 -8.8088e-05 -0.000790855 -0.0033109 -0.0025852 0.000810377 0.000686666 0.00536424
internal_weight=0 15357.8 8878.31 7643.78 5647.66 2819.13 6479.53 6278.84 630.711 4388.25 2828.53 3344.46 2612.49 2255.6 2080.94 2188.42 1326.07 1005.8 1060.59 1234.53 1996.11 1729.56 1890.59 1029 1143.32 342.762 754.835
internal_count=246000 202853 107216 90309 66007 28246 95637 94029 5504 62139 37761 49360 35207 30564 43147 22742 14517 12449 20142 16907 24302 21692 31890 19559 15635 6211 9010
is_linear=0
shrinkage=0.0152673


Tree=145
num_leaves=28
num_cat=0
split_feature=19 90 8 7 13 149 135 135 69 6 6 149 248 8 8 6 149 6 157 128 118 155 19 111 67 157 124
split_gain=153.473 111.796 96.6678 94.908 69.2516 54.0357 51.9052 45.8175 44.9409 43.1667 40.6925 39.7516 31.9685 31.0558 42.8042 34.1341 30.8998 30.6525 30.525 29.4684 29.4276 34.216 28.9857 27.7416 26.9384 24.8808 25.1544
threshold=1.0000000180025095e-35 -1.0000000180025095e-35 0.51063775510204101 0.069042731852957659 1.100940560457675 0.40272300543394141 0.46445929526123947 0.48754556500607543 1.0000000180025095e-35 -0.60369256474519617 0.55931495405179621 -0.56276057860585704 0.86111111111111127 1.0000000180025095e-35 0.052545918367346948 -0.028517126148705094 0.031129058073115359 1.0000000180025095e-35 1.0000000180025095e-35 0.30322931034482764 -1.0000000180025095e-35 116907.93000000001 0.19388630579008007 26225.921250000003 1.0000000180025095e-35 281.25000000000006 1.1250000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 8 3 4 6 13 9 22 20 -3 -4 -11 16 15 -15 -5 23 -7 -8 -17 -1 -22 -2 24 -13 26 -9
right_child=7 2 10 5 -6 17 18 25 -10 11 -12 12 -14 14 -16 19 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=-0.0041556442709610808 -0.0030088888497679855 -0.0038321282153421948 -0.0064024605005999742 0.0048454037285155429 0.007930601311135833 -0.0025513402296990992 0.002199981136043287 -0.0020797046487734147 0.0036473588866526778 0.0042686868035789289 -0.00054775818275741128 0.0011274914840196822 -0.0032559190043260967 -0.004081047751585967 0.0050544175164816234 0.012885084118677368 -0.0014878395912696154 0.0033349400805089422 0.0089202370761908775 0.0050145164926809873 -0.0015939405793824763 0.0068777485284726384 -0.0067303941776971181 0.028721113066917037 0.0081324937755893334 0.010796104357956512 0.0063424505407948103
leaf_weight=1154.3843546397984 1318.6045900825411 680.99530996195972 321.79604678973556 545.74504665285349 315.56243236362934 319.03395296260715 1233.2264785282314 464.08529582619667 339.73231249116361 518.64771565981209 2005.3011085391045 971.50705812126398 663.43607798777521 138.11960689164698 839.56522014737129 352.69156975857913 909.23777523450553 577.12196398898959 182.10984669998288 168.83371897041798 2203.3167189639062 116.50118944980204 789.51863219588995 9.0358282625675184 148.21185616590083 48.544473936781287 100.14475323818624
leaf_count=20814 24616 9605 4842 5573 3521 4065 13167 8366 4534 6062 30544 11763 8632 1845 10041 2868 11988 6839 1530 1492 29612 1202 18449 87 1691 642 1610
internal_value=0 0.0006077 0.00139534 0.00214482 0.000981819 0.00436853 0.000567359 -0.00333915 -0.00164091 -0.000339207 -0.00136178 0.000396838 -0.000343389 0.00573958 0.00375389 0.00754897 0.000600471 0.00122909 0.00307228 0.0103576 -0.00216085 -0.00116399 -0.00440749 0.00229073 0.00206418 0.000321556 -0.000566916
internal_weight=0 14714.1 10900.2 8573.08 5631.97 2941.11 5316.41 2720.9 3813.93 3901.07 2327.1 3220.08 2701.43 2044.96 977.685 1067.27 2037.99 896.156 1415.34 521.525 3474.2 2319.82 2108.12 1128.75 1119.72 612.775 564.23
internal_count=246000 192317 136155 100769 68046 32723 64525 53683 56162 49828 35386 40223 34161 21819 11886 9933 25529 10904 14697 4360 51628 30814 43065 13541 13454 10618 9976
is_linear=0
shrinkage=0.0152673


Tree=146
num_leaves=28
num_cat=0
split_feature=20 391 391 21 109 391 391 14 1 128 124 21 113 19 21 7 57 149 150 60 148 13 389 86 7 142 109
split_gain=155.262 115.503 141.292 105.047 84.2407 79.9213 53.8771 52.3304 55.6059 46.5423 41.0543 35.3113 34.2574 48.0431 32.2854 29.5761 28.9986 28.9448 27.6677 25.4465 24.5605 22.8669 22.4731 22.3821 22.3605 21.825 21.6029
threshold=0.41281381511244647 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.58333333333333315 -0.92257102786474277 -0.65476695674678731 -1.0000000180025095e-35 1.0000000180025095e-35 1.0360344827586208 2.8750000000000004 -0.32426629406169244 1.7868618572048882 -0.35101553262171653 -1.0000000180025095e-35 -0.10188467997760775 1.0000000180025095e-35 -0.057167895928611136 0.61857707509881432 -0.029699999999999997 1.0000000180025095e-35 0.87792107049355195 -0.035292170058631327 1.0000000180025095e-35 -0.43328979287180441 2.8437500000000004 1.2500000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 6 9 10 24 -3 -6 15 12 18 19 13 -4 21 -9 22 20 -5 -2 -17 -8 23 -14 -1 -15 -18
right_child=11 2 3 4 7 -7 14 8 -10 -11 -12 -13 16 25 -16 17 26 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.003674244821566015 0.0077144123242612432 0.0014030185320115336 0.011200105867538283 0.0013699771219652008 -0.0051734481194004112 -0.0073636853955900321 0.0043298456971429793 -0.0035321288647570471 0.0013093623492056012 -0.0015825882726338413 0.017844084341259454 -0.0052518988161911039 0.0061038214275335569 0.00073622445629977699 0.012645196642402783 0.0010556990232365047 -0.0013569130172885635 -0.0024036174687216455 0.0095178611569059473 -0.0020757356556048226 0.016279305272240866 0.013148167292343258 0.0035319465208608716 0.014035403900010915 0.0021594982999821807 0.0067894983323082492 0.022383313654293035
leaf_weight=238.79483798705041 66.533004462718964 370.69756176695228 116.60908705741167 1892.882113320753 786.044349482283 686.40286420471966 371.44866645336151 1652.6080817393959 1703.0431411545724 627.4612178504467 37.815228614956141 1389.9943092670292 611.85058215260506 2093.8367099836469 283.2805005107075 719.34777464903891 235.3750072941184 970.23592016287148 102.75698390230536 806.46355983056128 25.516697078943253 86.119206037372351 873.33275895938277 98.772203706204891 425.9216218534857 149.15568163245916 9.0712452232837659
leaf_count=3121 986 3718 740 21374 14354 12445 2934 29191 23553 6050 435 38225 4847 19663 3099 12111 2166 18079 973 12645 412 624 7114 690 5073 1298 80
internal_value=0 0.000548358 0.000965504 0.000508032 -0.000575537 -0.00371033 0.00618545 -0.00150597 -0.000935471 0.00228534 0.00209971 -0.00373843 0.00286708 0.00164519 0.00856504 -0.00207341 0.00443859 -0.000662251 0.00179502 -0.00131752 0.00159374 0.00601458 0.00519428 0.00722279 4.95145e-05 0.00114341 -0.000420907
internal_weight=0 15168.4 13817.3 12705.7 7890.25 1351.12 1111.55 5856.8 5070.75 4815.46 2033.45 2262.99 4188 2359.6 740.848 3367.71 1828.4 1715.1 1995.64 872.997 744.864 457.568 1583.96 710.623 664.716 2242.99 244.446
internal_count=246000 194144 173505 163130 120482 20639 10375 97700 83346 42648 22782 51856 36598 21701 6657 59793 14897 30602 22347 13631 12523 3558 12651 5537 8194 20961 2246
is_linear=0
shrinkage=0.0152673


Tree=147
num_leaves=28
num_cat=0
split_feature=20 411 391 391 90 10 391 67 130 141 20 391 391 11 90 7 391 122 223 388 130 166 154 13 143 11 391
split_gain=152.637 105.618 90.7418 107.991 95.4108 54.6955 48.3734 42.997 41.358 42.9182 37.3374 33.8318 38.9367 33.6883 32.6113 32.5947 33.9268 31.2112 30.8031 37.0332 28.5499 27.5364 26.9795 25.6542 25.5776 27.6845 25.0302
threshold=-0.85099376108228075 1.0000000180025095e-35 -0.84913404291403738 0.12742144408804593 -1.0000000180025095e-35 -0.5021975003433593 -0.92629748585859206 1.0000000180025095e-35 0.87500000000000011 0.055555555555555559 -1.8843834570786695 0.48751167347278374 0.51300508801153255 -0.78685368536853673 -1.0000000180025095e-35 -0.55072463768115931 1.4004253102747959 0.39655172413793111 -2884.6280000009515 -0.44491960834167915 1.9583333333333337 41959.080000000009 2.6428571428571437 1.0908562009114713 2.9444444444444451 -1.9969746974697469 -0.63378138164839226
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=7 2 6 4 26 20 -2 10 9 -7 -1 -5 18 -3 -15 -12 17 24 19 -13 -6 -14 -23 -16 25 -17 -4
right_child=1 13 3 11 5 8 -8 -9 -10 -11 15 12 21 14 23 16 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0049546833035342365 -0.00096224864156784753 -0.0069642866675003363 0.0050403710617596556 -0.0043339185211107682 -0.0037903000354644546 0.0043670969265731966 -0.0086906462887371104 0.005553823085097693 0.0069110943161242947 0.00019292249310022812 -0.0015344984242689182 0.10296015306134303 -0.0020282608733550207 -0.0054168459013790096 -0.0019492251449968407 -0.0051113680993549026 -0.0076163883607629386 -0.0003825776533958486 0.0059676088359728856 0.012705304441358695 0.004457145979882662 0.0072097859444380718 -0.0012812999687529926 0.006319691728672177 0.0094446968421834452 0.0029903913584598822 -0.0022342197604428536
leaf_weight=656.58335348591208 346.56918886117637 562.72063595615327 119.20872008241713 934.32044554874301 379.5613228045404 1488.4059532396495 422.37401202321053 734.70768640935421 730.11752577126026 942.35316003113985 899.00536666810513 1.5308149419724939 1998.0498037151992 712.19470779038966 1326.7109971605241 102.59849394857883 86.894492018967867 883.38068981841207 105.90271809324622 3.6893724072724572 130.78586108423769 160.6870988663286 187.23303350806236 93.00150490924716 135.95417255163193 1934.18681204319 1347.6389679163694
leaf_count=4249 5172 12538 1722 17236 7190 17483 8998 6257 8361 12917 9230 20 36278 14078 23728 1185 953 8107 1424 51 1962 1971 2921 1571 1149 17251 21998
internal_value=0 -0.000969816 -0.000197471 0.000254395 0.00165099 0.0029669 -0.00522046 0.00211473 0.00371656 0.00275278 0.0015748 -0.00185876 -0.000913561 -0.00363136 -0.00274675 0.00102329 0.00175787 0.00202789 0.00789704 0.043685 -0.00165788 -0.00133544 0.00261589 -0.00140029 0.00301208 0.00257732 -0.00163617
internal_weight=0 11993.1 9298.43 8529.48 5138.07 3671.22 768.943 5433.31 3160.88 2430.76 4698.6 3391.41 2457.09 2694.63 2131.91 4042.02 3143.01 3056.12 111.123 5.22019 510.347 2345.97 347.92 1419.71 2172.74 2036.79 1466.85
internal_count=246000 197619 145704 131534 71633 47913 14170 48381 38761 30400 42124 59901 42665 51915 39377 37875 28645 27692 1495 71 9152 41170 4892 25299 19585 18436 23720
is_linear=0
shrinkage=0.0152673


Tree=148
num_leaves=28
num_cat=0
split_feature=19 21 130 149 7 391 19 141 67 10 414 147 0 409 10 109 165 11 155 151 70 86 391 143 19 128 155
split_gain=147.781 124.982 97.5848 98.6652 65.8835 60.9288 43.9425 45.9236 40.0083 39.7156 39.0394 38.9136 36.9901 38.0837 35.4469 41.7329 34.96 30.3664 29.6572 29.6094 26.8989 26.5398 26.3256 25.4491 23.7081 23.6843 22.9738
threshold=0.19388630579008007 0.46486330130804837 0.54166666666666685 -0.028395032574785664 -0.46140449088760332 0.12742144408804593 -0.25931946189574345 -0.16666666666666663 1.5000000000000002 0.71247081444856486 -1.0000000180025095e-35 0.22972972972972977 1.0000000180025095e-35 -1.0000000180025095e-35 0.78512566955088603 -0.41666666666666657 91241.268750000003 1.0000000180025095e-35 173164.92750000002 0.64064261555806101 0.58494208494208511 1.0000000180025095e-35 0.95255065921527249 2.0555555555555558 -0.4294617065977519 0.20624137931034484 33998.602500000008
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 4 16 11 9 10 12 -5 -8 14 13 18 15 25 19 -3 -4 24 26 -12 -15 -9 -1 -6 -19
right_child=-2 17 8 6 5 -7 7 23 -10 -11 21 -13 -14 22 -16 -17 -18 20 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.017622405906226893 -0.0056834989240204898 -0.0042218866732011218 0.00085223976315489342 0.0070681800252329853 0.013365202737864191 0.00017325991793485146 -0.003288514260013664 -0.0039302927048184997 0.012572698179565033 -0.0011130526809920737 0.0002382045479775207 0.0014957136612303982 -0.0027237506001805533 0.0055505327595554424 0.0010451955576628541 0.0047033085317577323 0.0063076694051612276 -0.0027409640009575641 0.0095490851273979591 0.0083599927441690512 0.0051948660564339966 0.006538413706408285 -0.000135367382413061 0.0028761632244842152 -0.0025921551545008679 0.0056225390167482393 0.0059927005444969572
leaf_weight=13.361043047159908 1007.3516295142472 1487.7594191301614 1355.6637283731252 256.97179287299514 270.17642251029611 1490.4043536987156 748.07817482203245 2009.2174026649445 101.2454155869782 295.72393971309066 1434.0038839243352 876.52638390101492 258.03131596185267 1480.5726526286453 331.04678034037352 834.58237804844975 132.99949161708355 689.40267223492265 98.211444795131683 62.25946887396276 150.89441011287272 175.19707579724491 214.10534450039268 135.03968687914312 1287.5985620431602 147.97085487656295 77.421679951250553
leaf_count=97 23005 36400 17384 2386 2432 19648 11696 28702 1091 2562 17969 9298 3359 14824 2586 8560 1212 13797 977 629 2438 1822 2705 1700 15917 1528 1276
internal_value=0 0.000340324 0.000892871 0.000155472 0.00158176 0.00261575 -0.00137982 -0.00187985 0.00309763 0.00267536 -0.000404648 0.00409151 0.00281261 0.00326939 0.00552197 0.00669734 -0.00114231 -0.00287359 0.00144726 -0.00187669 -0.000677377 0.000930541 0.00482684 -0.00349714 -0.00237483 0.0106512 -0.0018459
internal_weight=0 16414.5 14009 10501.2 5446.93 3950.71 5054.23 4501.54 3507.83 552.696 2357.28 2460.3 3406.58 3148.55 1583.78 1252.73 1496.22 2405.48 1453.88 1363.22 917.719 1609.2 1694.68 2144.26 1300.96 418.147 766.824
internal_count=246000 222995 169084 128744 61907 44052 66837 61889 40340 4948 31487 24404 39249 35890 15106 12520 17855 53911 18361 16643 17511 19791 17529 30402 16014 3960 15073
is_linear=0
shrinkage=0.0152673


Tree=149
num_leaves=28
num_cat=0
split_feature=20 391 391 21 109 391 391 19 20 90 124 391 391 391 391 21 155 391 21 10 130 125 111 10 141 130 60
split_gain=148.098 110.104 133.277 100.207 79.7665 77.1463 51.3295 50.845 43.2083 42.3097 39.0484 37.2872 41.1035 47.2051 37.3527 34.1963 34.1217 30.8733 30.5111 29.7634 32.1001 31.6873 28.6597 27.536 26.365 30.4715 24.6197
threshold=0.41281381511244647 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.58333333333333315 -0.92257102786474277 -0.65476695674678731 0.042042249439647579 -1.417518363968721 -1.0000000180025095e-35 2.8750000000000004 0.12742144408804593 1.0000000180025095e-35 0.049180694651566131 0.45527790155677295 -0.32426629406169244 208036.77750000003 0.51300508801153255 -1.0000000180025095e-35 -0.2754429336629583 0.29166666666666669 -0.051724689870926786 3439.8675000000007 0.77853316852080767 -0.16666666666666663 2.5416666666666674 -0.029699999999999997
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 6 9 10 -1 -3 8 -6 -4 24 12 -11 -14 -13 26 19 -16 -8 -10 21 22 -21 -20 -5 -26 -2
right_child=15 2 3 4 7 -7 18 -9 16 11 -12 14 13 -15 17 -17 -18 -19 23 20 -22 -23 -24 -25 25 -27 -28
leaf_value=4.8370014301213269e-05 0.007577823488820969 0.0013268542970685095 -0.00021429894036067597 0.0034408020557911835 0.0023239246019278324 -0.0072546477110354028 0.005824071950527406 -0.0049869489380664524 -0.0036516532827082426 0.0029044657116936738 0.01727145007510306 -0.0034309308778762201 0.011942632780615976 0.003765131071492771 0.010793558386183219 -0.0051612310368583251 0.0056013967722430705 0.001689548727804573 0.014532383704963799 -0.00088333245805663431 0.0020950705091051704 -0.0040071720802358941 0.0077528157872067439 0.0022336416894105219 -0.00087662357035762949 0.0089335432250031727 -0.0020302529693323208
leaf_weight=664.50939041934907 66.875568812713027 371.81947851367295 1226.0581103861332 1026.8498377297074 812.92020710557699 679.08035140484571 460.31086783856153 825.2840414494276 1336.5987492352724 1480.6231934800744 38.391964573413134 320.18151677027345 303.89656123518944 369.00875472277403 95.292085606604815 1378.8076924942434 150.49968691915274 1029.0033791996539 232.42368906736374 1100.0413120314479 648.28847908042371 872.16087003238499 97.254801616072655 54.232202619314194 893.09042220003903 80.233917761594057 804.0186073705554
leaf_count=8194 986 3718 11909 10741 7460 12445 3558 18986 26774 11789 435 3250 2003 2849 776 38225 1912 10072 2624 16897 9765 14467 1439 475 10713 893 12645
internal_value=0 0.000534262 0.000940321 0.000494665 -0.000565154 -0.00363645 0.0059923 -0.00147327 -0.00089336 0.00222806 0.00203312 0.00306283 0.0043372 0.0074743 0.00115623 -0.00366321 -0.00151761 0.00247111 0.0083014 -0.0017844 -0.000862505 -0.00179355 -0.000173002 0.0122407 0.00173435 -5.68647e-05 -0.00128037
internal_weight=0 15168.1 13824.5 12705.7 7881.61 1343.59 1118.79 5843.05 5017.76 4824.06 2038.57 3598.01 2153.53 672.905 1444.48 2249.7 4204.84 1124.3 746.967 4054.34 2717.75 2069.46 1197.3 286.656 2000.17 973.324 870.894
internal_count=246000 194144 173505 163130 120482 20639 10375 97700 78714 42648 22782 30739 16641 4852 14098 51856 71254 10848 6657 69342 42568 32803 18336 3099 22347 11606 13631
is_linear=0
shrinkage=0.0152673


Tree=150
num_leaves=28
num_cat=0
split_feature=20 21 411 109 0 391 391 20 391 149 1 10 416 392 135 6 149 19 154 391 391 19 130 86 130 391 164
split_gain=144.321 124.467 76.4523 57.4363 43.794 56.4018 61.6927 40.8145 40.7534 39.756 37.5657 43.4964 50.9595 31.4984 31.1659 33.1897 34.3797 30.9631 30.5392 29.3702 28.0524 27.139 26.9631 26.7532 29.7097 27.4387 26.3885
threshold=-0.85099376108228075 -0.4706364644200467 1.0000000180025095e-35 -0.41666666666666657 1.0000000180025095e-35 0.12742144408804593 -0.66068996828538784 -1.8843834570786695 -0.84913404291403738 -0.36876546416773598 1.0000000180025095e-35 0.72043675319324285 -1.0000000180025095e-35 0.063469190079650975 0.43772782503037672 -0.51888888888888884 -0.36876546416773598 -0.24962301927574029 2.5000000000000004 -0.81178185562575544 0.45527790155677295 -0.35669443217215241 0.29166666666666669 1.0000000180025095e-35 2.7083333333333335 -0.64052006669616957 333306.65250000003
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=7 4 3 9 5 6 -2 -1 -5 18 17 12 -12 -10 15 -8 -17 -9 -3 -19 -7 -4 -15 25 -25 -21 -16
right_child=1 2 21 8 -6 20 14 10 13 -11 11 -13 -14 22 26 16 -18 19 -20 23 -22 -23 -24 24 -26 -27 -28
leaf_value=0.0053371216813671418 -0.0025404457381309783 0.0058431171882462928 0.010282799875276296 -0.007849348823092097 -0.0037215424236401807 -0.0044407410020821866 -0.0032121521130428097 0.005846023561900008 -0.0032630403163552441 -0.00066059854414686904 0.0087656352145452886 -0.00083195020371812432 0.0025347855343728523 -0.0014273760488058844 0.0060910219616660804 0.0073350532247369489 0.0019850109959720147 -0.0059328503679543778 -0.0025263931817426149 0.0064873251580707374 0.00033765893448438528 -0.005447259392749388 0.0038238899490423278 0.0040514721381060149 0.02823281509584926 -0.00058499890616696708 0.022251069348153241
leaf_weight=760.89593462273479 411.55983603000641 453.30111758224666 25.424529939889908 313.03219780698419 412.84094158187509 371.96958259865642 191.41007605567575 222.27511462196708 1982.7540758419782 1661.7974868584424 448.98763937875628 471.84494875743985 981.50352376699448 948.4133762922138 612.27201694622636 398.25655699521303 968.5275701507926 185.88016637042165 129.11905201710761 136.22153000161052 1230.570236608386 1533.3212699014693 299.59793788194656 196.34107868373394 12.611645258963106 2026.6397042647004 24.844438467174768
leaf_count=4896 4818 6061 322 7525 5077 4782 2103 1580 45089 26572 3405 3277 8523 16781 5304 3667 10039 2597 2025 1066 15155 37104 4985 1666 97 21274 210
internal_value=0 -0.000945176 -0.00218047 -0.00137 0.00101627 0.00148327 0.00286955 0.00205323 -0.00258068 0.000537741 0.00151742 0.00317109 0.00449781 -0.0020669 0.00388808 0.00271443 0.00355146 0.000382376 0.00397169 -8.9278e-05 -0.000766168 -0.00518353 -0.000159006 0.000365285 0.00558037 -0.000134776 0.00674234
internal_weight=0 11969 7346.76 5788.02 4622.25 4209.41 2606.87 5443.2 3543.8 2244.22 4682.31 1902.34 1430.49 3230.77 2195.31 1558.19 1366.78 2779.97 582.42 2557.69 1602.54 1558.75 1248.01 2371.81 208.953 2162.86 637.116
internal_count=246000 197619 146464 109038 51155 46078 26141 48381 74380 34658 43485 15205 11928 66855 21323 15809 13706 28280 8086 26700 19937 37426 21766 24103 1763 22340 5514
is_linear=0
shrinkage=0.0152673


Tree=151
num_leaves=28
num_cat=0
split_feature=20 1 391 2 128 13 143 10 2 10 147 130 120 38 140 13 389 8 20 90 391 157 391 149 391 387 167
split_gain=142.322 106.932 100.591 80.1492 79.1838 66.0292 65.3336 70.5169 50.0342 42.7255 44.8566 39.2289 36.6429 34.344 33.1218 32.6248 32.2994 35.6573 30.794 29.8504 31.9742 29.3944 28.8417 28.6327 26.9263 26.6914 26.5208
threshold=0.41281381511244647 1.0000000180025095e-35 -0.81178185562575544 1.0000000180025095e-35 1.0677241379310347 1.0699117618539711 2.6111111111111112 -0.09978024996566405 1.0000000180025095e-35 0.77853316852080767 -0.067567567567567557 2.0416666666666674 0.61380255941499107 0.0042499999999999769 -0.15099009900990096 -0.37952099292155528 1.0044877317300249 0.51063775510204101 -1.1812398945549447 -1.0000000180025095e-35 0.12742144408804593 22162.500000000004 -0.93013883649556617 0.11333086693797016 -0.66068996828538784 1.3778163713041456 1.7500000000000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 22 9 5 6 7 12 13 10 15 16 18 19 -2 -3 17 24 -4 -9 23 -12 -1 -21 -5 -13 -8
right_child=14 3 4 11 -6 -7 26 8 -10 -11 21 25 -14 -15 -16 -17 -18 -19 -20 20 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0017126896129324974 -0.0013449026143389966 0.002546220513666003 0.00032259544081721721 -0.0024297780011665743 -0.0037791107694910469 0.0053581666295631864 0.0041398602225231262 -0.0013232526386033037 -0.0022048636068476664 2.66187439192792e-05 0.0023936928310333422 0.0083354649047427919 0.0028330447715638669 -0.0027008308783894475 -0.0051413373626875139 0.0085141593454016468 -0.0034540279166812354 -0.0023447327739009585 -0.0042280712403496663 0.0058737851785777753 0.00057423018904753924 0.018538850768275904 -0.0083329326085993909 0.0010371622485834768 0.0027834777387681958 -0.010690268266681886 0.027020396679011988
leaf_weight=236.69214648194611 911.00159141980112 291.46791099943221 439.59800143539906 275.98234931007028 1147.786393230781 606.05735832452774 675.88445959612727 406.54670051671565 936.95164079219103 532.27213549613953 1177.8288829829544 196.94697701372206 260.7451890911907 339.35477957129478 1327.8301485758275 853.39502231217921 537.8405297677964 640.14060242287815 1575.897306855768 1018.8688977006823 736.2331002894789 26.893718861043453 457.51431469246745 403.20682566799223 1363.7305085547268 18.253061370924115 11.99123954772949
leaf_count=3200 20129 3335 4840 3571 17191 7107 7975 5264 11877 4385 13054 2116 3367 4300 31727 8586 6961 9347 29216 9727 9830 246 9068 4297 14938 238 108
internal_value=0 0.000522604 -0.00050147 0.00212623 -4.69926e-05 0.000529847 9.83611e-05 -0.000401941 0.00085811 0.00394969 0.00483444 0.000390405 -0.00253219 0.00184952 -0.00360088 0.00700351 -8.64428e-05 0.00070422 -0.00323105 0.00245531 0.00317135 0.00276473 -0.00609007 0.00450922 0.00190025 0.00667077 0.00455977
internal_weight=0 15168.1 9253.33 5914.75 8559.12 7411.34 6805.28 6117.4 3841.16 2881.86 2349.59 3032.89 2276.24 2904.21 2238.83 1144.86 2817.69 2279.85 2015.5 2564.86 2158.31 1204.72 694.206 1422.08 1639.71 215.2 687.876
internal_count=246000 194144 127367 66777 115099 97908 90801 82718 45295 29606 25221 37171 37423 33418 51856 11921 34817 27856 34056 29118 23854 13300 12268 14024 18509 2354 8083
is_linear=0
shrinkage=0.0152673


Tree=152
num_leaves=28
num_cat=0
split_feature=19 155 21 69 390 8 7 172 163 143 6 13 10 8 6 6 137 111 21 6 139 135 143 10 127 164 143
split_gain=140.031 118.911 103.576 90.0438 85.9634 72.8425 65.6894 63.1671 44.3502 39.7106 34.7769 34.0044 32.253 30.4082 59.9033 45.4097 30.0628 34.2273 28.7647 28.6115 26.962 24.5285 24.811 23.9261 23.3775 22.6196 22.295
threshold=0.19388630579008007 35028.247500000005 -1.2291473454499886 1.0000000180025095e-35 -0.11944027006271453 0.51063775510204101 0.069042731852957659 2.7500000000000004 -1.0000000180025095e-35 3.0555555555555558 0.55931495405179621 -0.37952099292155528 0.49807718719956057 1.0000000180025095e-35 0.10365497076023393 -0.1333583959899749 -1.0714285714285712 4026.9375000000005 -2.0621762643796608 0.4846616541353384 8.1115842454061344e-05 -1.9729647630619682 -1.2777777777777775 0.79913473423980241 -0.13485457097226924 283107.38625000004 2.7222222222222228
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 18 4 9 6 16 20 -8 11 -7 -4 -9 15 -15 24 -6 -18 -1 -16 25 -19 -23 -17 -10 -3 -12
right_child=-2 7 3 -5 5 10 8 12 13 -11 26 -13 -14 14 19 23 17 21 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=0.0062756835691121235 -0.0055639205541982628 0.0016595210429716648 -0.0057500757255130623 0.0035076430616820609 0.0031171849809375411 -0.0084349754563544047 -0.002819147776692895 0.0079709614458101929 0.0055451461303257579 0.0020577974231135426 -0.0024472748870195174 -0.0025082177888985212 0.0026318963605988918 -0.0056514674237002826 0.0017840342087394729 0.0094258625208835274 -0.0019309395757939234 0.033851530779052431 0.0018247030994662469 0.0086482115132965262 -0.0017595439151688467 0.063880790808557006 0.0035192860346683567 0.001280958600069838 -0.0033951292233797034 0.0095818310750634354 0.0045802933870953966
leaf_weight=397.78137344866991 996.53900962136686 448.15246124193072 1084.7971074730158 1018.2709285374731 396.74305566959083 220.4873627256602 270.20159165561199 748.977399809286 123.15251810289919 326.86827222816646 1500.9572678171098 2542.2662990670651 416.79853302426636 195.98274900764227 460.05221844650805 515.38364732824266 2073.7102528903633 6.8756525404751292 2370.5626189000905 207.54028221033514 480.22120895981789 1.4306428246200074 127.08664519526064 103.72488385997713 151.52676106058061 104.62705628946424 112.13721709698439
leaf_count=2510 23005 5476 20705 14574 4726 3861 4013 7374 1534 4950 26864 43872 3351 3114 6726 5694 28473 98 18545 2941 6021 23 1671 923 2158 1094 1704
internal_value=0 0.000329804 -0.000180926 -0.000822807 -0.00124689 -0.000161123 0.00085668 0.0036338 0.00291831 -0.00302034 -0.00273789 -0.0034806 0.00607073 0.0038059 0.00174694 0.00578417 -0.000744025 -0.00144184 0.00246798 0.00393363 0.000874141 0.00597352 0.0043606 0.00807692 0.000581038 0.0031785 -0.00195256
internal_weight=0 16406.3 14207.5 11439.2 10420.9 6466.99 4633.41 2198.78 2027.56 3953.93 1833.58 3627.06 1165.78 1757.36 863.575 893.788 2605.85 2209.1 2768.34 667.593 1033 135.393 128.517 619.109 274.679 552.78 1613.09
internal_count=246000 222995 199679 178624 164050 94523 62094 23316 27103 69527 32429 64577 10725 23090 12781 10309 34991 30265 21055 9667 12591 1792 1694 6617 3692 6570 28568
is_linear=0
shrinkage=0.0152673


Tree=153
num_leaves=28
num_cat=0
split_feature=411 391 392 164 391 391 21 90 391 391 7 8 19 171 21 391 391 0 391 17 141 387 387 23 391 140 21
split_gain=138.74 107.407 134.055 86.3712 68.1007 62.5444 56.1663 49.1036 63.3428 112.295 47.5526 64.2496 47.3949 47.2236 42.8835 40.4976 34.7508 34.5289 31.9992 31.6004 30.9887 30.2164 29.9097 30.437 29.2149 28.7701 28.3134
threshold=1.0000000180025095e-35 -0.80185022711144738 0.14774693638305278 39122.122500000005 -0.92257102786474277 -0.64052006669616957 0.44962562997048133 -1.0000000180025095e-35 -0.47078515063125309 -0.45016581085748902 -0.2098650245692604 1.0000000180025095e-35 -0.3376378893188533 9.2500000000000018 -1.034174758399736 -0.32289053306422838 -0.6485657192683002 1.0000000180025095e-35 -0.54098017844301649 1.0000000180025095e-35 0.20370370370370372 -0.52663346888579643 0.41313238142155323 1.0000000180025095e-35 -0.40474156749661011 1.0000000180025095e-35 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 3 6 -1 16 10 -7 18 -10 25 20 -2 -5 -14 24 -4 21 -9 -17 -12 -16 23 -13 -11 -3 -18
right_child=12 2 5 13 -6 7 -8 8 9 15 11 22 14 -15 17 19 26 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=3.7491808410578466e-05 0.0063816111426552267 -0.00056030719347592648 0.0031177645860244658 0.006488008630195375 -0.0071756195210601397 -0.00070304262175170055 -0.0039661524298385542 0.00017127885158083227 0.014643950208198229 0.0017291856174945287 0.0086600593086244258 0.0018598446280560599 -0.00021604637580409337 -0.00038567665766868519 -8.02863842856164e-05 0.0030290910755857289 0.0061574301102789311 -0.009027254995004258 -0.0087189563438571475 0.0075492007167984026 0 -0.0044167893107954319 -0.0026317093577976638 -0.003064195566342754 -0.0057645206601800517 -0.0045039401539896497 0.013490839358754683
leaf_weight=591.85651292093098 127.38544237241149 1006.9591443575919 419.13101305253804 614.69365425221622 624.00959294848144 1088.8862590976059 1182.2880672384053 391.4843592569232 208.91825738176703 380.36805474758148 326.94410395435989 1597.0346190650016 900.52020763978362 371.14973655156791 487.73115615546703 1817.4267363883555 322.09095092490315 296.24541507475078 123.35741556435823 455.25090880319476 134.28400509990752 1677.7542393077165 749.35045816190541 356.95941353961825 177.32457988895476 762.19454677589238 206.94787270016968
leaf_count=7537 1148 14007 4206 6516 12240 12950 28471 4231 1743 3774 3324 21975 8736 5213 8669 18240 2471 6525 1818 3671 1629 34834 11543 5325 2111 10863 2230
internal_value=0 0.000675244 0.00109105 -0.000299944 -0.00365748 0.00285945 -0.000977146 0.00212662 0.00299612 0.00383598 -0.00025889 0.0008597 -0.0027294 0.00389136 -0.00307767 0.003034 0.00643713 -0.00412065 -0.00194362 0.00393915 0.00612514 -0.00344441 -3.56558e-05 0.000955402 -0.000638314 -0.00226481 0.00904741
internal_weight=0 13908.9 12693 7101.86 1215.87 5591.19 6116.01 4643.02 3554.13 3039.29 4933.73 3164.57 3489.64 985.843 3362.25 2830.37 948.17 2461.73 514.842 2272.68 461.228 2165.49 2703.34 1953.99 557.693 1769.15 529.039
internal_count=246000 186088 166311 108866 19777 57445 97137 48538 35588 29539 68666 43796 59912 11729 58764 27796 8907 50028 6049 21911 4953 43503 38843 27300 5885 24870 4701
is_linear=0
shrinkage=0.0152673


Tree=154
num_leaves=28
num_cat=0
split_feature=19 391 391 21 391 411 109 119 166 391 129 19 118 16 21 388 21 135 109 143 19 8 126 12 10 111 133
split_gain=135.342 112.537 140.101 109.443 81.558 72.5233 56.776 52.5571 44.4043 39.8855 36.292 35.1877 34.9878 33.86 32.4011 31.9827 30.0854 29.146 27.778 28.7765 25.1361 25.0826 24.5796 24.2944 24.1015 23.5038 22.8762
threshold=0.19388630579008007 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.92257102786474277 1.0000000180025095e-35 -0.41666666666666657 0.73808104886769976 181399.20750000002 -0.65476695674678731 -0.62456902722522767 -0.31528071226839544 1.1212230215827341 1.0000000180025095e-35 -1.8457901202353957 0.80078901295443894 -1.0000000180025095e-35 0.57624544349939255 1.0000000180025095e-35 0.16666666666666669 -0.32834624111576771 0.51063775510204101 -0.63238397698201032 0.82185902118334564 0.77853316852080767 1017.9450000000001 -0.97569230769230753
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 9 7 15 6 10 11 12 -3 -5 -4 13 25 -13 -1 -11 21 -9 -20 -7 23 -16 -12 26 -8 -18
right_child=-2 2 3 5 -6 20 8 18 -10 16 17 14 -14 -15 22 -17 24 -19 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0047632364808157272 -0.0054889217916428206 0.0017585656123372505 0.0063790266476278232 0.0077613404552266049 -0.0072858881182762229 0.0063996008862385228 -0.0029289120187096069 0.0026535483492252268 0.006273249440866646 0.0052912179796937896 0.00097675179366404821 0.0039688342018917187 0.0091517642834840086 0.0011421420510468038 0.0037461986819438253 -0.0022101856769344776 0.0017031897898067971 0.0041411489441421871 0.0034837454443155604 0.0099175130003264916 -0.0041702142361512489 -0.0030147937942483624 -0.00067884655027134421 0.029534581900523035 0.002270560545476055 0.0010445121721237615 0.015290301076854616
leaf_weight=221.26891771890223 990.03544033318758 400.70597453601658 259.38473146408796 204.4139948990196 738.88411496393383 53.533140737563372 2827.7870620731264 1016.5176797695458 174.97214180976152 488.34250551834702 1578.5968428887427 534.919168792665 69.258445331826806 755.02561297081411 332.82585814222693 497.63733807206154 35.112306017428637 563.68943209573627 331.9766407571733 328.52763845026493 1476.1208091266453 438.48158336058259 2400.9811756424606 6.7995613180100909 57.188069032505155 391.75275453180075 218.93917710892856
leaf_count=2830 23005 4194 1720 2160 14557 613 52249 8550 2271 3884 19734 3545 883 11272 3131 6611 481 6272 2947 2657 30435 6789 25221 77 518 6845 2549
internal_value=0 0.000323221 0.000718686 0.000281146 -0.0037245 -0.000781611 -0.000123056 0.00202661 -0.00124194 0.00572084 0.00156431 0.000965449 -0.00156967 -0.00175926 0.000532697 -5.04011e-05 0.00769412 0.00107065 0.00425323 0.00669973 -0.00379353 0.000210608 -0.000136537 0.00110872 0.0114291 -0.00244255 0.0134513
internal_weight=0 16403.6 14945.9 13745.6 1457.79 8540.43 7010.78 5205.13 4218.8 1200.29 2791.98 3528.11 4043.82 3974.57 3268.73 718.906 799.582 2587.57 1677.02 660.504 1529.65 2023.88 2733.81 1585.4 311.24 3219.54 254.051
internal_count=246000 222995 198997 187371 23998 139600 108552 47771 73520 11626 35032 33617 71249 70366 31897 9441 7432 32872 14154 5604 31048 26600 28352 19811 3548 59094 3030
is_linear=0
shrinkage=0.0152673


Tree=155
num_leaves=28
num_cat=0
split_feature=20 391 391 21 109 391 119 14 391 20 112 140 52 112 109 118 10 409 149 70 387 21 141 391 388 161 122
split_gain=135.514 101.131 121.745 89.6051 74.0352 71.3226 59.2353 54.1407 45.6929 38.5084 33.3349 32.3077 31.4473 30.1 28.8273 28.2658 28.1055 27.8184 27.389 25.2504 24.3403 24.2133 23.1206 41.9513 24.4179 25.6736 22.71
threshold=0.45114359061287296 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.58333333333333315 -0.92257102786474277 0.51281287246722307 -1.0000000180025095e-35 -0.65476695674678731 -1.126355914706455 -0.73759016367567898 -0.15099009900990096 3.5000000000003335 -0.64902126047634823 0.75000000000000011 1.16726618705036 -0.0069358604587281955 -1.0000000180025095e-35 -0.0060715307131818932 0.41891891891891897 0.42612580082725582 -1.0000000180025095e-35 2.5370370370370376 1.2847011455949713 -0.62996904611222726 7374.2175000000007 3.8793103448275867
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 8 6 19 -1 13 -6 -3 26 15 18 14 -4 -8 -11 -10 -12 -2 22 -16 -18 -5 24 -24 -26 -9
right_child=11 2 3 4 7 -7 12 9 16 10 17 -13 -14 -15 20 -17 21 -19 -20 -21 -22 -23 23 -25 25 -27 -28
leaf_value=0 0.0022820075290572333 0.0012388054314313799 0.0053295798224684554 0.00053777109715150595 -0.0051303889559077562 -0.0069984169849646623 0.0040806553446875943 0.0022595658766350994 0.013049742134770963 0.0028559790597729316 -0.0033865918684001487 -0.0055142819797630582 -1.3690639263842063e-05 7.6528777765525266e-05 0.013491319877283959 0.026778154147317896 0.0035940586186204476 -0.00072291056490293205 -0.003633523787152565 0.0045710190358524833 0.002625768189479463 0.0099994760879586302 0.048365013277157268 0.0721686764129085 -0.0015578180792690018 0.044475200786044986 -0.0039454342971538582
leaf_weight=674.35123853199184 286.74130792543292 379.6551324352622 282.59638156741858 1449.5290740281343 800.79618803039193 681.54632367566228 1501.7498755902052 1089.8585722260177 180.87586298026145 195.65637136623263 1689.9656419381499 1121.8907925058156 371.89578046649694 2558.8516936004162 151.45662826299667 12.194849710911511 362.02488595619798 2013.9633966740221 495.10194632969797 594.74279749952257 73.87674256414175 229.2118806745857 2.975071273744109 2.4435799419879904 25.575073957443241 2.9369936846196643 156.22376645728946
leaf_count=8436 6029 3820 2295 16873 15071 12969 11916 11172 1836 3308 34759 27442 3426 24513 1186 163 2702 35284 11514 6152 635 2297 36 25 356 37 1748
internal_value=0 0.000465069 0.00084782 0.000424813 -0.000568957 -0.00351615 0.00204324 -0.00143521 0.0056051 -0.000859553 -0.0016052 -0.00385119 0.00398897 0.000602533 0.00485607 0.00432794 0.00773931 -0.00194084 -0.00145226 0.00191027 0.0099751 0.00609535 0.000836886 0.0132687 0.00798204 0.00314172 0.00147377
internal_weight=0 15485 14129.1 12977.3 8036.86 1355.9 4940.43 5958.66 1151.77 5157.86 3911.78 1903.73 2098.98 2841.45 1727.08 207.851 772.113 3703.93 781.843 2078.2 225.333 591.237 1483.46 33.9307 31.4871 28.5121 1246.08
internal_count=246000 201015 179610 168955 124984 21405 43971 101505 10655 86434 73514 44985 17163 26808 13737 3471 6835 70043 17543 23479 1821 4999 17327 454 429 393 12920
is_linear=0
shrinkage=0.0152673


Tree=156
num_leaves=28
num_cat=0
split_feature=20 1 19 391 143 14 10 19 19 10 8 7 14 387 10 20 389 141 119 67 125 8 7 390 165 391 13
split_gain=131.894 113.586 101.554 93.4154 76.4486 73.5719 59.9128 57.0434 63.028 51.5533 53.9209 74.7741 50.0889 37.0747 36.848 31.5824 31.3677 30.6815 26.0687 25.5705 24.4498 26.2029 34.3168 26.0561 23.777 23.2009 22.6087
threshold=0.51688161336547822 1.0000000180025095e-35 -0.23999248241935275 -0.81178185562575544 2.6111111111111112 -1.0000000180025095e-35 -0.16446916632330721 0.0028346554504373738 -1.0000000180025095e-35 0.77853316852080767 0.51063775510204101 -0.55072463768115931 -1.0000000180025095e-35 0.42612580082725582 0.75738222771597319 -1.1812398945549447 -0.53535046455599156 0.16666666666666669 0.72377830750893934 1.0000000180025095e-35 -0.4022453953765141 1.0000000180025095e-35 0.02326304658829384 0.2316748759960926 30442.871250000004 -0.92257102786474277 -0.06535440705905167
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 14 25 6 -3 15 8 19 10 11 24 -10 17 -1 -5 -6 26 -2 -8 23 22 -22 -14 -7 -4 -13
right_child=18 5 3 4 16 9 7 -9 12 -11 -12 13 20 -15 -16 -17 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.007558555994597203 -0.0056817948295237617 -0.0013452703195125824 -0.0029937813416531559 0.00027647042664499772 0.010685648011615277 -0.00088861239068794434 -0.0026652989371408376 -0.0035973802955515002 -0.0042458485708791321 -0.00064067362608817373 9.2125002305534673e-05 0.0057829117411327307 0.0019798544919911827 0.0022752784949458104 0.0007637051891945211 -0.0036863906133471772 0.0024362295081282008 0.0038853006906030699 -0.00061247795800256036 0.0032742712801921425 0.0018902831938684408 -0.00056611178563822711 0.0091661865526135294 0.0080729539976522689 0.0073446752196344332 -0.0088109283374500132 0.0098488734131682142
leaf_weight=441.64510767534375 1064.3267616853118 1230.1549466084689 270.53661519102752 584.30402696505189 127.48133674263954 652.53609623014927 1195.1080744173378 866.15084087848663 244.80802395753562 832.60691772773862 858.73163102567196 607.66366622783244 294.70680768042803 595.73306220397353 326.96603067219257 2286.3871087376028 720.70819112099707 643.10535663925111 309.41293195262551 195.29805892333388 645.92039682716131 588.15637623891234 199.23679522797465 381.80386352352798 93.217878920957446 413.1610745806247 714.03340724110603
leaf_count=3969 27027 17125 3994 6331 1545 8519 14183 15569 3311 7159 11951 6276 3466 7312 2785 43339 9065 7173 6453 2141 7279 7988 1746 3916 858 8990 6530
internal_value=0 0.000382174 -0.000643173 -0.00109827 -0.0006517 0.00199419 -0.00114511 -6.50904e-05 0.000749559 0.00281805 0.00351166 0.00439697 0.0022732 0.00563605 0.0046809 -0.00287663 0.00368913 0.00665005 -0.00454693 -0.00182408 0.0030343 0.00189489 0.0036181 0.00543354 0.000129947 -0.00652405 0.00798759
internal_weight=0 16010.2 9782.38 9013.77 8330.07 6227.78 7481.88 4611.19 3745.04 4997.63 4165.02 3306.29 2354.63 2560.54 768.611 2870.69 848.19 1964.8 1373.74 1390.41 2109.82 1433.31 845.157 676.511 745.754 683.698 1321.7
internal_count=246000 212520 139617 132863 119879 72903 109269 59599 44030 55778 48619 36668 27706 27291 6754 49670 10610 19979 33480 16324 24395 17013 9025 7382 9377 12984 12806
is_linear=0
shrinkage=0.0152673


Tree=157
num_leaves=28
num_cat=0
split_feature=20 21 109 149 130 119 61 7 11 112 21 147 165 25 122 8 20 388 149 109 414 35 130 111 6 391 391
split_gain=129.272 110.951 66.9732 48.1391 41.4976 41.4059 38.9548 34.4312 33.4463 33.0582 29.2524 29.1936 28.8556 32.5399 27.8296 28.8956 26.8453 26.0711 24.6807 24.4454 26.8504 23.6963 24.3868 23.5398 23.7687 23.3442 32.508
threshold=-0.85099376108228075 -0.45447813724047786 -0.41666666666666657 -0.36876546416773598 0.29166666666666669 0.73808104886769976 0.0042499999999999977 -0.46140449088760332 -0.50412541254125409 -0.76405132818788757 -1.811377762099047 0.60810810810810823 88108.290000000023 -0.21419999999999997 0.39655172413793111 1.0000000180025095e-35 0.58744417577269659 0.5370309485325353 -0.028395032574785664 1.7500000000000002 -1.0000000180025095e-35 0.00095 0.79166666666666685 37055.520000000011 -0.028517126148705094 0.48751167347278374 0.76182316479324586
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=6 5 3 11 8 9 7 -1 -4 -2 -11 12 13 -3 15 23 -5 -16 -10 20 -7 22 -12 24 -9 -17 -27
right_child=1 2 4 16 -6 19 -8 14 18 10 21 -13 -14 -15 17 25 -18 -19 -20 -21 -22 -23 -24 -25 -26 26 -28
leaf_value=0.00034225005696576755 0.0095464117633473379 0.045125152053584403 -0.0065294714931889855 -0.00085044853402034396 -0.00085354387083001434 -0.00034287836812330568 -0.0010081930968317966 0.0043963878187667036 -0.0014950796121862258 0.0030240608986795612 -0.0011845320951949716 -0.0016616936126601298 0.019870806294264499 0.0039118566605034662 0.0022669969164778288 -0.00010353817288552755 -0.0074413650182735356 -0.0043727748144663618 -0.0046743485030156153 0.016792936647031798 0.0041268266463482597 -0.0038022475696219003 0.0026272647179141754 0.032929956090701457 0.0093630120046119623 0.010355721352054068 0.0024520215841125907
leaf_weight=1258.1341821141541 81.346249464899302 4.3600575402379027 962.5827923733741 1885.7000103648752 1254.1260288711637 448.62724835053086 873.89364994317293 884.62313978001475 1125.498937567696 513.63464143127203 1532.9314826205373 192.35667437314987 30.014958940446377 450.93762019649148 785.78251123428345 476.24969328939915 156.43952431902289 166.29015833884478 1175.1709864605218 29.565410580486059 1010.6802546754479 541.70919860899448 524.57277452200651 7.3972893804311743 308.91518493741751 158.44875263050199 539.43024032190442
leaf_count=11929 794 58 24293 30653 26951 5118 8356 6741 22952 3922 19190 3117 304 6354 6791 4439 4320 1386 26655 285 9442 7200 6011 46 2015 1343 5335
internal_value=0 -0.000898423 -0.00208365 -0.000187252 -0.00322333 0.00093127 0.00193831 0.00250189 -0.00413117 -4.60611e-05 -0.000300275 0.00333419 0.00533308 0.00434628 0.00331572 0.00420109 -0.00136051 0.00109699 -0.00312328 0.00303389 0.00274659 -0.000960909 -0.00020808 0.00587175 0.00569089 0.00248378 0.00426208
internal_weight=0 11920.3 7237.19 2719.81 4517.38 4683.07 5459.16 4585.27 3263.25 3194.19 3112.85 677.669 485.313 455.298 3327.14 2375.06 2042.14 952.073 2300.67 1488.87 1459.31 2599.21 2057.5 1200.94 1193.54 1174.13 697.879
internal_count=246000 197619 145657 44806 100851 51962 48381 40025 73900 37117 36323 9833 6716 6412 28096 19919 34973 8177 49607 14845 14560 32401 25201 8802 8756 11117 6678
is_linear=0
shrinkage=0.0152673


Tree=158
num_leaves=28
num_cat=0
split_feature=411 391 392 165 130 391 391 7 8 391 391 171 17 19 387 391 391 90 10 86 391 391 8 391 168 163 118
split_gain=129.359 97.0368 121.84 80.4823 68.372 62.9616 55.4406 47.2183 53.5934 47.07 124.596 45.8471 44.2652 44.0665 39.4483 38.3727 30.7886 30.5101 28.4132 28.3739 28.1041 26.6361 37.4542 25.5832 25.2003 27.9573 24.4344
threshold=1.0000000180025095e-35 -0.80185022711144738 0.14774693638305278 39993.693750000006 2.2916666666666674 -0.92257102786474277 -0.64052006669616957 -0.2098650245692604 1.0000000180025095e-35 -0.47078515063125309 -0.45016581085748902 12.750000000000002 1.0000000180025095e-35 -0.3376378893188533 -0.18119716943117045 -0.54098017844301649 -0.6485657192683002 -1.0000000180025095e-35 0.70477956324680691 1.0000000180025095e-35 -0.32289053306422838 0.48751167347278374 0.51063775510204101 -0.40474156749661011 3.2500000000000004 21606.480000000007 -0.0075539568345323735
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 5 3 4 7 -1 16 -3 -9 15 -11 -5 17 -2 18 -8 -4 -12 24 21 23 -10 -23 -19 -15 -26 -6
right_child=13 2 6 11 26 -7 9 8 19 10 12 -13 -14 14 -16 -17 -18 20 -20 -21 -22 22 -24 -25 25 -27 -28
leaf_value=3.9010961922919303e-05 0.0060945309590304808 -0.0034088048813157678 0.0029450964084898369 0.0060131678943381979 -0.00010874485925054389 -0.0069358496937078689 0.0001553794493475377 0.0043366671083889573 -0.0033996360990329599 0.013394854020129516 -0.001330713588216792 -0.00096705262146496601 0.0053507876376247899 -0.00019988397981478325 -0.0043737979385164967 -0.0089827444126271763 0.0084982152933859544 0.0011678428862993773 -0.0048095567983348205 0.004453199810716589 0.0029143889767844172 0.0032094402111895438 -0.0017947032168645737 -0.0066407591382778948 0.022258915204259887 -0.0039930127170052041 0.0060281607234146705
leaf_weight=591.57107750698924 128.5992138646543 1945.7311179209501 421.86960205622017 671.51610941812396 236.07379591464996 609.91024302504957 453.52824863232672 472.74614072404802 1126.2552071046084 235.65913789905608 836.50164930336177 322.49868148006499 725.21822321042418 992.95631435513496 1965.4120817575604 139.27975008450449 538.03950649313629 298.10083277337253 341.30236932821572 193.59102590754628 1824.1538714841008 486.02893802337348 1228.3569987230003 144.40483031794429 24.402648841962218 14.421245129778979 406.63946205563843
leaf_count=7537 1148 31969 4206 7168 3872 12240 4982 5861 19697 1978 10205 4609 6162 16533 37457 2090 4701 3088 4293 2775 18240 7395 20641 1793 284 197 4879
internal_value=0 0.000650474 0.0010432 -0.000286358 -0.000944489 -0.00349459 0.00272293 -0.00150086 -0.000439553 0.00203115 0.00261834 0.00373955 0.00195193 -0.00264562 -0.00298538 -0.00197847 0.00606834 0.00115436 -0.000990988 -0.00118696 0.00207554 -0.00157485 -0.000370476 -0.00136153 0.000263967 0.0123023 0.00376044
internal_weight=0 13907.7 12706.2 7089.44 6095.42 1201.48 5616.76 5452.71 3506.98 4656.85 4064.04 994.015 3828.38 3467.09 3338.49 592.808 959.909 3103.16 1373.08 3034.23 2266.66 2840.64 1714.39 442.506 1031.78 38.8239 642.713
internal_count=246000 186088 166311 108866 97089 19777 57445 88338 56369 48538 41466 11777 39488 59912 58764 7072 8907 33326 21307 50508 23121 47733 28036 4881 17014 481 8751
is_linear=0
shrinkage=0.0152673


Tree=159
num_leaves=28
num_cat=0
split_feature=20 1 391 2 130 149 390 391 10 416 165 389 8 391 391 391 135 136 390 139 61 7 10 17 127 130 219
split_gain=125.983 108.984 93.9574 79.2863 74.8751 60.7811 48.7122 43.9746 43.041 47.4058 38.33 38.9615 43.8297 31.8284 31.5466 30.8821 30.8671 44.9251 30.0839 28.2571 27.3352 24.8833 23.4224 22.7072 21.9824 22.8338 22.8099
threshold=0.51688161336547822 1.0000000180025095e-35 -0.81178185562575544 1.0000000180025095e-35 0.29166666666666669 -0.1637686521149341 0.21400322269547925 -0.64052006669616957 0.85599505562422762 -1.0000000180025095e-35 163488.19500000001 0.73889071348950008 0.51063775510204101 0.12742144408804593 -0.66068996828538784 -0.93013883649556617 0.83748481166464173 0.27368105515587537 0.62308307408686048 0.44346092780014623 1.0000000180025095e-35 0.24295577533121854 0.067367119901112493 -1.0000000180025095e-35 -0.53956105115423691 -1.0416666666666663 -497.60270000000713
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 15 8 5 6 -4 -6 9 24 11 12 14 -8 -5 -1 17 18 -9 20 22 -16 -7 -11 -3 26 -26
right_child=-2 3 4 10 7 19 13 16 -10 23 -12 -13 -14 -15 21 -17 -18 -19 -20 -21 -22 -23 -24 -25 25 -27 -28
leaf_value=-0.0015152349396630686 -0.0044609511584282674 0.011863157119259575 -0.0014499352092498415 -0.002471356712401783 0.0090446958435020739 -0.0027143314751393432 0.0044280280808038797 0.0012739158333589734 -0.0010189651538341389 -0.0037595283052916295 0.0074392045154472166 -0.0031043872516220137 -0.0023397996983982837 -0.00032918948295052188 0.0016135871561224354 -0.0082118696454379463 0.0045221219495382445 -0.0025361939960931246 0.008225765263534723 -0.0047221120062957232 -0.004689023251166765 0.0059592098140755318 0.00076656880211986654 0.0033079701875981539 0.036825533040513163 0.005240928694681366 0.010541913169835182
leaf_weight=248.07759012840688 1363.9784820340574 184.50423841737211 1456.7681412827224 269.26178966462612 184.24077196791768 795.93428743071854 832.47153696790338 1223.2699165679514 386.32911012135446 112.45793879963458 164.88357055559754 761.58044552616775 685.17710353992879 535.01486401073635 831.57456646673381 475.13214897736907 558.59809256531298 744.3014224562794 165.47193526104093 988.34436644986272 530.68135169893503 494.96355632506311 1031.9842892792076 1535.861969396472 9.823697838932274 755.57317463308573 44.176377449184656
leaf_count=3460 33480 1650 20889 3628 1758 13710 8264 17797 3130 1556 1629 10283 10473 7645 9423 10023 6399 10284 1918 16196 8740 5375 12534 17489 87 7802 378
internal_value=0 0.00037232 -0.000633443 0.0019495 -0.000209032 -0.00115808 0.000488617 0.00182424 0.0037212 0.00441772 0.000273538 -0.00011224 0.000882958 0.00256034 0.00227255 -0.00592849 0.00132597 0.000484322 0.00210991 -0.0025503 -0.00163602 0.0032426 -0.000744247 0.00281983 0.00705693 0.00594761 0.0156107
internal_weight=0 16006.5 9770.29 6236.17 9047.08 6171.2 2824.25 2875.88 3028.73 2642.4 3207.44 3042.56 2280.98 1367.49 1595.8 723.21 2691.64 2133.04 1388.74 3346.94 2358.6 1326.54 1827.92 1648.32 994.077 809.573 54.0001
internal_count=246000 212520 139617 72903 126134 87978 36798 38156 32092 28962 40811 39182 28899 15909 18426 13483 36398 29999 19715 51180 34984 14798 26244 19045 9917 8267 465
is_linear=0
shrinkage=0.0152673


Tree=160
num_leaves=28
num_cat=0
split_feature=19 20 130 11 125 20 10 416 7 118 513 164 119 125 130 6 8 141 137 13 1 387 67 70 19 389 148
split_gain=126.813 106.579 87.8054 75.9227 43.5237 36.6678 35.6241 41.8119 35.501 33.662 33.2708 32.1968 32.0008 31.4805 30.2325 27.0241 30.7711 26.9805 26.4446 26.052 25.8574 25.2924 23.7281 22.9781 22.5862 21.8627 22.6401
threshold=0.19388630579008007 -1.055547744992388 0.54166666666666685 0.093784378437843804 -0.39010825878916106 0.3451954345106808 0.81712676830105768 -1.0000000180025095e-35 -0.63009267898239707 1.2535971223021585 1.0000000180025095e-35 29195.640000000003 -0.11889153754469606 -0.188129383282061 2.0416666666666674 -0.42439431913116116 1.0000000180025095e-35 0.092592592592592601 0.50000000000000011 -0.140599243673034 1.0000000180025095e-35 1.6747903497335972 1.5000000000000002 -0.71930501930501911 -0.4294617065977519 -0.085401430792700919 0.51085263373642154
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 10 3 4 8 19 7 20 -3 23 14 13 -4 15 17 -9 -17 -1 22 -6 -5 -21 -14 -10 -8 26 -22
right_child=-2 2 12 6 5 -7 24 11 9 -11 -12 -13 18 -15 -16 16 -18 -19 -20 21 25 -23 -24 -25 -26 -27 -28
leaf_value=0.0036316055851653328 -0.0053482121746336823 -0.0050650806537604863 -0.00061306177431198815 0.0012743880870377847 -0.0042381035197334186 -0.006279287375758575 0.014060865093682404 -0.0033017816068577933 -0.0027608531152375306 0.025814464188363778 -0.00071865709251151845 0.0041927032967979195 0.0034205441134180893 -0.002876176282923663 0.0078074494409522844 0.0065488355559552439 -0.00020871576749209795 0.00078242535491145396 -0.00025814590938221123 -0.00026009731858587951 0.012206399520608953 -0.0063482596689174954 0.014082238030022613 0.0020405118172011254 -0.0030553717505970406 0.0032604326135951996 -0.0002877467018759267
leaf_weight=2065.6614770144224 977.65857384726405 287.83642538823187 882.22599024139345 770.27679748088121 1145.3405368700624 817.60159205272794 18.031190305948257 239.53864520043135 325.6960395667702 12.352172639220951 673.40702678263187 314.05077687092125 1610.5582659710199 1039.3509265240282 279.24091860279441 275.04662417061627 359.94680035114288 1254.5785910561681 492.55030559748411 1169.4703607708216 161.55752917565405 184.61853586137295 50.64044994674623 802.85038397461176 768.72620952129364 347.02716559916735 40.929805725812912
leaf_count=15797 23005 5390 15636 11018 20422 20823 127 3396 6052 149 5910 3390 20894 15604 2133 3023 5310 11451 6729 18138 1770 3265 593 12774 8482 4208 511
internal_value=0 0.000311442 -0.000419057 -0.00117119 -0.00250552 -0.00346527 0.000287696 0.000941418 -0.000270731 0.00093148 0.00238492 -0.000330572 0.00182739 -0.00107795 0.0029681 0.00104888 0.00270503 0.00255789 0.00283127 -0.00254067 0.00309532 -0.00109775 0.00375273 0.000646489 -0.00264798 0.00562975 0.00963791
internal_weight=0 16389.1 12116.2 9080.25 4745.77 3317.03 4334.48 3547.73 1428.74 1140.9 4272.89 2227.93 3035.98 1913.88 3599.48 874.532 634.993 3320.24 2153.75 2499.43 1319.79 1354.09 1661.2 1128.55 786.757 549.515 202.487
internal_count=246000 222995 187704 143852 87013 62648 56839 48230 24365 18975 35291 30723 43852 27333 29381 11729 8333 27248 28216 41825 17507 21403 21487 18826 8609 6489 2281
is_linear=0
shrinkage=0.0152673


Tree=161
num_leaves=28
num_cat=0
split_feature=411 391 392 155 391 21 391 119 391 391 19 21 16 391 7 8 7 109 0 391 64 16 172 143 21 11 143
split_gain=123.81 91.9418 115.026 78.6739 60.6347 55.9514 52.538 47.2653 45.4085 118.632 42.2766 40.7878 38.7174 37.2946 34.7364 50.9503 32.4312 31.7132 30.7828 29.1548 28.9214 28.0673 27.0416 26.7394 26.6379 25.8252 25.2524
threshold=1.0000000180025095e-35 -0.80185022711144738 0.14774693638305278 165056.09625000003 -0.92257102786474277 0.44962562997048133 -0.64052006669616957 0.98241954707985701 -0.47078515063125309 -0.45016581085748902 -0.3376378893188533 0.31785522338584254 1.0000000180025095e-35 -0.54098017844301649 -0.2098650245692604 1.0000000180025095e-35 0.23598930148659578 0.25000000000000006 1.0000000180025095e-35 -0.6485657192683002 2.9531250000000058 -1.0000000180025095e-35 -1.7499999999999998 3.1666666666666674 -2.184422931748109 -0.78685368536853673 1.2777777777777779
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 3 5 -1 7 19 14 13 -10 -2 18 21 -8 -3 16 -16 -9 25 -4 23 -11 -5 -17 -23 -12 -27
right_child=10 2 6 22 -6 -7 8 17 9 12 11 -13 -14 -15 15 20 -18 -19 -20 -21 -22 24 -24 -25 -26 26 -28
leaf_value=4.6726353319393897e-05 0.0059432605041157046 -0.0024227215093817096 0.0028535786336255846 0.00033945121567245239 -0.0068181009679162399 -0.0035998296824202814 0.0001250416409511238 0.0015523030575284996 0.01300728342561152 -0.0038305694057729637 -0.004863280941938994 -0.0063729953034381169 0.0049220393880474852 -0.0089092995791916867 0.0031471968688501764 -0.0001743908107370423 0.013911656549065902 0.0083110988537141179 -0.0066499352837910714 0.0082442375711980348 -0.0038751215815009533 0.012607707393240743 0.0086695459683891942 0.0065137689728989598 0.0013431194100436414 -0.0015057602503103038 0.0032264830061247037
leaf_weight=591.15696524083614 129.24852680414915 1635.4218182023615 423.29695937223732 135.03080263547599 603.07374360971153 1248.3683412186801 454.00816887244582 665.4327907692641 238.0140201151371 245.00472806207836 434.70605108328164 647.82013186067343 784.56487460806966 138.19126919656992 338.40788906626403 1847.2283402271569 81.961119133979082 215.92610198631883 306.75228974223137 542.15539944916964 471.57118229009211 49.851479768753052 292.92798762209713 150.34537350945175 2756.5432500690222 1623.1951158456504 312.56470432505012
leaf_count=7537 1148 23177 4206 1728 12240 30098 4982 8112 1978 3319 7750 17584 6714 2090 3714 26404 809 2423 5299 4701 7541 268 3014 1846 29187 23989 4142
internal_value=0 0.000635293 0.0010163 -0.000277434 -0.00341283 -0.000686795 0.00264493 -1.23426e-05 0.00197106 0.00254625 -0.00259409 -0.00292904 0.00189413 -0.00196998 -0.000644082 0.000359529 0.00527339 0.00322006 -0.00209185 0.0058913 -0.000473699 0.00111233 0.00606399 0.000325003 0.00154737 -0.00149763 -0.000736665
internal_weight=0 13908.5 12714.3 7082.62 1194.23 6654.66 5631.63 5406.29 4666.18 4073.98 3454.29 3325.04 3835.96 592.199 4524.94 2889.51 420.369 881.359 2677.22 965.452 2469.14 3051.4 427.959 1997.57 2806.39 2370.47 1935.76
internal_count=246000 186088 166311 108866 19777 104124 57445 74026 48538 41466 59912 58764 39488 7072 63491 40314 4523 10535 41180 8907 35791 32774 4742 28250 29455 35881 28131
is_linear=0
shrinkage=0.0152673


Tree=162
num_leaves=28
num_cat=0
split_feature=411 10 391 391 391 391 391 391 130 120 164 21 149 7 391 7 8 0 67 12 21 10 11 13 172 391 391
split_gain=120.286 90.4299 85.4302 120.971 68.8108 64.902 76.0598 47.7236 44.199 43.8605 41.5835 41.1985 39.2883 39.0485 38.2029 35.9059 37.93 33.6209 31.506 30.2225 28.678 26.3794 37.5187 27.2457 26.0686 24.2742 23.2898
threshold=1.0000000180025095e-35 -0.54216453783820895 0.12742144408804593 1.0000000180025095e-35 0.049180694651566131 -0.81178185562575544 -0.036077397995487537 -0.92257102786474277 0.70833333333333337 0.61014625228519204 33462.978750000002 0.31785522338584254 -0.17805013079766904 -0.55072463768115931 1.0000000180025095e-35 -0.016296572743671078 0.51063775510204101 1.0000000180025095e-35 1.5000000000000002 0.82185902118334564 -0.29970545880896432 0.78512566955088603 -0.78685368536853673 0.93687578784058967 6.7500000000000009 -0.64052006669616957 -0.66068996828538784
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 9 3 5 -5 7 8 -3 12 14 15 17 13 -7 -1 -4 -17 21 -10 -15 -18 22 -2 -24 -12 26 -14
right_child=11 2 10 4 -6 6 -8 -9 18 -11 24 -13 25 19 -16 16 20 -19 -20 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=-0.0046186740726538037 -0.0044852142974545145 0.00018399243807216457 -0.0038353632713987082 0.0098954505861938435 0.0032092949050406957 -0.0011906183652430169 -0.0019640210384333956 -0.0070525975189063379 0.00512446141401129 0.0033599160653865006 0.0010245306277160977 -0.0060163377043491242 -0.0015334399251437124 0.0046863356104711882 -0.00080593197363036119 0.0037304983736622679 0.0011295052091936178 -0.0064327483278085107 0.021705652111366831 0.043258630048429059 -0.0032540637769877161 -0.0051166925905077928 -0.00022511877300284279 0.0055471019321498231 0.0084282894135838081 -0.0006276972716772293 0.0063824641045750943
leaf_weight=1111.2652449775487 440.43432171270251 548.16544600762427 1002.0826580058783 630.96627537719905 845.53591743297875 309.09841498173773 987.3738344553858 344.17579103261232 935.52732691168785 335.3794201053679 427.6394331138581 653.56761245056987 128.42710129544139 1255.7964263558388 1380.6630757879466 428.93890046142042 588.76205396652222 317.17453597672284 27.716162605211139 4.6159311681985846 841.5547433141619 336.84206722490489 1480.1953959465027 218.20340779423714 151.28671630099416 1370.9073380120099 255.60548077523708
leaf_count=20910 7809 6780 14637 5245 8779 3440 13549 6448 9374 4654 5202 17739 1387 12139 24747 5833 6693 5419 255 40 15975 3877 22030 3038 1385 16240 2376
internal_value=0 0.000625443 0.00124761 0.0021471 0.0060737 0.0012054 0.00185058 -0.00259785 0.0027312 -0.00181038 -0.000748304 -0.00256048 0.00189245 0.00364787 -0.00251012 -0.00150546 -0.000244515 -0.00174811 0.00561548 0.0048417 -0.00144334 -0.00114376 -0.000513362 0.000511646 0.00297736 0.00031705 0.00371199
internal_weight=0 13911.5 11084.2 7643.91 1476.5 6167.41 5275.07 892.341 4287.69 2827.31 3440.26 3446.42 3324.45 1569.51 2491.93 2861.34 1859.26 2792.85 963.243 1260.41 1430.32 2475.68 2138.83 1698.4 578.926 1754.94 384.033
internal_count=246000 186088 135777 86052 14024 72028 58800 13228 45251 50311 49725 59912 35622 15619 45657 43138 28501 42173 9629 12179 22668 36754 32877 25068 6587 20003 3763
is_linear=0
shrinkage=0.0152673


Tree=163
num_leaves=28
num_cat=0
split_feature=19 14 1 391 128 19 130 164 416 130 171 67 21 86 389 6 8 20 7 8 6 391 111 69 21 389 19
split_gain=121.616 108.421 101.902 88.0723 77.0571 62.3213 59.6387 57.5274 48.5306 42.6516 38.8987 38.2547 40.9177 36.4336 35.3738 31.5268 34.0354 30.0384 29.3131 37.6914 29.8742 29.104 28.6446 21.9887 22.6951 23.4525 21.8421
threshold=0.19388630579008007 -1.0000000180025095e-35 1.0000000180025095e-35 -0.84913404291403738 1.0677241379310347 -0.23674106267790407 2.0416666666666674 36029.92500000001 -1.0000000180025095e-35 0.12500000000000003 8.7500000000000018 1.0000000180025095e-35 -1.811377762099047 1.0000000180025095e-35 -0.056221408997843399 -0.58470760233918118 0.51063775510204101 0.51688161336547822 -0.2098650245692604 1.0000000180025095e-35 0.12253968253968255 -0.92257102786474277 37055.520000000011 1.0000000180025095e-35 -1.4231812591257043 -0.36312272686057057 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 17 3 21 5 -5 7 11 14 15 -9 12 -7 18 -4 -10 22 -1 -14 -20 -21 -3 23 24 -17 -26 -15
right_child=-2 2 8 4 -6 6 -8 10 9 -11 -12 -13 13 26 -16 16 -18 -19 19 20 -22 -23 -24 -25 25 -27 -28
leaf_value=-0.0021847135844229107 -0.0052588825117790578 -0.0020761641785048009 0.0069070815620386004 0.0053829884610526388 -0.0035617258204740125 0.00419402042998501 0.0047814661360412623 0.005629884948046132 -0.0049361778216983482 0.004188657783811665 -0.0014174550190610199 0.0026542419606594841 -0.0036604016267741978 -0.002939712692702834 0.0026756324253138942 0.0059432118021727183 -0.002326355095094317 -0.0079203218400598786 0.0023613943757059574 -0.0075654483021935434 -0.0013315406437037734 -0.0088201756432251567 0.025584281106405437 0.0075064588430646959 0.0040589103452287056 -0.00074405547772712596 0.0055531329831167422
leaf_weight=2024.6214171145111 970.11807622946799 276.84799835830927 790.92357544228435 629.43375235423446 1089.953622315079 296.50301562994719 639.08383391425014 605.60518581420183 240.30221344530582 908.55867339111865 258.5592087469995 665.32236639782786 1614.9571878314018 97.679094962775707 1129.2243725135922 207.23341843113303 565.50345632061362 239.63786063343287 586.46442962251604 208.28262869268656 1330.0969995222986 334.74602139182389 11.799446344375609 145.52491438761353 317.61739268712699 925.52560941316187 243.38580556027591
leaf_count=28656 23005 4018 7711 5465 17312 1976 7904 5925 3282 10560 3528 9223 25971 1220 12139 1390 8480 5863 7123 3552 23533 7544 120 1530 3752 11965 3253
internal_value=0 0.000303911 0.000801788 -0.00019399 0.000218668 0.000794277 0.000351493 -0.000126396 0.00248968 0.00136875 0.00351087 -0.000751645 -0.0012715 -0.00167104 0.00442391 0.000303147 0.000887102 -0.00279643 -0.00210817 -0.000923869 -0.00218238 -0.00578404 0.00202327 0.00184015 0.00126434 0.000476168 0.00309369
internal_weight=0 16383.4 14119.1 8876.92 8265.33 7175.37 6545.94 5906.86 5242.21 3322.07 864.164 5042.69 4377.37 4080.87 1920.15 2413.51 2173.2 2264.26 3739.8 2124.84 1538.38 611.594 1607.7 1595.9 1450.38 1243.14 341.065
internal_count=246000 222995 188476 127547 115985 98673 93208 85304 60929 41079 9453 75851 66628 64652 19850 30519 27237 34519 60179 34208 27085 11562 18757 18637 17107 15717 4473
is_linear=0
shrinkage=0.0152673


Tree=164
num_leaves=28
num_cat=0
split_feature=20 1 391 128 90 130 8 10 10 416 391 414 141 391 142 143 13 391 150 109 391 7 149 140 17 387 6
split_gain=117.774 100.563 86.5821 78.707 67.2416 61.4878 50.766 50.5534 44.5144 56.1592 40.4711 39.3113 37.7576 33.8809 35.6272 50.3496 33.0487 30.7756 29.9932 29.4673 29.2435 27.8075 26.0044 25.9991 25.0803 24.9957 24.407
threshold=0.51688161336547822 1.0000000180025095e-35 -0.81178185562575544 1.0677241379310347 -1.0000000180025095e-35 1.0000000180025095e-35 0.51063775510204101 -0.16446916632330721 0.80641395412718042 -1.0000000180025095e-35 -0.81178185562575544 -1.0000000180025095e-35 0.055555555555555559 -0.64052006669616957 0.34375000000000006 2.7222222222222228 -0.58547464365364099 0.1379033485638034 0.61857707509881432 2.4166666666666674 -0.93013883649556617 0.838713690365118 -0.55593076250974105 -0.15099009900990096 1.0000000180025095e-35 0.52077873246429163 0.46857142857142858
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 20 5 25 7 8 22 9 12 -11 24 21 -7 -15 19 -13 -12 -18 -16 -1 -6 -4 -2 -9 -3 -19
right_child=23 4 3 -5 6 13 -8 11 -10 10 17 16 -14 14 15 -17 18 26 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0014477647185944377 -0.0017953189394808303 0.00029646640437622495 0.0012118264372820591 -0.0038143427115313946 0.0087157751131078966 0.0089499437750793533 -0.00030387230637470393 -0.0032547106834364525 -0.00043008115270359236 -0.0030308474073610365 0.0047507061369224156 -0.0039582041066949826 0.0034422913482741084 0.0050148098777565327 -0.0014383208051355117 0.0043575541587563679 0.001599666389909295 -0.0023822373284771809 0.0095254842322124653 0.01570940116404761 -0.0079999585475258699 0.021645559541327394 -0.0036724357954295334 -0.0061245244119987321 0.0028359766658165378 -0.0041703813070880233 0.007392214305001984
leaf_weight=247.07496291957796 559.74305098503828 1468.8504797481 308.48989303596318 1218.8394423034042 604.95597231015563 167.41608580574393 914.67932946607471 827.23038591258228 509.35883759893477 232.8008523825556 1387.7003050055355 237.74542886950076 373.60045806691051 610.01793593168259 1158.5881281960756 594.2997260093689 2206.6673350334167 278.37939336895943 117.66353182680905 23.569542083889246 464.32171371765435 42.55082593485713 1372.4726421330124 790.36416842788458 192.9200080987066 363.40845473110676 75.447043457999825
leaf_count=3460 13132 18772 4884 19239 5370 1560 12744 12409 4017 3343 13949 3122 4014 7666 16583 7173 25153 3672 988 300 10023 402 24672 20348 2385 5699 921
internal_value=0 0.00035832 -0.000610344 -0.000205494 0.00187004 0.00035611 0.00288986 -0.000585724 0.00372594 0.00443569 0.0029241 0.000437067 0.00734825 0.00230057 0.00182955 0.000730169 0.00144837 0.00372565 0.00200562 -0.00108609 -0.00573824 0.00958602 -0.00277059 -0.00433699 -0.0020936 -0.000584843 -0.00026914
internal_weight=0 15999 9747.32 9035.92 6251.73 7817.08 4419.47 5263.19 3504.79 2995.43 1974.33 3582.23 1021.11 2553.89 2386.48 1776.46 2562.08 1741.53 2324.33 1182.16 711.397 647.507 1680.96 1350.11 1020.15 1832.26 353.826
internal_count=246000 212520 139617 126134 72903 106895 48432 73613 35688 31671 21885 44057 9786 33282 31722 24056 29263 18542 26141 16883 13483 5772 29556 33480 14794 24471 4593
is_linear=0
shrinkage=0.0152673


Tree=165
num_leaves=28
num_cat=0
split_feature=19 14 409 11 10 1 143 149 416 21 129 135 67 24 390 6 19 21 11 29 141 155 6 391 140 19 19
split_gain=117.47 105.031 96.5005 59.8769 51.6273 45.9805 48.0032 52.9667 46.2215 45.7918 31.7627 38.621 29.9367 28.9477 34.7525 27.6695 26.3615 24.9764 24.6956 23.8526 23.6847 23.2849 21.6576 23.374 20.9847 20.9817 20.4679
threshold=0.19388630579008007 -1.0000000180025095e-35 -1.0000000180025095e-35 -1.0294279427942792 0.81712676830105768 1.0000000180025095e-35 2.7222222222222228 0.58126903912910022 -1.0000000180025095e-35 -1.2291473454499886 -0.58203222617731687 0.52946537059538279 1.0000000180025095e-35 1.5000000000001112 0.16570586039276028 -0.37970342522974093 -0.28696985974602296 0.74859572400426033 -0.43206820682068203 0.20160000000000006 -0.092592592592592574 273579.62625000003 -0.58470760233918118 0.1379033485638034 -0.23514851485148511 -0.31528071226839544 -0.094094051649595542
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 16 9 17 5 6 7 12 20 -3 -11 15 13 14 -5 -12 -1 24 -18 22 -7 -13 -10 -24 -4 -17 -26
right_child=-2 2 3 4 -6 8 -8 -9 19 10 11 21 -14 -15 -16 25 18 -19 -20 -21 -22 -23 23 -25 26 -27 -28
leaf_value=0.0028513772185953436 -0.0051855600967264633 0.0020908499038754988 0.0024141480417943571 2.5778972164670051e-05 -0.0008487465495449041 0.0096287519274478282 0.0078464843971153952 -0.002947671386841706 -0.0020530796395786984 0.002750950695148335 -0.0045549930107660315 0.00035091467310872725 0.0062688733402281385 -0.0020338435352822812 0.0042712605558408914 0.0054351547375001618 -0.0058750831626104682 -0.007113416834977032 -0.0021778533577668617 -0.0065106506443488744 0.0044913811917053252 0.01095327214099142 0.0052982586523315413 0.0010815593680729258 0.0041368188574632085 -0.0018646345212748846 -0.0031272906845315148
leaf_weight=177.98157786950469 964.08807256445289 1117.6413703337312 388.11102470755577 821.5817866884172 967.50628684833646 486.19685244187713 281.77113739214838 569.43469984270632 153.193374177441 404.26879725791514 1051.696366224438 967.9722666926682 361.76708449982107 428.53160911239684 1003.74233465828 94.882254730910063 596.52771626971662 148.04309022054076 1483.9010208379477 58.419582691043615 384.16257542744279 50.778568282723427 965.78914676420391 457.72170285135508 105.5923937279731 2263.1929984521121 590.71473073959351
leaf_count=1713 23005 8616 5293 10843 8674 4414 2991 8282 1898 6162 19197 14011 4094 6008 11524 871 11068 3696 21738 766 4101 551 9824 5917 1313 40116 9314
internal_value=0 0.000297737 0.000787118 0.00186429 0.00241545 0.00294579 0.0018024 0.00126437 0.00452397 -0.000690735 -0.00133597 -0.00171123 0.00218501 0.00152494 0.00236559 -0.00249122 -0.0027583 -0.00123167 -0.00324284 0.00300099 0.00737327 0.000890414 0.00336 0.00394918 -0.000419094 -0.00156659 -0.00201169
internal_weight=0 16381.1 14122.7 8172.28 6939.82 5972.31 3466.83 3185.06 2505.48 5950.43 4832.79 4428.52 2615.62 2253.86 1825.32 3409.77 2258.41 1232.46 2080.43 1635.12 870.359 1018.75 1576.7 1423.51 1084.42 2358.08 696.307
internal_count=246000 222995 188476 98952 79336 70662 43742 40751 26920 89524 80908 74746 32469 28375 22367 60184 34519 19616 32806 18405 8515 14562 17639 15741 15920 40987 10627
is_linear=0
shrinkage=0.0152673


Tree=166
num_leaves=28
num_cat=0
split_feature=19 10 2 67 19 11 149 135 21 19 19 10 1 10 391 17 154 10 0 111 391 135 166 111 17 157 391
split_gain=114.905 92.9516 95.2583 55.3947 49.0056 47.4502 44.1964 40.387 38.1248 37.3337 46.3997 37.4695 36.5993 38.996 36.2695 33.6404 30.1332 27.8172 27.0244 26.1484 26.1343 25.1265 24.689 27.457 24.2779 23.9636 23.9071
threshold=1.0000000180025095e-35 -0.56647438538662265 1.0000000180025095e-35 1.0000000180025095e-35 -0.013319222063253615 -1.2626512651265125 -0.55593076250974105 0.48754556500607543 -1.4458113164070314 -1.0000000180025095e-35 -0.23365734194992674 0.5060431259442385 1.0000000180025095e-35 0.08165087213294879 -0.16577837173759505 1.0000000180025095e-35 1.3571428571428574 0.68871034198599113 1.0000000180025095e-35 6148.6875000000009 1.4145872876544134 0.43772782503037672 88754.895000000019 6781.9725000000008 1.0000000180025095e-35 11812.500000000002 -0.13661918361854106
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 3 5 -1 -3 16 24 -4 10 11 -8 13 -11 -6 20 22 19 26 -12 21 -10 23 -7 -2 -14 -16
right_child=7 2 8 -5 14 6 9 -9 15 12 17 -13 25 -15 18 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0092428846187165414 -0.0046744108844859623 -0.002027884559243224 0.0025451405983738687 0.0054148563095839609 -0.0052769194622824932 0.0054804696329142531 0.007957465147963123 0.00051053464751851362 -0.0025260732786236187 -0.0011213562029824791 -0.0013745747424759027 0.00062757273107527602 0.004443786518542007 0.0032047308187616234 0.010839711565217194 0.0018357137117895801 0.0013473559383201967 -0.00600065257648908 -0.0073387943534483193 0.01041887442098512 -0.0092578433589391891 0.00088686106382344422 0.020565370798558399 0.020593737976560611 0 0.020460543355378301 -0.0009796739069424
leaf_weight=85.234091226011515 1726.6186285037547 750.08114702254534 689.25084901228547 1016.1079943533987 762.28770560026169 598.82224128581583 217.8248087875545 604.66617619246244 2231.3251157552004 874.3438470736146 757.08362656459212 652.32673077657819 1046.3503913227469 1085.9019122961909 40.655196027830243 627.66739747487009 358.09868794679642 323.42548179626465 155.94634726271033 46.211715532466769 113.07864650152624 644.33111692592502 29.776109214872122 29.780242763459682 307.72124747559428 22.411353833973408 1544.07945243828
leaf_count=1165 37508 11903 4793 10827 14510 5961 2048 10618 33282 12844 9589 5611 10945 12705 548 7128 3870 3701 2885 535 2128 8072 210 284 5557 207 26566
internal_value=0 0.000519493 0.00108111 0.00208671 -0.0021055 0.00158734 0.00203769 -0.00294025 -0.000740491 0.00144778 -0.000168545 0.00247439 0.00251631 0.00127054 -0.00249632 -0.00136934 0.00494457 -0.00221786 -0.00127289 -0.0006823 -0.00204558 -0.00175816 0.00688622 0.00621736 -0.00397038 0.00479198 -0.000669347
internal_weight=0 14702.4 12114.2 7808.55 2588.2 6792.44 6042.36 2639.01 4305.65 5025.88 1996.87 870.152 3029.01 1960.25 2502.97 3616.4 1016.48 1126.72 1740.68 803.295 2988.73 2875.66 658.379 628.602 2034.34 1068.76 1584.73
internal_count=246000 192317 146643 91240 45674 80413 68510 53683 55403 58185 21484 7659 36701 25549 44509 50610 10325 13825 29999 10124 43482 41354 6455 6245 43065 11152 27114
is_linear=0
shrinkage=0.0152673


Tree=167
num_leaves=28
num_cat=0
split_feature=20 21 128 14 130 149 154 141 155 111 414 20 11 264 8 122 155 19 33 19 157 390 19 142 143 124 141
split_gain=113.418 102.672 78.7995 64.4456 55.5719 51.4798 48.1367 39.6 36.3128 35.9847 40.5751 33.4128 30.7701 30.4392 27.8212 27.1756 27.1439 27.1121 24.8154 24.553 23.789 24.2839 22.6926 22.5746 25.2118 22.1797 21.5335
threshold=-1.055547744992388 0.64988196944952348 1.0677241379310347 -1.0000000180025095e-35 1.0000000180025095e-35 -0.58342319933459807 2.5000000000000004 -0.12962962962962959 1567.9800000000002 7757.4037500000004 -1.0000000180025095e-35 -2.0580407920971773 -1.8655115511551152 -96505.784999999989 -0.70318877551020398 4.7068965517241388 165056.09625000003 -0.31528071226839544 0.0028499999999999988 -0.27656332852295634 281.25000000000006 -0.057234430688367817 -0.37481395413786084 0.34375000000000006 2.3888888888888897 1.1250000000000002 -0.2407407407407407
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=11 2 3 -2 5 6 14 9 -9 10 -7 -1 -13 -4 -5 16 18 -6 26 -15 21 25 -3 -23 -25 -19 -14
right_child=1 22 13 4 17 7 -8 8 -10 -11 -12 12 15 19 -16 -17 -18 20 -20 -21 -22 23 -24 24 -26 -27 -28
leaf_value=0.0088712089395172455 -0.0027347782467365168 0.017022937219728924 0.013049051780442626 -0.0042348529538611054 0.0096538086191683865 -0.0029984536831295047 -0.0022495272158312035 -0.0030286793686830323 0.0017284459417061726 0.0088770041922071729 0.0015201131005044648 -0.0034806822520832763 0.0042573309659457229 0.0027679862365642964 0.006327659665777593 -0.0018589559514601824 0.0081748027984887874 -0.0010618637771232092 -0.00074617049546292133 -0.0040104536304091387 0.0091816939893183316 0.0070010332625256855 -0.0046296212464529913 0.00028178478028735907 0.0059822337767202419 0.0034132918202880139 0.0016099528085813011
leaf_weight=164.27563033252954 1389.9630554337054 10.998830847442148 25.963225184008479 62.855531949549913 124.87664843723178 638.69456985965371 268.14305438473821 1876.9490965697914 464.31850118935108 119.08166408911347 1681.1394518595189 237.65516924858093 1306.4427080638707 133.44162999838591 627.21212691813707 355.12105543911457 190.60711246728897 771.09101110137999 543.02631387487054 1580.333301294595 113.26022997871041 323.37443111091852 1503.4960122182965 542.77453068271279 273.82543393038213 386.92385696433485 1621.831215094775
leaf_count=974 22252 166 380 902 981 10803 4059 30344 5989 1591 22311 2545 9759 1303 7611 3233 1238 11849 4973 26728 1135 4004 40046 7582 3250 5559 14433
internal_value=0 -0.000729152 -0.000232274 0.000305328 0.000817169 -1.30448e-05 0.00321475 -0.000662096 -0.00208127 0.000696562 0.000271966 0.00210433 0.00184049 -0.00322368 0.00535134 0.00215774 0.00254985 0.00269913 0.0022379 -0.00347705 0.00233438 0.00199214 -0.0044641 0.00357486 0.00220549 0.000425828 0.00279441
internal_weight=0 12918.7 11404.2 9664.48 8274.52 5738.39 958.211 4780.18 2341.27 2438.92 2319.83 4418.96 4254.68 1739.74 690.068 4017.03 3661.91 2536.13 3471.3 1713.77 2411.25 2297.99 1514.49 1139.97 816.6 1158.01 2928.27
internal_count=246000 208845 168633 140222 117970 83610 12572 71038 36333 34705 33114 37155 36181 28411 8513 33636 30403 34360 29165 28031 33379 32244 40212 14836 10832 17408 24192
is_linear=0
shrinkage=0.0152673


Tree=168
num_leaves=28
num_cat=0
split_feature=19 14 409 7 8 6 13 135 6 8 13 7 7 387 140 165 64 6 129 21 21 126 147 112 113 19 143
split_gain=111.979 98.4899 91.6692 58.8448 61.636 57.9818 51.0105 41.8067 36.2664 40.8579 32.1016 30.7006 30.0069 28.1267 27.2154 27.1491 26.1382 24.9104 24.6466 23.3757 22.1827 22.0774 22.3925 21.9577 21.0499 20.6756 20.6356
threshold=0.19388630579008007 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.46687814890837837 1.0000000180025095e-35 -0.092535505430242262 -0.35974013381169395 0.43772782503037672 0.075944026733500439 0.51063775510204101 1.1211092795500825 -0.096411021956832724 -0.016296572743671078 0.27862778654634074 0.056930693069306933 41957.347500000011 2.9531250000000058 0.40024227234753557 -0.4929563062119876 -1.3471229168525309 -0.23406711614192396 -0.50322998310294975 1.283783783783784 -0.55432517322474217 9.1297065938837552 -0.3060815920516391 2.5000000000000004
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 13 6 14 5 16 20 10 -6 12 18 -7 -10 -1 -4 24 21 -14 -8 -16 -3 22 -5 -13 -11 -15 -25
right_child=-2 2 3 4 8 11 7 -9 9 15 -12 23 17 25 19 -17 -18 -19 -20 -21 -22 -23 -24 26 -26 -27 -28
leaf_value=-0.0014557134187462152 -0.0050854754915491971 -0.00063924467159326404 0.0011350133249636186 0.008069200371251202 -0.0031974467687487201 -0.00096598111110263066 0.0020042542374069917 0.0027417579436965918 -0.00039828974786992286 -0.0016095527118885186 0.0052655436474501301 0.014927884986574803 0.0027477654212914172 0.0054321038257178697 0.0031273598611130569 0.0056063632529586649 -0.0011234125535702349 0.0079032699746395818 -0.001774964983922635 -0.0034457990525423652 -0.0041337611885410557 0.0025851896879038635 -0.0029505896101125659 0.0065877553602771222 0.0037685738597292629 -0.0056935801765308188 0.017011427419811265
leaf_weight=1492.5630679875612 955.95494936220348 689.29635422490537 1184.7387860678136 344.49318154342473 406.46217620186508 89.35944495536387 485.01053380221128 1142.1489637903869 293.96818418614566 1095.2494918275625 196.24193315021694 106.14714805595577 469.54792708344758 40.184436518698931 149.27698816731572 176.56214162148535 337.40302250906825 421.58158619888127 2304.2693210300058 767.95764402113855 1126.6340295877308 1412.1274887640029 47.682752901688218 635.97535519301891 199.83377468958497 713.6775274630636 48.928281597793102
leaf_count=21339 23005 8134 14424 3140 5426 1087 6543 13871 4107 17230 2773 899 5629 420 1070 2032 4101 5006 35009 10853 23194 14865 509 5486 2682 12760 406
internal_value=0 0.000289633 0.000762207 0.00181021 0.0025711 0.00411899 -0.000679886 0.000256237 0.00104081 0.00169287 -0.000691683 0.00742314 0.00380246 -0.00267877 -0.000388268 -1.9107e-08 0.00275587 0.00519827 -0.00111444 -0.00236561 -0.00281256 0.00348642 0.00670519 0.00838238 -0.000772172 -0.0050871 0.00735052
internal_weight=0 16377.3 14130.9 8187.3 6085.32 3022.12 5943.6 4127.67 3063.21 2656.74 2985.52 880.41 1185.1 2246.43 2101.97 1471.65 2141.71 891.13 2789.28 917.235 1815.93 1804.3 392.176 791.051 1295.08 753.862 684.904
internal_count=246000 222995 188476 98952 72605 30493 89524 58196 42112 36686 44325 7878 14742 34519 26347 21944 22615 10635 41552 11923 31328 18514 3649 6791 19912 13180 5892
is_linear=0
shrinkage=0.0152673


Tree=169
num_leaves=28
num_cat=0
split_feature=20 1 19 391 2 143 149 391 21 165 389 8 172 11 90 391 20 389 64 125 391 13 389 7 140 167 119
split_gain=111.314 94.4831 86.9125 79.6999 67.6025 65.9051 64.7114 51.2456 39.8001 35.4239 36.197 38.2734 32.7963 32.7071 31.1745 29.6653 29.214 28.8086 28.7643 28.5715 28.3328 27.8599 26.8079 25.7825 25.3979 23.6349 23.5581
threshold=0.51688161336547822 1.0000000180025095e-35 -0.23999248241935275 -0.81178185562575544 1.0000000180025095e-35 2.6111111111111112 -0.55593076250974105 -0.64052006669616957 -1.2483043297940404 163488.19500000001 0.73889071348950008 0.51063775510204101 -1.2499999999999998 -0.78685368536853673 -1.0000000180025095e-35 -0.6485657192683002 -1.8421595884852648 -0.53535046455599156 4.671875000000008 -0.74193959426963429 -0.66068996828538784 1.1114127799864251 0.0761002880763091 -0.65845617963550407 -0.15099009900990096 1.7500000000000002 0.75417163289630518
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 -1 -4 14 6 12 15 -9 10 11 20 -5 -10 -3 -8 -15 -7 22 23 -6 -18 -14 -16 26 -19 -2
right_child=24 4 3 5 9 17 7 8 13 -11 -12 -13 18 16 19 -17 21 25 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.0042980164237420198 -0.0034778952723821099 0.00073653891251356863 -0.006129603418000602 -0.0021419136449537168 -0.0023845779005457392 0.01002679537957102 -0.00081338455903221028 0.0005472422932047184 -0.0052800424313361131 0.0071091895266235392 -0.003012713012062968 -0.0021919110677528298 0.0068474915394076087 0.0036575293985372996 -0.0048620197119713868 0.0076356998497438371 -0.0027068570260156003 0.0017922527659934699 -0.0031364156494418562 0.003839852480539059 0.0030414824717095211 0.0029280827450770602 0.0010563082975345141 0.012804674070202998 -0.0060139655700509713 0.0219069242245198 0.0038872823269299286
leaf_weight=778.0374363437295 425.13933260925114 758.85905434936285 659.28176045231521 313.61930187605321 267.5096637532115 130.01650165952742 179.74892018921673 1092.3008277341723 913.75777363590896 166.57771890424192 756.12273452244699 678.37018236890435 491.54429057426751 196.58757751062512 21.301771385595202 205.37621138431132 3391.5822387803346 713.39661334082484 127.35765591077507 2133.6040800847113 1335.4785615298897 215.93136645294726 306.71922836080194 143.8778077121824 782.05431990511715 13.786274403333662 131.65864367596805
leaf_count=6754 10565 9325 12984 4856 3628 1545 2170 8673 17951 1629 10283 10473 5776 1545 213 1988 57621 8942 1728 21332 14798 3125 3836 1222 20348 123 2567
internal_value=0 0.000347259 -0.00059352 -0.00101981 0.00181042 -0.000612285 -0.00107543 -0.00171329 -0.00207182 0.000257611 -0.000115562 0.000840821 0.0021058 -0.00268014 0.00343447 0.00367012 -0.00205298 0.00339319 0.00355505 0.00432096 0.00213007 -0.00236689 0.00463462 0.0104678 -0.00423521 0.00219211 -0.00171913
internal_weight=0 15990.7 9729.04 8951.01 6261.7 8291.72 7434.53 6195.28 5810.16 3204.06 3037.48 2281.36 1239.24 4717.86 3057.64 385.125 3804.1 857.199 925.621 2298.78 1602.99 3607.51 798.264 165.18 1338.85 727.183 556.798
internal_count=246000 212520 139617 132863 72903 119879 109269 93073 88915 40811 39182 28899 16196 80242 32092 4158 62291 10610 11340 22767 18426 60746 9612 1435 33480 9065 13132
is_linear=0
shrinkage=0.0152673


Tree=170
num_leaves=28
num_cat=0
split_feature=411 21 1 391 10 143 165 128 21 8 7 130 163 90 8 168 67 417 171 47 13 150 7 392 11 10 434
split_gain=109.308 82.0127 74.2016 70.6061 58.4921 43.6511 41.9364 41.7665 38.6558 38.2603 60.6292 29.528 29.5037 28.3466 27.0721 26.0962 25.217 25.4649 24.7105 24.698 24.0225 23.9557 23.6212 23.2602 22.9962 24.2112 27.1461
threshold=1.0000000180025095e-35 -1.3471229168525309 1.0000000180025095e-35 -0.81178185562575544 -0.16446916632330721 2.7222222222222228 34868.891250000008 0.19387931034482761 0.31785522338584254 0.51063775510204101 -0.0048516514275051305 1.0000000180025095e-35 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.27534183673469381 1.7500000000000002 1.0000000180025095e-35 1.0000000180025095e-35 3.7500000000000004 1.0000000180025095e-35 -0.51022980703965859 0.61857707509881432 0.028239099334452948 -1.5410832847635565 -1.0085258525852583 0.74282378794121695 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 -1 3 -3 5 15 9 11 13 10 16 19 -12 -2 -14 23 17 -4 -8 20 -6 22 -22 -5 -15 26 -26
right_child=8 2 6 4 7 -7 18 -9 -10 -11 12 -13 14 24 -16 -17 -18 -19 -20 -21 21 -23 -24 -25 25 -27 -28
leaf_value=0.0032286434841675119 -0.0039944329883397044 -0.006302641884699433 -0.0010743540277211052 0.0010554367333450471 -0.0032380128911686408 0.0026431365708079399 0.0080885886705807757 -0.0015055856413430961 -0.0058332746238074296 -0.0018687796632500561 -0.0015765197585307538 0.0044794069939095666 -0.00043055180264621739 -0.0045428955002838134 0.0061340165235848681 0.005652954711109888 0.0047393965092232485 0.0076392602820131109 0.0016709628391583505 -0.0030910011554322703 0.00013441610609287534 0.011148366722139534 0.0045891176570869944 -0.0038246078864687134 0.00028395761723433373 -0.0034359566359899998 0.0075373652243465594
leaf_weight=2299.4008738100529 848.24001255631447 526.00886980444193 1576.7470668815076 253.5720985904336 198.61934403888881 373.06204810738564 337.22316267155111 1258.001883674413 642.24219861440361 845.9600195735693 171.90854479931295 733.81003803387284 168.99576918594539 297.15630947798491 983.20250299200416 78.130534691736102 231.46247251145542 81.883052099496126 246.1351667996496 308.10431957803667 695.00568727962673 70.095151614397764 466.57783664390445 2002.5925619136542 1138.7299096658826 357.33794096857309 134.73132981546223
leaf_count=16038 14113 11191 20249 5387 2926 5706 3006 17922 17739 13429 2249 8953 2125 5330 10877 1035 2681 1029 2925 4444 8432 621 5861 39002 16955 4077 1698
internal_value=0 0.00059449 7.18205e-05 -0.000924157 -0.00048308 -0.00219208 0.00156737 0.000754895 -0.00245263 0.0010145 0.00177628 0.00190889 0.00428126 -0.00166689 0.00516332 -0.00296892 1.6291e-05 -0.00063779 0.00539801 0.00081817 0.00166697 0.00246578 0.00193212 -0.00327203 -0.000637785 6.86387e-05 0.00105962
internal_weight=0 13906.5 11607.1 6963.58 6437.57 2707.36 4643.52 3730.21 3418.44 4060.16 3214.2 2472.21 1324.11 2776.2 1152.2 2334.3 1890.09 1658.63 583.358 1738.4 1430.3 1231.68 1161.58 2256.16 1927.96 1630.8 1273.46
internal_count=246000 186088 170050 111480 100289 51130 58570 49159 59912 52639 39210 31237 15251 42173 13002 45424 23959 21278 5931 22284 17840 14914 14293 44389 28060 22730 18653
is_linear=0
shrinkage=0.0152673


Tree=171
num_leaves=28
num_cat=0
split_feature=20 130 141 1 2 390 19 10 416 165 0 118 149 162 143 19 140 145 20 19 391 140 140 149 135 12 128
split_gain=107.651 91.2351 92.9581 61.4168 54.6681 49.9039 48.7499 47.5644 47.8862 47.5023 45.4793 37.1026 35.8293 35.7537 34.836 31.5168 31.4055 28.7276 27.1547 26.193 25.1257 25.964 24.8297 23.6781 23.6557 23.5236 21.0141
threshold=0.51688161336547822 1.0000000180025095e-35 0.055555555555555559 1.0000000180025095e-35 1.0000000180025095e-35 0.29782425509802973 -0.31936837048240385 0.78512566955088603 -1.0000000180025095e-35 103718.70000000003 1.0000000180025095e-35 -0.015467625899280574 -0.12923255746832393 899.19000000000017 3.7222222222222228 -0.23999248241935275 0.051980198019801992 1.0000000180025095e-35 -1.0155440627755654 -0.23999248241935275 0.12742144408804593 7.0173267326732676 -0.15099009900990096 -0.057167895928611136 -0.75789793438639108 -0.55505843681519351 0.73794827586206913
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 5 7 15 -3 8 -5 17 11 25 -7 -11 20 -1 18 19 -17 -4 21 -13 -2 -21 -10 -8 -27
right_child=22 6 9 4 -6 12 10 -9 24 13 -12 14 -14 -15 -16 16 -18 -19 -20 23 -22 -23 -24 -25 -26 26 -28
leaf_value=0.0044846264337666808 -0.0016872179938132858 0.0089742096628193397 0.00063632483431372484 0.0093376047320832614 0.00020550208094230845 0.0036522360884183157 -0.0030617587159581846 -0.00082544789389864877 0.0089134836170478328 0.020266962736948224 -0.0035770610241774347 0.0044545677287084889 -0.00071938300279943536 0.0013298324170233687 0.0075769715757849024 0.003195518833727162 -0.0043894581150268844 0.0078472570172642767 -0.0021569876977294259 -0.0021469607098687777 0.00045378035585011384 -0.0022987685971458771 -0.0059425964368889283 -0.0047604762867634867 0.0018256552339554327 0.0024597595998090927 -0.0032281895014769973
leaf_weight=160.83689551055431 555.56038187816739 231.89271536096931 419.61229321733117 500.45299989171326 1477.4350965358317 846.94924671202898 375.04910816624761 328.10983872227371 136.42773300409317 24.418422274291515 339.14514256455004 1318.1106611471623 896.76502352580428 456.72196487896144 379.39249617606401 301.56101413816214 1055.0221156869084 57.857015527784824 818.32230166904628 1713.2562395371497 842.52656283974648 145.55056072957814 776.87454028986394 1563.0768378265202 590.18391017429531 825.58280067518353 184.00372207909822
leaf_count=1457 13132 1683 4139 4661 18589 9175 6589 2680 1633 260 5005 13326 12320 5153 3798 2880 17293 841 14002 25733 11124 1539 20348 26593 6546 12470 3031
internal_value=0 0.000340754 -0.000396166 0.000669174 0.00231519 -0.000552261 0.0021443 0.00431325 0.00569469 -0.00218739 0.00178264 0.00223164 0.0013989 0.00231797 0.00327845 -0.00201279 -0.00249786 -0.00276739 -0.000707179 -0.00293645 0.00256673 0.00377652 -0.0041757 -0.00339683 0.00317115 0.000194492 0.00141359
internal_weight=0 15988.3 11347 7112.07 3032.61 4079.46 4641.25 1555.17 1227.06 4234.94 4409.36 4070.22 1743.71 481.14 2685.58 2335.74 2174.91 3753.8 1119.88 3695.95 2306.19 1463.66 1332.43 3276.33 726.612 1384.64 1009.59
internal_count=246000 212520 153955 91236 34109 57127 58565 15520 12840 62719 56882 51877 21495 5413 29787 35632 34175 57306 16882 56465 25989 14865 33480 52326 8179 22090 15501
is_linear=0
shrinkage=0.0152673


Tree=172
num_leaves=28
num_cat=0
split_feature=21 14 1 128 10 416 143 10 414 17 150 155 7 8 86 387 163 143 21 6 111 17 387 388 168 70 131
split_gain=105.731 97.3945 94.6423 72.3563 56.3779 79.0736 50.4976 63.613 41.4689 34.7671 30.9574 29.5054 29.2433 45.9659 29.0079 27.0922 26.567 26.0112 25.7746 25.719 24.9337 25.7942 23.763 26.9139 22.6158 24.7595 23.3669
threshold=0.77609554057632191 -1.0000000180025095e-35 1.0000000180025095e-35 1.0677241379310347 0.72043675319324285 -1.0000000180025095e-35 2.1666666666666674 -0.16446916632330721 -1.0000000180025095e-35 -1.0000000180025095e-35 0.61857707509881432 244704.39750000002 -0.46687814890837837 1.0000000180025095e-35 1.0000000180025095e-35 0.29019879267634097 -1.0000000180025095e-35 -1.3888888888888886 -0.15186092134132381 -0.45677944862155384 1890.5850000000003 1.0000000180025095e-35 0.70198368591164573 -0.3491846764486925 2.2500000000000004 0.58494208494208511 0.48868046571798196
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 15 3 6 5 -4 7 14 20 -7 16 -8 -11 22 19 -1 -10 -6 -15 -3 21 -9 -14 -24 25 -2 -26
right_child=24 2 4 -5 17 9 11 8 10 12 -12 -13 13 18 -16 -17 -18 -19 -20 -21 -22 -23 23 -25 26 -27 -28
leaf_value=-0.0014361815959711803 -0.0051121493959170421 -0.005487054808206009 0.0065978908167423547 -0.0036821505205207336 0.034879333842901358 -0.0040668789422226882 0.0030612945500863493 -0.0034566912241506833 -0.0021366840773627939 -0.00095123549640215141 0.0094783110545431353 0.01548075592969869 0.0070916638620524691 0.0035901522795492085 0.0062647771762584211 -0.0050653596029662448 0.0022031520821138816 -0.00073811135050539517 -0.0010543937221586944 -0.0015502479860501457 0.0043858624257882648 0.0026533578852292144 0.024561272783728719 -0.0010287816987007586 0.0011952537397798238 0.0002410365270846282 0.034278581851325318
leaf_weight=1470.4172456637025 1190.5900738332421 503.82922469638288 1219.2235935255885 1155.18909936212 4.5923646278679362 208.73374770581722 918.34120732545853 821.97905384376645 373.93058343604207 481.62666029855609 123.23206556774676 47.164928941056132 701.76921114698052 533.54324362613261 92.0711634401232 719.5105926822871 2608.7458351068199 1069.1659205611795 577.90915860049427 1719.181981915608 150.14016219042242 198.40605549886823 10.008656043559311 151.33256450667977 21.157000500708822 238.47012370824814 6.5850201919674864
leaf_count=20754 30068 9490 12831 18586 43 3367 11195 12722 4912 6070 1019 422 6698 5568 1336 12329 29170 9356 8798 29484 1966 2412 95 1783 407 5007 112
internal_value=0 0.0003549 0.000834274 -0.000123038 0.00251828 0.00337459 0.00041989 -5.64295e-05 0.00104566 0.00189608 0.00196981 0.00368055 0.00240684 0.00323058 -0.00209609 -0.0026331 0.0016559 -0.000570782 0.00116719 -0.00244703 -0.00139858 -0.00225938 0.00587619 0.000530411 -0.0039426 -0.00421253 0.0095651
internal_weight=0 15860 13670.1 8712.21 4957.91 3884.15 7557.02 6591.52 4276.43 2664.92 3105.91 965.506 2456.19 1974.56 2315.08 2189.93 2982.68 1073.76 1111.45 2223.01 1170.53 1020.39 863.11 161.341 1456.8 1429.06 27.742
internal_count=246000 210406 177323 122714 54609 45210 104128 92511 52201 32379 35101 11617 29012 22942 40310 33083 34082 9399 14366 38974 17100 15134 8576 1878 35594 35075 519
is_linear=0
shrinkage=0.0152673


Tree=173
num_leaves=28
num_cat=0
split_feature=19 67 21 20 157 11 164 513 20 141 66 149 113 49 143 141 21 143 19 135 138 11 148 390 124 12 17
split_gain=105.69 91.7328 87.2443 88.8633 47.1135 45.2127 41.8804 40.9494 34.1208 29.5699 32.3612 29.2367 29.2228 28.663 26.5101 25.6879 24.5881 23.2594 22.3462 22.3205 22.2344 25.4377 21.5851 22.0339 20.3182 20.4328 20.2194
threshold=0.19388630579008007 1.0000000180025095e-35 -1.3471229168525309 -0.070954388596485909 191.25000000000003 0.37871287128712877 171427.09500000003 1.0000000180025095e-35 -1.6973680938911146 0.94444444444444453 1.0000000180025095e-35 -0.19168877239106538 14.31449661931642 1.0000000180025095e-35 2.3888888888888897 1.0000000180025095e-35 -2.0089485232886477 1.8333333333333335 -0.37481395413786084 0.40249088699878499 1.5000000000000002 0.16639163916391642 0.41599200655872115 -0.54526803573712035 1.8750000000000002 -0.066745799853907953 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 16 6 5 11 7 8 -4 10 12 22 -10 -7 -13 -3 -1 -11 -9 -6 -14 -22 23 -5 25 -17 -12
right_child=-2 15 3 4 19 13 -8 18 9 17 26 14 20 -15 -16 24 -18 -19 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=0.005467996399491761 -0.0049670804881193657 0.0048622762863683904 0.0035997087622108995 -0.0055640941807035098 -0.0011094112961350644 0.0010739476764935483 0.0055721450664682464 0.0099810909492400839 0.0012034706089962377 -0.0039978007981622326 -0.0019189418496676676 -0.0053562833869593759 0.004916420275364603 -0.0043612690004681525 -4.634146161075797e-06 -0.0024684000087229711 0.0016811071365567644 0.0033011641890388641 -0.002815482302093743 0.0096297880607869018 0.030473108018630464 0.0021969461368070288 0.016359166519269271 -0.0006619730839127389 0.0060517758603416266 0.0024995111869184719 0.0021203199500148639
leaf_weight=509.84753409028053 946.2490871809423 1111.7617059238255 785.41671570017934 287.70061650313437 74.456670951098204 963.2092121373862 342.70536971837282 32.217914987355471 2288.9707032870501 582.44898157566786 1276.59499964118 1804.3833060562611 211.33833265304565 295.12495325505733 248.94722009822726 335.67659999802709 1917.8356314487755 121.76734421774745 1164.2704257033765 108.90378818847239 18.240964528173212 13.700454320758579 14.987410824745892 852.04842421784997 181.35207885876298 451.8450182620436 371.25683089904487
leaf_count=3161 23005 12777 5602 6559 1203 16630 2924 246 27344 8294 15359 42835 2338 5532 4844 5017 14295 1563 14683 1463 216 125 278 17425 2169 5842 4271
internal_value=0 0.000280217 -0.000155378 -0.000695807 -0.00234163 -0.00265443 0.000364512 0.000103101 0.000646025 0.000169058 0.000658432 -0.00361658 0.00174334 -0.000194019 -0.00471197 0.0032753 0.00248056 -0.00272214 -0.00246164 0.00522259 0.00678013 0.0187189 -0.00166037 -0.00190818 0.00144419 0.000370249 -0.0010032
internal_weight=0 16367 14286.4 11858.7 4649.76 4466.4 7208.93 6866.22 5669.74 4884.32 4180.1 3208.07 2532.25 1258.33 2053.33 2080.64 2427.68 704.216 1196.49 183.36 243.28 31.9414 1154.74 1139.75 968.874 787.522 1647.85
internal_count=246000 222995 197190 179734 96769 94103 82965 80041 65112 59510 49653 71941 30023 22162 47679 25805 17456 9857 14929 2666 2679 341 24262 23984 13028 10859 19630
is_linear=0
shrinkage=0.0152673


Tree=174
num_leaves=28
num_cat=0
split_feature=411 391 391 0 391 391 391 10 391 391 391 164 0 141 119 387 147 143 17 141 391 391 10 391 6 138 129
split_gain=103.667 78.0065 92.3244 109.47 76.8335 78.9979 54.1043 50.7039 48.9713 62.2107 38.2019 36.3196 36.1484 34.9474 34.6118 32.4274 31.6943 29.7775 27.9668 27.9279 27.057 26.9113 25.8945 25.3056 23.7695 22.4262 22.1618
threshold=1.0000000180025095e-35 -0.80185022711144738 0.12742144408804593 1.0000000180025095e-35 -0.043865024937375957 -0.64052006669616957 -0.92257102786474277 -0.55026782035434685 0.48751167347278374 0.51300508801153255 0.049180694651566131 59136.232500000006 1.0000000180025095e-35 -0.53703703703703687 -1.0000000180025095e-35 -0.24877276285889841 0.85135135135135143 2.0555555555555558 1.0000000180025095e-35 0.055555555555555559 0.10767533198381948 -0.6485657192683002 0.70477956324680691 0.040151588545052345 -0.49309941520467832 1.5000000000000002 -0.41285346292626152
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 6 3 4 5 21 -1 14 -4 -10 18 25 15 -5 -7 22 -13 19 23 26 -12 -3 -2 -6 -25 -11 -9
right_child=12 2 8 13 10 7 -8 17 9 11 20 16 -14 -15 -16 -17 -18 -19 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=5.9856424656423833e-05 0.0015006258390760816 0.0025144165941672647 -0.0032783104451984376 0.0033398371657912727 0.0044847357306539411 -0.0074644806082829881 -0.0064813912504430226 0.0046889131030249127 0.0089799445314767568 -0.0015236689727670184 0.00085069786264104527 0.009073324225692023 -0.0067911024679638467 -0.003846941774129514 -0.00033692510359490269 -0.0030767859666165848 0.00067902321632800386 0.0059615941612904911 0.012052952325216658 -0.00095952315498210039 0.0060607809365549438 0.0076396317284157366 -0.003756655285462083 -0.0042372770413756384 0.012631269906450764 0.0021071778425752223 0.00090748957613814298
leaf_weight=589.6626750882715 867.53453849256039 430.92485843971372 1297.418279837817 190.12824922241271 722.50666003674269 271.56482281163335 583.64155579544604 540.01353125087917 178.06546865217388 2388.6214891020209 608.95667784288526 164.38772359862924 387.60813273303211 890.71949608251452 389.02568163536489 1857.2305163238198 296.31498543731868 298.56868324242532 210.7600877340883 1133.8843411635607 380.6123702339828 555.59650363959372 291.41230022907257 20.967326745390892 172.73167869634926 473.41541882790625 1116.358651900664
leaf_count=7537 13931 4259 21304 2426 7834 5657 12240 5149 1974 38015 7361 1605 7686 13417 5918 34823 3852 2946 1714 13789 3460 4739 3472 262 1475 7657 11498
internal_value=0 0.000578046 0.000925761 0.00193716 0.00265008 0.00156642 -0.00318673 0.000552151 -0.000744574 0.00019196 0.00507017 -0.000276743 -0.00239456 -0.00257388 -0.00328226 -0.00182612 0.00369679 0.00137532 0.00699778 0.000880895 0.0028647 0.00541112 0.000170382 0.00582253 0.0107556 -0.000919777 0.00214626
internal_weight=0 13904.8 12731.5 7933.32 6852.47 4735.94 1173.3 3749.42 4798.22 3500.81 2116.53 3322.74 3403.79 1080.85 660.591 3016.18 460.703 3088.83 1126.97 2790.26 989.569 986.521 1158.95 916.206 193.699 2862.04 1656.37
internal_count=246000 186088 166311 91904 76061 53955 19777 44957 74407 53103 22106 51129 59912 15843 11575 52226 5457 33382 11285 30436 10821 8998 17403 9571 1737 45672 16647
is_linear=0
shrinkage=0.0152673


Tree=175
num_leaves=28
num_cat=0
split_feature=19 14 1 391 128 19 130 164 0 390 154 387 20 13 67 391 6 391 21 125 387 166 128 130 147 20 20
split_gain=102.156 90.6362 81.2248 77.3306 66.8465 52.4731 51.4479 49.7485 42.4538 39.4272 35.1994 33.18 27.695 27.5209 27.2843 27.1599 26.4001 26.4544 25.3252 26.2339 21.6649 21.3629 21.0055 20.9956 22.5499 20.6807 20.4036
threshold=0.19388630579008007 -1.0000000180025095e-35 1.0000000180025095e-35 -0.84913404291403738 1.0677241379310347 -0.23674106267790407 2.0416666666666674 36029.92500000001 1.0000000180025095e-35 0.219808077042038 3.785714285714286 -0.46988402741854279 0.51688161336547822 -0.41985843110637056 1.0000000180025095e-35 -0.92257102786474277 -0.58470760233918118 0.22868048666705626 -1.584014230423459 -0.39650825075464791 0.27862778654634074 181399.20750000002 2.2057068965517241 0.79166666666666685 0.98648648648648662 -1.2978146567935001 -0.78572725661621623
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 12 3 15 5 -5 7 9 11 13 -9 14 20 -7 -4 -3 26 22 -11 -20 21 -1 23 24 -18 -19 -13
right_child=-2 2 8 4 -6 6 -8 10 -10 18 -12 16 -14 -15 -16 -17 17 25 19 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.001305313593533158 -0.0048980317781950793 -0.0018985560515225261 0.0036726693572275066 0.0049244021138430344 -0.003338336233633579 -0.0045811330595516477 0.0044226786739601145 0.0053263428843181703 -0.0026983418544205598 0.0054070030678746821 -0.0012687090917369059 0.0021088304582866642 -0.0075982832258884164 -0.0010394877409064997 0.0098571188427406982 -0.0084936876315727348 0.0035147117651396428 0.004801367611643936 0.0026013351390934262 -0.001076194360772697 -0.004282277694588707 0.0079694843731987468 -0.0024166213923835864 0.0066718758003469526 -0.00178413163634139 -0.00092632907210070392 -0.0058703172678174296
leaf_weight=1285.7796190474182 940.84412202052772 273.59851106442511 1387.6998956464231 638.77643843367696 1072.3384881448001 678.20089469663799 647.39507438987494 599.07091657444835 377.3916548229754 249.33920732885599 272.27738230116665 126.14496421813965 231.24634438753128 2125.0619271993637 191.58470412530005 321.87181160971522 1272.5662122424692 179.30691534653306 703.94895536452532 1260.6343969646841 653.73069443739951 60.209710203111172 144.23820463195443 408.07557050138712 216.90135395154357 807.75000147335231 178.33448246493936
leaf_count=17359 23005 4018 13653 5465 17312 12270 7904 5764 5394 1611 3689 1080 5863 33797 1667 7544 13622 1357 9334 18839 10707 590 1827 4130 2574 12770 2855
internal_value=0 0.000274818 0.000726785 -0.000167493 0.00021514 0.000747601 0.000337849 -0.000109823 0.0022233 -0.000696168 0.0032552 0.00260335 -0.00258396 -0.00189986 0.00442986 -0.00548048 0.001735 0.00216744 0.00082384 0.000237005 -0.00199882 -0.0008825 0.00315959 0.00358849 0.00273679 0.000105637 -0.0025353
internal_weight=0 16363.5 14132.5 8842.51 8247.04 7174.71 6535.93 5888.53 5289.99 5017.19 871.348 4912.6 2230.97 2803.26 1579.28 595.47 3333.32 3028.84 2213.92 1964.58 1999.72 1345.99 2041.78 1897.54 1489.47 987.057 304.479
internal_count=246000 222995 188476 127547 115985 98673 93208 85304 60929 75851 9453 55535 34519 46067 15320 11562 40215 36280 29784 28173 28656 17949 22153 20326 16196 14127 3935
is_linear=0
shrinkage=0.0152673


Tree=176
num_leaves=28
num_cat=0
split_feature=20 130 141 1 416 10 390 155 0 391 391 125 21 21 128 119 150 0 430 389 21 391 20 134 67 391 391
split_gain=100.746 86.8317 87.3997 56.1992 49.5516 77.9036 46.5885 44.3373 38.7442 37.822 48.4282 35.9138 33.1091 29.5526 29.4819 24.6196 24.5539 24.3558 24.1012 23.9343 23.4768 22.8156 22.5901 23.0864 22.1836 21.8348 28.8874
threshold=0.51688161336547822 1.0000000180025095e-35 0.055555555555555559 1.0000000180025095e-35 -1.0000000180025095e-35 0.80641395412718042 0.29782425509802973 104349.91500000002 1.0000000180025095e-35 0.12650512597654215 -0.81178185562575544 -0.066470532481089153 -1.7794007366397382 -1.0130370759385332 1.3517068965517243 0.72377830750893934 0.61857707509881432 1.0000000180025095e-35 1.0000000180025095e-35 1.0313227980861785 0.64988196944952348 -0.6485657192683002 -1.8421595884852648 0.28180212014134282 1.5000000000000002 -0.043865024937375957 -0.64052006669616957
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 6 5 17 12 13 9 10 -3 -8 -1 21 18 -2 -14 -5 24 20 -6 -4 -11 -24 25 26 -12
right_child=15 8 7 4 19 -7 11 -9 -10 22 14 -13 16 -15 -16 -17 -18 -19 -20 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.0039881446355648012 -0.0051944464254383271 -0.0027911876816441119 -0.0069996314543349005 0.0078014428376635891 0.0020846199142568501 -0.0014874798881124912 0.003223773153043087 0.0022029141326355994 -0.0027437101850268804 0.0085462042981410257 0.0074646452838721808 -0.0012028411771705344 -0.0030162594611669903 -0.0034513017271009831 -0.00054089896185904613 -0.00019540437572659051 0.0027917179207219553 -0.0018593187673615413 0.011126554877669927 -0.0033350378801876406 -0.0037641025796840044 0.0006495491316481039 0.0018266712389963542 -0.0018481767150076377 0.01370016120250602 0.0066314206179667445 0.0018313463337253004
leaf_weight=198.84707947075367 1018.5280155688524 242.64030737988651 102.6712132692337 797.36599694751203 1359.1172209884971 345.65356018580496 1008.7428110409528 484.01985190995038 355.60393393412232 82.343136038631201 272.64155504480004 737.0061969589442 1941.7947664037347 2856.237548450008 251.93764490261674 301.45090279914439 184.11654920503497 64.150635985657573 139.60287637263536 296.81499399617314 180.1625774782151 774.82254131510854 995.46408808976412 662.82611415907741 59.959054257720709 593.27308983542025 992.11378789320588
leaf_count=1350 27027 3802 978 7890 14846 2940 11257 5420 5175 594 2391 10238 31900 49666 2985 6453 2382 867 1292 3995 3571 6655 15139 9300 595 5994 11298
internal_value=0 0.000328366 -0.000391769 0.000639676 0.00220958 0.00461312 -0.000531846 -0.00213355 0.00208577 0.00248807 0.00367241 0.00134981 -0.00194879 -0.00269825 0.00435563 -0.00405993 -0.00250873 0.00707118 0.00495962 0.000624017 0.00139372 -0.000236398 0.000746075 0.000352249 0.00450486 0.00420176 0.00305394
internal_weight=0 15979.9 11331.5 7113.77 3043.26 1207.17 4070.51 4217.75 4648.41 4292.8 2552.17 1745.75 2324.76 3733.73 2309.53 1319.98 2125.91 861.517 2057.59 1836.09 1539.28 877.494 1740.63 1658.29 1917.99 1858.03 1264.76
internal_count=246000 212520 153955 91236 34109 11697 57127 62719 58565 53390 28357 21495 35632 57299 24555 33480 34282 8757 21570 22412 18417 7633 25033 24439 20278 19683 13689
is_linear=0
shrinkage=0.0152673


Tree=177
num_leaves=28
num_cat=0
split_feature=20 21 128 414 119 7 8 131 20 264 11 90 109 167 248 90 171 118 33 143 19 13 19 126 149 165 19
split_gain=99.5476 91.4983 71.4754 56.4815 52.3992 39.3973 50.5291 34.1323 31.0423 29.0227 28.4255 28.4207 28.2383 27.7761 26.064 27.6602 25.7524 24.9653 24.3544 23.8553 23.5501 22.9419 22.4658 22.2191 21.5445 21.4427 21.4172
threshold=-1.055547744992388 0.64988196944952348 1.0677241379310347 -1.0000000180025095e-35 0.73808104886769976 0.085712508552590674 1.0000000180025095e-35 0.57082794307891349 -2.0580407920971773 -96505.784999999989 -1.8655115511551152 -1.0000000180025095e-35 0.25000000000000006 0.75000000000000011 0.30555555555555564 -1.0000000180025095e-35 -2.2499999999999996 0.88381294964028789 0.011849999999999994 2.7222222222222228 0.0028346554504373738 1.100940560457675 -0.31045995720902853 -0.28167179006942039 -0.52946948885268019 187634.62125000003 -0.37481395413786084
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=8 2 3 11 5 7 16 13 -1 -4 -10 -2 25 20 15 -12 -7 -14 -8 24 21 -5 -11 -18 -17 -6 -3
right_child=1 26 9 4 12 6 18 -9 10 22 14 -13 17 -15 -16 19 23 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=0.008460788694270617 -0.0041868215780351192 0.016455377217622209 0.012729419516320173 -0.0014329089487139018 0.001741165280511825 -0.0041555313988081554 0.0013010289053216946 0.0038951425904750333 -0.0034177920572405541 0.0038284509113345041 0.0002941432999940311 -0.00061440709937160554 0.0054765925944316157 0.0056919593886988994 6.7726333449901163e-06 0.0064014914334435446 0.0099920438978809544 0.017175471844881801 -0.0033730741834062158 0.0097584917574045048 -0.0052259105569145651 0.0050388485331209305 -0.0037682155167435625 0.0039094604949786657 0.0024269902862113146 0.010762065455548897 -0.0044127108306960009
leaf_weight=165.68368090689182 747.76020850241184 11.180153220891951 26.199038533493876 2341.9792204741389 1127.7214068323374 58.62938067689538 1323.3471167013049 325.66490795835853 236.32532128319144 94.846205081790686 780.16494943015277 1722.9242904763669 343.35915876552463 125.85469040647149 1102.9115182906389 402.36666564643383 237.95088382810354 49.635442089289427 322.61932031810284 141.18891958519816 368.30038486234844 134.31530627608299 1600.3995150178671 359.84462950378656 1603.1949220001698 65.334551051259041 1476.1514050811529
leaf_count=974 13827 166 380 32533 13647 702 20243 4201 2545 857 7614 27782 3920 1319 9102 2909 2321 434 5497 1034 7503 1692 27174 3995 12977 606 40046
internal_value=0 -0.000686327 -0.000219885 0.000290239 0.000975814 0.000280007 0.00181352 -0.000788447 0.00196681 -0.00308609 0.00171207 -0.00169957 0.00342578 -0.00130524 0.00201533 0.00276901 0.00539536 0.00698545 0.000379013 0.00366404 -0.00161842 -0.0010778 -0.00333739 0.00634847 0.0032295 0.00224457 -0.0042475
internal_weight=0 12864 11376.7 9655.24 7184.56 5598.51 2302.39 3296.11 4431.84 1721.44 4266.15 2470.68 1586.05 2970.45 4029.83 2926.92 656.425 392.995 1645.97 2146.75 2844.59 2476.29 1695.25 597.796 2005.56 1193.06 1487.33
internal_count=246000 208845 168633 140222 98613 80006 32758 47248 37155 28411 36181 41609 18607 43047 33636 24534 7018 4354 25740 16920 41728 34225 28031 6316 15886 14253 40212
is_linear=0
shrinkage=0.0152673


Tree=178
num_leaves=28
num_cat=0
split_feature=19 14 7 8 7 8 166 0 1 69 20 20 10 10 163 13 387 513 7 8 21 20 109 8 20 131 113
split_gain=98.017 87.3472 77.1105 101.508 58.1437 54.3045 38.0556 35.896 35.6044 32.9682 32.7565 26.5829 26.565 26.3134 25.9684 25.8264 24.704 24.2778 24.1485 24.1089 23.8443 27.1622 23.0801 22.8842 22.6186 21.8588 21.2383
threshold=0.19388630579008007 -1.0000000180025095e-35 -0.46140449088760332 1.0000000180025095e-35 0.02326304658829384 -0.27534183673469381 91241.268750000003 1.0000000180025095e-35 1.0000000180025095e-35 1.0000000180025095e-35 0.03385880314723428 0.51688161336547822 0.81712676830105768 0.78512566955088603 -0.56249999999999989 1.100940560457675 0.34997975935878928 1.0000000180025095e-35 0.21260185357964798 0.072596938775510225 -0.24228079682889067 -0.46464867409446292 2.2500000000000004 0.51063775510204101 -1.7357936452326219 0.50808538163001304 2.1836350102350974
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 11 6 4 8 -6 9 10 22 15 17 -1 14 16 -7 20 -10 18 24 -12 -3 -22 25 -21 -5 26 -4
right_child=-2 2 3 7 5 12 -8 -9 13 -11 19 -13 -14 -15 -16 -17 -18 -19 -20 23 21 -23 -24 -25 -26 -27 -28
leaf_value=-0.0019714027384132742 -0.0048153718543809667 -0.00092048474102376075 -0.0020196700430725203 0.0059998617878015675 0.00010448056105161423 0.00070648774947926435 0.0039782862224579715 -0.0090881648346378182 0.0063166717591376523 0.0029419394525062076 -0.0058315154704571626 -0.0074876516430103235 0.0010084431794113347 -0.0011238914593480595 0.0077689134931760552 0.0034081713676190899 0.00038028520477459806 -0.0016088690402432286 0.0027093693156148464 0.0014132090837158855 -0.0016591342348916992 -0.005653918776871548 0.013491308799261897 -0.0021664894446963923 -0.00091819383237037812 0.0037355342656516161 0.002235567170526755
leaf_weight=1995.6875759772956 934.3077079243958 1241.0534194223583 997.07997038774192 123.73071096464992 418.50330178625882 137.80521754361689 302.67412985116243 99.342646239325404 674.71427412889898 325.03335464186966 251.17167842015624 228.5152473077178 196.43670249730349 208.2067569103092 1236.4749977104366 180.79327885247767 220.05206060037017 658.39814342744648 1825.2863521222025 681.3446692135185 768.86450183205307 838.61275236867368 29.710781032219529 1062.1016886737198 986.77620811760426 293.99447806738317 374.83431297913194
leaf_count=28656 23005 12894 14108 875 5582 1515 2978 1907 6642 4216 5119 5863 1475 1610 11703 2294 2693 8116 20730 12910 9727 18781 350 22726 12117 3316 4092
internal_value=0 0.000268382 0.000711487 0.00137819 0.0030162 0.00501384 -0.00119581 0 0.00159276 -0.00166563 0.000161236 -0.00254288 0.00631589 0.0037281 0.0070676 -0.00216318 0.00486737 0.00103341 0.00162918 -0.00140573 -0.00252022 -0.00374934 0.00019808 -0.000762276 -0.000138207 -3.50924e-05 -0.000850222
internal_weight=0 16357.2 14133 10476 4787.81 1989.22 3657.03 5688.15 2798.59 3354.36 5588.81 2224.2 1570.72 1102.97 1374.28 3029.32 894.766 3594.19 2935.79 1994.62 2848.53 1607.48 1695.62 1743.45 1110.51 1665.91 1371.91
internal_count=246000 222995 188476 137586 53086 20275 50890 84500 32811 47912 82593 34519 14693 10945 13218 43696 9335 41838 33722 40755 41402 28508 21866 35636 12992 21516 18200
is_linear=0
shrinkage=0.0152673


Tree=179
num_leaves=28
num_cat=0
split_feature=411 391 391 21 391 109 119 19 21 155 129 109 119 128 124 10 391 391 130 143 112 20 172 149 7 8 148
split_gain=96.5583 73.0853 85.78 65.6243 51.6341 48.5885 43.0725 36.8885 35.3176 34.9795 32.2316 31.3782 28.6078 27.9092 25.9632 25.5589 33.6296 33.358 30.5743 24.7557 24.5278 24.5074 23.0178 22.8884 22.6923 38.7424 22.6802
threshold=1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 -0.55092222074356589 -0.92257102786474277 -0.41666666666666657 0.72377830750893934 -0.3376378893188533 0.31785522338584254 162010.71000000005 -0.62456902722522767 1.0000000180025095e-35 1.0896901072705605 0.0069293103448275703 2.6250000000000004 -0.31170168932838888 -0.16577837173759505 -0.13637983244433508 0.29166666666666669 1.2777777777777779 -0.58588632668844787 0.370986856692119 10.750000000000002 0.43992884186994752 -0.17154941842383528 0.51063775510204101 0.34600199836031981
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 4 -3 6 -1 10 13 -2 19 12 -5 -8 15 20 23 16 -7 -18 -17 21 -4 -9 -10 24 -12 -26 -27
right_child=7 2 3 5 -6 9 11 8 22 -11 14 -13 -14 -15 -16 18 17 -19 -20 -21 -22 -23 -24 -25 25 26 -28
leaf_value=6.2557323363374669e-05 0.0056117772942366395 0.0050474504556397692 0.0061492315258581355 0.0068717676831188054 -0.0063485995917433556 -0.0087318930489284925 0.0023737161673509648 -0.0017032407965669033 -0.0060576388431815165 0.0043536206321566663 -0.00038948747597554088 0.0070710806592726438 0.0017140663348994469 -0.00091869752119931104 0.009964133034011096 -0.0021645040380428491 0.015380122449011165 -0.0030285439590166043 0.0019158762393985363 0.0014719383786891661 0.0013252866204029727 -0.0057369531498544001 0.064261011908882462 -0.0017077218735983772 0.0051740397598415352 -0.0022448655675462881 0.014903024001447916
leaf_weight=589.24869374930859 130.52246795594692 1061.749365594238 297.23063093051314 214.1018471121788 576.39226987585425 263.05493778176606 867.24948614835739 1761.0606833156198 619.30394900590181 234.7591347862035 866.80019153095782 545.86164594441652 503.38779665715992 1138.354758143425 68.779680730774999 1768.0201948489994 23.094458945095539 1087.4037487506866 562.31773970648646 430.50446824915707 1470.872041888535 442.84311916865408 0.86632575839757819 787.563187494874 645.75736767239869 311.58189114369452 18.792164228856564
leaf_count=7537 1148 9662 2346 2253 12240 5996 6926 24385 17561 3138 10877 4357 7924 11204 876 30025 446 24408 9040 6049 13438 10746 23 11237 7135 4741 282
internal_value=0 0.000556709 0.000892159 0.000513403 -0.00310035 -0.000362714 0.00200733 -0.00231857 -0.00263975 -0.00136856 0.00116775 0.00419546 -0.00169022 0.000940109 0.000711449 -0.00215543 -0.00381022 -0.00263476 -0.00117589 -0.00186274 0.00214201 -0.00251836 -0.00592396 0.000465297 0.00139898 0.00299626 -0.00123333
internal_weight=0 13902.4 12736.7 11675 1165.64 7355.41 4319.57 3385.1 3254.58 4442.04 2913.38 1413.11 4207.28 2906.46 2699.27 3703.89 1373.55 1110.5 2330.34 2634.41 1768.1 2203.9 620.17 2630.49 1842.93 976.131 330.374
internal_count=246000 186088 166311 156649 19777 118378 38271 59912 58764 80977 37401 11283 77839 26988 35148 69915 30850 24854 39065 41180 15784 35131 17584 34272 23035 12158 5023
is_linear=0
shrinkage=0.0152673


Tree=180
num_leaves=28
num_cat=0
split_feature=19 67 155 390 391 391 143 391 171 130 125 19 141 19 1 137 13 392 141 140 140 129 12 75 19 391 29
split_gain=94.6643 86.0926 80.388 71.2263 52.1632 64.1714 51.2639 47.6201 44.6707 38.3304 47.6694 28.5155 27.1789 30.4935 26.8235 25.5428 25.4505 23.7309 23.6201 22.5877 21.995 24.8842 22.1433 21.5018 22.9877 20.8712 20.5978
threshold=0.19388630579008007 1.0000000180025095e-35 35028.247500000005 -0.42634925740084223 0.12742144408804593 1.0000000180025095e-35 3.1666666666666674 0.049180694651566131 3.2500000000000004 0.20833333333333334 -0.188129383282061 -0.25297406411107237 -0.2407407407407407 -1.0000000180025095e-35 1.0000000180025095e-35 -0.92857142857142849 0.17589450208474744 0.52572309678287887 1.0000000180025095e-35 0.52722772277227736 6.1460396039603973 2.7406761751257549 -0.96740321402483553 1.0000000180025095e-35 -0.39580668621267479 0.059577442725710486 -0.15459999999999996
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 6 5 9 16 26 17 10 12 -12 13 -5 -13 -6 19 -4 -3 -1 21 22 -11 24 -17 -9 -7
right_child=-2 18 8 4 15 7 -8 25 -10 20 11 14 -14 -15 -16 23 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0033391608804959811 -0.0047465161741555286 0.0046741292110457659 0.0061426972428510135 -0.00050311787527012935 0.0017431709862525157 0.037820753078334976 0.0035422041306614285 -0.0048911241105503971 6.6673011643622688e-05 -0.0047262083403779194 0.0021931383401310686 -0.0047501023540127731 -0.00072660827920675028 0.0052978802888069051 -0.00077961888326277373 0.011798526819207683 -0.001438376652773205 0.001081312530554454 0.001400867848612896 -0.0073732206711746252 -0.0027880615636465943 -0.0017580606164993467 0.0051631686590168646 -0.0051265250293334791 -0.0016471073479702248 0.0027508764818679966 0.0077245228319454485
leaf_weight=1287.3662717137486 928.98561406508088 1118.2733780648559 795.51759579405189 338.681601440534 476.86712168157101 5.3494518492370835 287.9606299251318 96.00230853818357 839.39456237107515 55.497563978657126 280.38429047167301 936.14886656589806 859.46242719702423 549.18472099304199 698.93631520494819 29.68632984533906 1162.1700750999153 302.90882952511311 969.67115761525929 441.15088539011776 153.62298560515046 178.22911014035344 777.23208550363779 451.91724280640483 2235.9288927931339 593.39410494454205 433.13996002264321
leaf_count=22681 23005 12777 7650 3243 6869 44 3911 1192 10238 818 2587 15424 11095 6440 9143 240 17677 2417 13028 8182 1877 2272 8684 7555 36842 6408 3701
internal_value=0 0.000263078 -0.000160104 -0.000615091 6.79363e-05 0.000913164 -0.00258393 0.00419184 0.00272954 0.000145084 -0.000620031 -0.00228508 0.00120005 0.00307513 -0.00305878 -0.0015049 -0.00319757 0.00475573 0.00315865 -0.00437476 0.00255905 0.00338104 0.00449211 -0.00207832 -0.00146586 0.00167229 0.00812965
internal_weight=0 16354.1 14266.1 12328.3 9149.67 5955.27 3178.65 1127.89 1937.82 4827.38 3662.8 1915.47 1747.33 887.866 1635.09 3194.4 2890.69 1098.43 2087.94 1728.52 1164.58 1010.96 832.73 2717.53 2265.62 689.396 438.489
internal_count=246000 222995 197190 176885 124434 72928 52451 11345 20305 61583 47932 27154 20778 9683 24567 51506 48540 10067 25805 30863 13651 11774 9502 44637 37082 7600 3745
is_linear=0
shrinkage=0.0152673


Tree=181
num_leaves=28
num_cat=0
split_feature=14 391 391 149 391 19 143 10 152 414 391 10 387 13 67 19 10 389 70 18 119 391 387 389 480 155 451
split_gain=94.1115 82.805 99.3544 69.505 67.3427 62.954 55.4625 59.0262 45.2244 35.962 33.2703 31.9399 29.9856 29.1756 28.9516 32.2385 35.1584 27.4245 26.7752 26.1365 24.5791 24.8229 23.2878 23.0539 22.924 22.7012 22.268
threshold=-1.0000000180025095e-35 -0.80185022711144738 -0.63378138164839226 -0.58342319933459807 -0.92257102786474277 0.023652303677922096 2.6111111111111112 -0.32941903584672433 0.81250000000000011 -1.0000000180025095e-35 -0.65476695674678731 -0.0069358604587281955 0.27862778654634074 -0.040531368176088427 1.0000000180025095e-35 -1.0000000180025095e-35 0.16776541683834642 0.0761002880763091 -0.24671814671814671 -1.1249999999999998 -1.0000000180025095e-35 -0.18246996685449549 0.41313238142155323 -0.23780013799738434 1.0000000180025095e-35 240507.60750000001 1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=12 4 10 8 23 6 7 20 17 -9 -3 -12 -1 -8 15 -11 22 18 -4 -18 21 -5 -17 -2 -7 -16 -15
right_child=1 2 3 5 -6 24 13 9 -10 14 11 -13 -14 26 25 16 19 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0015984666530321071 0.0043155827159724863 0.0013818968074482021 0.0025877347989762957 -0.0090424193988980477 -0.0067651644529985516 -0.0030680343155884363 0.0012110786867776714 -0.0012842231479953798 -5.2718400760920542e-05 -0.00071211229376543937 0.012734471440544142 0.0052342027001217534 -0.005243444387877735 0.0062166505662679923 0.0039219725820100245 0.0014694156584827967 0.010039578287610084 0.0021701266103368116 0.0091493411768082192 0.0029505261981044315 -0.00077510635322777896 -0.0027331808024381754 -0.0035116585264672769 -0.001850950000125318 0.043349848573160904 0.019255539747004783 0.029967923609182556
leaf_weight=1573.837763203308 215.57741476036608 365.12091503478587 220.70270944200456 184.66369952261448 641.32516544312239 1476.0660052914172 445.12342919036746 1460.7174582835287 635.79553156904876 1581.5267383102328 177.27994108758867 560.60249391198158 799.06737585552037 443.31962063908577 600.88368551060557 701.78904682211578 135.29366852901876 473.66975773870945 449.73176448792219 1288.2472139559686 1363.8441430237144 724.33881262876093 317.51233059726655 408.19796999916434 2.2594645693898192 23.579335913062096 9.4407852068543416
leaf_count=23741 2734 3778 3169 3851 14033 30968 5525 20388 8838 16581 1822 4723 14894 4736 6079 8808 1263 5720 4530 13576 20812 14432 5126 5538 49 192 94
internal_value=0 0.000443325 0.000790404 0.000403126 -0.0032915 -5.84046e-05 0.000406868 1.94461e-05 0.00319769 0.000801945 0.00518365 0.00705155 -0.0028301 0.00401272 0.00145944 0.000981806 0.00208219 0.00501169 0.00700438 0.00363202 -0.00207981 -0.00402668 -7.35881e-05 0.00026623 -0.00298504 0.0045216 0.00674514
internal_weight=0 14906.6 13641.5 12538.5 1265.1 10758.6 9280.28 8382.4 1779.9 6109.55 1103 737.882 2372.91 897.884 4648.83 4024.37 2442.84 1144.1 670.434 1423.54 2272.85 909.003 1019.3 623.775 1478.33 624.463 452.76
internal_count=246000 207365 185060 174737 22305 152480 121463 111108 22257 72013 10323 6545 38635 10355 51625 45354 28773 13419 7699 14839 39095 18283 13934 8272 31017 6271 4830
is_linear=0
shrinkage=0.0152673


Tree=182
num_leaves=28
num_cat=0
split_feature=21 14 1 391 128 10 8 7 130 142 64 150 143 10 391 129 70 67 387 391 391 143 109 137 70 168 172
split_gain=93.2265 84.6982 81.9622 66.9502 62.4434 55.0223 43.9615 50.8438 41.5335 35.465 34.8577 34.2519 31.0021 30.5194 27.5806 26.9842 25.925 25.2615 24.877 24.79 24.6248 24.5994 22.13 21.7265 21.7099 23.2266 24.7962
threshold=0.77609554057632191 -1.0000000180025095e-35 1.0000000180025095e-35 -0.84913404291403738 1.0677241379310347 0.72043675319324285 0.51063775510204101 -0.55072463768115931 0.29166666666666669 0.34375000000000006 1.0000000180025095e-35 0.59034443817052529 2.7222222222222228 -0.089891498420546612 -0.64052006669616957 -0.56140162932591864 -0.44517374517374514 1.0000000180025095e-35 0.29019879267634097 -0.16577837173759505 -0.92257102786474277 -1.3888888888888886 2.4166666666666674 -0.78571428571428559 0.58494208494208511 2.2500000000000004 6.7500000000000009
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 18 3 20 8 6 7 -4 10 15 11 13 14 19 -11 -10 -9 23 -1 -5 -3 -7 -16 -15 25 -2 -27
right_child=24 2 5 4 -6 21 -8 16 9 12 -12 -13 -14 17 22 -17 -18 -19 -20 -21 -22 -23 -24 -25 -26 26 -28
leaf_value=-0.0013258748309873984 -0.0049010662094604845 -0.0018654021121263498 0.00028053300786230181 -0.0059353707306846713 -0.003230337459792921 0.033264909736333489 3.5699022220307813e-05 0.0023600310960673757 0.027520374346088061 0.0085505594065089004 -0.0025916435642276037 0.0054208526931678637 0.0041087415848573144 0.0035253384334509581 -0.001151094850150119 0.0051102326558553676 0.0059925848151790887 0.0052694617673423594 -0.0048300373493505942 -0.00062098371766737168 -0.0083946300937206442 -0.00087384765095898135 0.014099758430642829 -0.0003232276887825999 0.00044789676663105652 -0.0014418519525778118 0.028330996024657593
leaf_weight=1459.457864113152 1168.699946641922 263.24764078296721 669.87292429991066 265.79189477860928 1057.4267319645733 4.7312690727412692 824.1279007345438 629.31427066028118 12.823385523632167 78.387103889137506 1009.9861923828721 315.07627640105784 600.45534556359053 442.30991964414716 1042.8992341067642 587.41725736483932 1784.179351631552 307.82985488139093 706.17467118613422 909.31453089788556 285.38528079167008 1073.7677551899105 22.392341800034046 1490.6904017366469 237.26466230303049 16.939064834266905 9.8752120360732061
leaf_count=20754 30068 3774 8305 4487 16895 43 11738 7797 151 782 15921 3174 6946 4710 14695 7063 17370 3291 12329 15662 6480 9356 298 18385 5024 329 173
internal_value=0 0.000331126 0.000775835 -0.000118323 0.000228466 0.00233628 0.00317927 0.00401646 0.00074603 0.00240832 -7.40907e-05 0.000605059 0.00129958 0.000157891 -0.000167741 0.00561326 0.00504947 0.00120536 -0.00247309 -0.00183162 -0.00528026 -0.000709452 -0.000819339 0.000552938 -0.0037353 -0.00457311 0.00931242
internal_weight=0 15843.1 13677.4 8691.43 8142.8 4985.99 3907.49 3083.37 7085.37 2344.37 4741 3731.01 1744.13 3415.94 1143.68 600.241 2413.49 2240.83 2165.63 1175.11 548.633 1078.5 1065.29 1933 1432.78 1195.51 26.8143
internal_count=246000 210406 177323 122714 112460 54609 45210 33472 95565 29935 65630 49709 22721 46535 15775 7214 25167 26386 33083 20149 10254 9399 14993 23095 35594 30570 502
is_linear=0
shrinkage=0.0152673


Tree=183
num_leaves=28
num_cat=0
split_feature=20 11 90 1 128 10 416 21 69 61 10 143 141 17 22 19 140 109 45 20 2 21 119 21 389 209 19
split_gain=92.6641 78.4546 70.7221 68.3975 56.1289 40.8357 49.6889 37.7352 37.6851 33.1398 30.8361 30.6521 29.5079 27.7873 26.6195 25.1313 23.9776 23.4228 23.3605 23.2305 22.0925 26.3397 21.7477 21.1584 23.8368 20.3799 27.4414
threshold=0.51688161336547822 -1.6047854785478546 -1.0000000180025095e-35 1.0000000180025095e-35 0.19387931034482761 0.80641395412718042 -1.0000000180025095e-35 -1.5586313096075675 1.0000000180025095e-35 0.0022499999999999955 0.088930092020326895 2.5000000000000004 0.055555555555555559 1.0000000180025095e-35 -0.044199999999999996 1.0000000180025095e-35 -0.15099009900990096 -1.0000000180025095e-35 0.13355000000000003 -1.7685268741381348 1.0000000180025095e-35 -0.69283274727985822 0.75417163289630518 0.77609554057632191 0.051834893618320547 -270.41625549003214 -0.31528071226839544
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 -1 8 4 7 6 12 -4 23 13 -6 20 17 -9 -14 -12 22 25 -19 -15 -8 -22 -2 24 -3 26 -5
right_child=16 2 3 5 10 -7 11 9 -10 -11 15 -13 14 19 -16 -17 -18 18 -20 -21 21 -23 -24 -25 -26 -27 -28
leaf_value=-0.0032305810350221498 -0.003181164416446525 0.00037630116906186249 0.004706154671094147 0.015156337202679056 -0.003743497396341426 -0.00096643134342992861 0.0032859067174775647 0.00064342551692672331 0.0035912719541231252 -0.0022146490629536743 0.00083381918632567426 0.0078234162541423406 0.013643013587295699 0.011119488319581773 0.0013803871042053636 -0.0050993554922630522 -0.0056795605295017508 0.0029789935334621916 0.030245576657768516 0.0029688892634404927 0.0034128223008010167 -0.0013676768889407458 0.0039230668988573499 -0.0054909459669415343 -0.0023455483421012096 0.011318570356886664 -0.0030731026661313231
leaf_weight=1333.2327846121043 415.62666408531368 1232.7676831781864 645.86224089935422 28.505024969577789 958.09380811080337 573.40610282309353 1037.3984754271805 2447.8070986550301 351.72501597553492 727.94397361204028 1053.1444090474397 205.92711518518627 46.681540951132774 96.561139512807131 369.8839058931917 197.35146946646273 757.93587673455477 227.79096197150648 7.4736802875995627 569.27389870584011 404.69193763285875 796.51332618668675 131.3162343390286 305.51067867130041 1894.2039843071252 399.08320849388838 56.780807608738542
leaf_count=22963 10565 17393 4161 193 16753 4597 10937 34229 4672 11408 11932 2120 495 645 4041 3657 20348 2160 69 6835 3377 11814 2567 7574 26559 3375 561
internal_value=0 0.000313572 0.00063712 0.00126431 0.000307985 0.00280351 0.00340979 0.00128975 -0.00115872 0.000712774 -0.00168258 0.0021775 0.00605215 0.00140022 0.00278244 -9.58874e-05 -0.00391758 0.00793082 0.00390903 0.00416765 0.0016534 0.000235572 -0.00145795 -0.0016483 -0.00126961 0.00986293 0.00293376
internal_weight=0 15967.6 14634.4 10850.2 6696.04 4154.14 3580.73 4487.45 3784.21 3841.59 2208.59 2444.53 1136.2 3113.64 416.565 1250.5 1304.88 719.634 235.265 665.835 2238.6 1201.21 546.943 3432.48 3126.97 484.369 85.2858
internal_count=246000 212520 189557 133359 89620 43739 39142 57278 56198 53117 32342 28248 10894 41709 4536 15589 33480 6358 2229 7480 26128 15191 13132 51526 43952 4129 754
is_linear=0
shrinkage=0.0152673


Tree=184
num_leaves=28
num_cat=0
split_feature=411 7 8 6 7 391 391 135 6 8 6 6 7 11 10 19 131 0 10 140 9 1 119 513 130 19 10
split_gain=90.1867 70.3087 92.2168 80.1602 49.9121 40.6749 50.7535 36.4372 35.3469 52.4589 41.8678 36.9056 36.1807 35.1075 30.6097 40.7361 29.0965 26.6835 26.0544 28.8572 23.6203 22.0882 25.4914 21.0426 23.2784 25.5343 20.1482
threshold=1.0000000180025095e-35 -0.46140449088760332 1.0000000180025095e-35 -0.017790309106098575 0.0055980593394289986 -0.80185022711144738 -0.92257102786474277 0.50455650060753354 0.050467836257309946 0.51063775510204101 0.40024227234753557 0.55931495405179621 0.057349007899483738 -0.78685368536853673 0.79185551435242429 -0.31528071226839544 0.50355756791720585 1.0000000180025095e-35 0.015725861832165917 1.0000000180025095e-35 1.1875435493380504 1.0000000180025095e-35 0.70828367103694878 1.0000000180025095e-35 2.2916666666666674 0.21086062242541623 0.95968960307650064
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 7 3 5 -5 6 -3 18 -4 10 -10 -11 -12 -2 15 -15 21 -17 19 -1 26 22 -7 24 25 -13 -6
right_child=13 2 8 4 20 16 -8 -9 9 11 12 23 -14 14 -16 17 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.0017556395942240146 -0.0054785647261612353 0.0019963383817863524 -0.003501623487548081 -0.0016154286076450108 0.0088423389477270548 -0.00067220266107710907 -0.0064753109052755062 0.0013740076175181898 0.00037113644871358516 -0.005573687573073703 -0.00208681594329257 0.00019554932898058067 0.0060720842286606383 0.0088420318934713527 -0.0053342109260174596 -0.00065700150473689978 0.0056748754835992347 -0.0061502308768386785 -0.00090724979428708755 -0.006694741936953877 -0.0022399223786430051 0.0033282242920147096 0.0045316787047088797 -0.0032430231848716781 0.0054557419154683756 -0.0082778921093721227 -0.0018780286391507069
leaf_weight=625.24750318937004 637.42654960975051 371.18566714972258 646.43380666151643 153.3488253634423 835.85896819829941 1063.1247418951243 294.77343643456697 881.66423059254885 1420.4941210839897 377.96992023102939 151.90663319453597 1557.3343542199582 716.49698920920491 97.320713870227337 410.70214971527457 1991.5902280043811 530.43333954922855 230.64872057922184 1551.7639948483557 502.93847353197634 50.756855733692646 1091.8055954910815 275.83555117435753 487.51325861737132 185.06871555745602 87.283223520964384 41.431589998304844
leaf_count=11259 13961 4517 9648 2049 7037 13115 6322 10136 19725 6087 2387 24129 9266 885 5250 34987 4853 4829 18912 9551 598 10325 2676 8476 2538 2227 255
internal_value=0 0.000537037 0.00117478 0.00275156 0.00640245 0.00166027 -0.00174053 -0.00131167 -0.000142231 0.000291767 0.00199279 -0.00114949 0.00463418 -0.00224756 -0.00148953 -0.000804437 0.00242825 -0.00123177 -0.00219868 -0.00396638 0.00773724 0.0017156 0.000393511 -0.000423461 0.000323067 -0.000249536 0.0083253
internal_weight=0 13900.7 10339.1 4708.55 1081.4 3627.16 665.959 3561.61 5630.5 4984.07 2288.9 2695.17 868.404 3367.69 2730.26 2319.56 2961.2 2222.24 2679.95 1128.19 928.047 2430.77 1338.96 2317.2 1829.69 1644.62 877.291
internal_count=246000 186088 136230 51747 9939 41808 10839 49858 84483 74835 31378 43457 11653 59912 45951 40701 30969 39816 39722 20810 7890 26116 15791 37370 28894 26356 7292
is_linear=0
shrinkage=0.0152673


Tree=185
num_leaves=28
num_cat=0
split_feature=20 21 149 143 414 1 10 154 148 20 19 248 21 8 389 69 124 90 387 143 7 19 151 124 390 139 165
split_gain=90.1679 82.5215 62.2405 63.7989 52.4102 39.9091 53.5685 39.4708 29.6406 29.2539 26.4376 26.3622 24.4953 24.2889 31.0144 27.6901 23.2271 23.0231 22.9338 22.909 22.4159 22.2606 22.062 23.2064 21.0377 20.9452 23.1549
threshold=-1.055547744992388 0.64988196944952348 -0.58342319933459807 2.5000000000000004 -1.0000000180025095e-35 1.0000000180025095e-35 -0.16446916632330721 1.642857142857143 -0.55219563435130126 -2.0580407920971773 -0.44856919509688314 0.63888888888888895 -1.0130370759385332 0.51063775510204101 -0.39869714423440467 1.0000000180025095e-35 1.8750000000000002 -1.0000000180025095e-35 1.4677332951356872 2.7222222222222228 0.89257946134229038 0.023652303677922096 -0.40783540022547909 1.0000000180025095e-35 0.70381212032294349 0.51458020144747574 170434.05750000002
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=9 2 7 4 10 6 -6 8 -2 -1 -4 17 -12 14 -7 -16 25 -11 19 -19 -18 -8 -10 -24 -3 26 -5
right_child=1 24 3 16 5 13 21 -9 22 11 12 -13 -14 -15 15 -17 20 18 -20 -21 -22 -23 23 -25 -26 -27 -28
leaf_value=0.008152831045380577 0.003711015561416882 -0.0045297191198232223 0.024638990651356142 0.00227777091389594 -0.0035726451160139616 0.0059588539696346565 0.00071761445850692242 -0.00048181026441279125 0.0041367710302244835 0.0001030757152845114 -0.0007810665610505686 -0.00045100537266271984 -0.0041385895863196628 -0.0017749830773367452 0.00034805663227468868 0.0070150740928375654 0.0064890774098577218 0.0031032417730054288 -0.0018518140393535814 0.009412923635231104 0.025938086987751893 -0.0036660559124461686 0.034539308515990651 0.01070875033219312 0.0031170803087094807 -0.0031129388445561542 0.011976786562801631
leaf_weight=166.72492926195264 898.11244692280889 1377.540846535936 7.7637758851051322 663.27795475535095 1521.5703513678163 357.70571874640882 1983.9416141025722 593.13923798315227 33.769224900752306 824.83395799249411 740.82399800792336 1066.4568843394518 1653.259547919035 534.97299764491618 1512.6815387029201 160.92873854003847 113.94388529658318 2038.0028060022742 199.30759598687291 145.3075345531106 16.134609043598175 312.1943649277091 17.768522933125496 24.244145683944225 87.717116646468639 149.23388096317649 63.361225506290793
leaf_count=974 11251 38099 60 8566 29168 3922 24492 8700 456 8088 7772 9111 35054 8196 18326 1741 1323 15969 1963 1050 195 6057 197 262 2113 2239 656
internal_value=0 -0.000655338 -0.000214588 -0.000667451 -0.00108523 -0.000360288 -0.00135104 0.00260906 0.00450063 0.00186886 -0.00300808 0.00162121 -0.00310362 0.00111002 0.00187443 0.000995369 0.00297175 0.00231304 0.00307419 0.00352819 0.00900791 0.000117332 0.0137037 0.0211204 -0.00406533 0.00206299 0.00313917
internal_weight=0 12824.1 11358.8 9791.79 8785.84 6384 3817.71 1567.03 973.894 4440.63 2401.85 4273.91 2394.08 2566.29 2031.32 1673.61 1005.95 3207.45 2382.62 2183.31 130.078 2296.14 75.7819 42.0127 1465.26 875.873 726.639
internal_count=246000 208845 168633 147767 134788 91902 59717 20866 12166 37155 42886 36181 42826 32185 23989 20067 12979 27070 18982 17019 1518 30549 915 459 40212 11461 9222
is_linear=0
shrinkage=0.0152673


Tree=186
num_leaves=28
num_cat=0
split_feature=19 67 21 164 389 8 7 152 135 111 137 6 414 171 6 8 6 13 135 11 21 129 151 6 112 70 390
split_gain=87.6175 79.9264 75.8858 68.326 60.5494 49.2426 56.2577 43.4702 32.7072 31.6609 34.3537 30.4649 29.9737 28.0161 26.2934 36.1524 29.1385 24.9373 24.4193 23.7101 23.0782 21.8466 21.4046 21.2709 23.4967 21.063 20.6741
threshold=0.19388630579008007 1.0000000180025095e-35 -1.3471229168525309 39122.122500000005 0.051834893618320547 0.51063775510204101 0.085712508552590674 2.9375000000000004 0.54586877278250312 11094.075000000003 -1.0714285714285712 0.55931495405179621 -1.0000000180025095e-35 -2.2499999999999996 0.50927318295739366 1.0000000180025095e-35 0.10365497076023393 0.87792107049355195 0.457168894289186 -1.8655115511551152 -2.0089485232886477 -0.74775638996693616 0.6846110484780159 -0.017790309106098575 -0.54164243887810337 0.32007722007722011 -0.58583939660879392
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 20 4 5 6 9 8 -5 10 -4 -7 -6 -8 15 23 -17 21 19 -14 -1 -12 26 -15 -25 -19 -21
right_child=-2 -3 3 7 12 11 13 -9 -10 -11 17 -13 18 14 -16 16 -18 25 -20 22 -22 -23 -24 24 -26 -27 -28
leaf_value=0.0051783081150863193 -0.0045964469575469095 0.0030349952398157688 0.0031392036940836184 0.0012680949520765031 -0.0044246360767966324 -0.007790599162812579 -0.0028606980630430873 -0.0019359622344320149 0.0065487379987928234 0.012538015580929412 0.012378912658878825 -0.0014584908171457168 -0.0076347275365702483 0.0027972027194244687 0.0097881736284753818 -0.0048279720025390868 0.0021937600930336549 -0.0013600182069652088 0.00066810586086944615 -0.0036089805235419597 0.0015201941438395992 -0.0030014152269832264 0.052374941173187251 0.017469635671743713 0.0061653160471692127 0.0075241956472998474 -0.00072175707652604327
leaf_weight=513.01939785853028 917.44032190181315 2096.5875346716493 368.15071922540665 547.77725227549672 1256.9278611503541 201.24743875302374 180.06920155324042 397.63548531569541 556.25622002035379 40.293872563168406 21.44073323532939 1538.7375965397805 186.64459120854735 461.68806864880025 140.72505073435605 188.41118846088648 509.19749036431313 143.17721090838313 799.44143802858889 1045.5668623317033 1925.0545837953687 1432.0696616824716 1.4764516837894905 50.96620774641633 317.24448296241462 107.95633404701948 1315.1245078649372
leaf_count=3161 23005 25805 4756 6503 23826 3701 2675 5607 5146 544 269 28209 3858 5895 1912 3123 7472 2026 10796 18972 14295 22181 20 461 2981 1168 17633
internal_value=0 0.000251776 -0.000157217 -0.000664143 -0.00110805 -5.46883e-05 0.000884017 0.00237623 0.00393769 -0.000814196 -0.00107936 -0.00219694 -0.0024101 0.00283035 0.0034504 0.00285932 0.000283353 -0.00199607 -0.0016509 -0.00238185 0.00229405 -0.00276657 -0.00196231 0.00501304 0.00776351 0.0024256 -0.00200461
internal_weight=0 16342.9 14246.3 11808.2 10306.6 5701.38 3961.39 1501.67 1104.03 2113.09 2072.79 1739.99 4605.18 1848.3 1668.23 1527.51 697.609 1704.64 3348.25 2548.81 2438.07 1453.51 2362.17 829.899 368.211 251.134 2360.69
internal_count=246000 222995 197190 179734 162478 87373 55463 17256 11649 30944 30400 31910 75105 24519 21844 19932 10595 25644 51279 40483 17456 22450 36625 9337 3442 3194 36605
is_linear=0
shrinkage=0.0152673


Tree=187
num_leaves=28
num_cat=0
split_feature=20 130 141 111 414 69 416 165 0 7 162 391 391 10 12 128 21 124 109 10 140 430 119 112 391 261 387
split_gain=88.0574 79.0985 80.1751 59.8109 44.8453 41.7472 42.9075 40.1748 34.8853 34.7523 33.7188 32.3141 42.7371 27.9173 26.69 26.5658 26.3898 25.4621 24.7268 25.3758 23.3308 22.1232 20.9574 20.8816 20.8498 20.1189 20.1041
threshold=0.51688161336547822 1.0000000180025095e-35 0.055555555555555559 3790.8787500000003 -1.0000000180025095e-35 1.0000000180025095e-35 -1.0000000180025095e-35 103718.70000000003 1.0000000180025095e-35 0.069042731852957659 899.19000000000017 0.12650512597654215 -0.81178185562575544 0.32007965938744681 0.71375091307523753 1.3517068965517243 -0.80033360143826193 0.87500000000000011 -0.41666666666666657 0.79185551435242429 -0.15099009900990096 1.0000000180025095e-35 0.77145411203814074 -0.56673863977145367 -0.80185022711144738 15.875000000000002 -0.24877276285889841
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 4 26 6 9 16 11 18 -9 12 -3 24 -11 21 -4 -13 19 -6 22 -14 -2 -5 -8 -20 -1
right_child=20 8 7 23 5 -7 13 10 -10 14 -12 17 15 -15 -16 -17 -18 -19 25 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.00013705627198650156 -0.0030912331670914549 -0.0026598806966611041 -0.00056791518442532636 0.012738192251157318 0.005517516343774528 0.0051885819038511548 -0.0079795307640596995 0.019281704719602041 -0.0026247847860583788 0.0041508538376240625 0.0010958260105623486 -0.00059751694389006949 0.0042127577097214909 0.0011172943453500561 0.015102846765254137 -0.00057066940652461182 -0.003422998898377297 0.0032787794413119144 -0.0014100945393273126 -0.0021719527329767318 -0.0055813787052841754 0.010505638100733 0.0039141101442791513 0.0040557444007188713 -0.0015742482749431623 0.035363219031168951 -0.0035196079542698139
leaf_weight=754.7250776514411 415.08022193983197 240.23328972794116 1068.7311684675515 74.616442501544952 348.64537814632058 479.53444290906191 130.29231107793748 24.985466483980417 352.60760487616062 556.79010518267751 460.65498027019203 1134.7186835035682 1935.4687020238489 1032.9799369368702 58.0133754350245 251.77057797648013 2636.9143301974982 603.51895373128355 662.22002533264458 138.10957558266819 751.12013208866119 142.01000782102346 129.82606094516814 550.97765903547406 1407.603493899107 3.2697500847280017 910.75650610029697
leaf_count=10053 10602 3802 9951 787 3873 5148 2470 260 5175 6351 5153 16860 20278 10092 624 2985 47355 8173 8401 1159 20348 1292 2530 6439 20108 24 15707
internal_value=0 0.000304891 -0.000384675 0.00060181 0.000165248 0.000913167 0.000438213 -0.00205992 0.00197878 0.00227094 0.00205787 0.00235783 0.00344635 -0.000817998 0.00520376 0.00408024 -0.00260212 0.000743293 0.000697495 0.00331693 -0.00383281 0.0046483 -0.00140455 0.0051097 -0.00212383 -0.00120509 -0.00199248
internal_weight=0 15960.1 11299.8 7108.53 6482.94 4817.46 4337.92 4191.29 4660.33 1767.05 485.64 4307.72 2569.48 2570.88 614.803 2329.25 3705.65 1738.24 1152.24 486.755 1296.03 2077.48 544.906 625.594 1537.9 665.49 1665.48
internal_count=246000 212520 153955 91236 84010 58250 53102 62719 58565 20432 5413 53390 28357 32670 6975 24555 57306 25033 13457 5032 33480 21570 13132 7226 22578 8425 25760
is_linear=0
shrinkage=0.0152673


Tree=188
num_leaves=28
num_cat=0
split_feature=14 1 21 13 17 416 17 149 7 389 166 138 143 21 12 145 57 135 149 111 126 151 303 111 143 7 388
split_gain=87.1293 89.1533 59.4723 44.0787 41.0639 36.482 32.8515 32.2089 37.5072 26.3104 26.0848 27.3486 25.5545 25.1109 24.6382 24.1846 23.5252 24.9312 23.1826 22.7367 21.4304 21.2335 19.8191 19.5496 19.4162 21.0886 19.0151
threshold=-1.0000000180025095e-35 1.0000000180025095e-35 -0.61445131617886728 1.100940560457675 1.0000000180025095e-35 -1.0000000180025095e-35 -1.0000000180025095e-35 -0.21135171585026369 0.12676494370840333 -0.056221408997843399 176182.59375000003 1.0000000180025095e-35 2.6111111111111112 -0.93408681903246593 -0.54446676406135852 2.2500000000000004 0.031200000000000023 0.457168894289186 2.094030011308686 1226.2050000000002 -0.56816541465632475 0.6158399098083428 -7306003168.5600042 2108.7787500000009 2.1666666666666674 -0.15463083908689432 -0.77607244876232973
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=13 2 16 4 7 9 -7 8 15 -3 11 19 23 -1 -6 -4 17 22 21 -8 -17 -5 -2 -9 25 -16 -14
right_child=1 5 3 18 14 6 10 12 -10 -11 -12 -13 26 -15 24 20 -18 -19 -20 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.00035761391767533623 0.012625663740417785 0.0057247053727653386 -0.0024533192722529214 0.0034064332671748061 -0.0036261832017777437 -0.0042548357838244804 -0.00042865053335943381 -0.0042638035358534415 0.0025672003488180534 0.0021420793392928177 0.0073795205618722584 0.0033438049691099951 0.031680246603275848 -0.0037860526312143423 -0.0013951006954198773 0.041997040133662317 -0.001879308458043112 0.0038505723673569249 -0.011398574269918674 0.0043401844349813022 0.00062628498804576116 0.018986610147155535 0.00055348595993933282 0.00087963789407428819 0.0088106952399932097 0.0038064405000127937 0.00014076853842338966
leaf_weight=725.83738934993744 32.102728027850389 825.38871220871806 1205.9702870734036 370.59735020250082 210.04357717745006 252.93213133513927 1844.8186848796904 2323.393059508875 552.12525249458849 1164.85765658319 164.49981929175556 906.94059115089476 4.3281515333801499 1630.2547528371215 338.75015255995095 5.1321079879999161 508.65761544927955 863.09591715410352 22.73969098366797 266.34747319668531 7.4962213207036239 21.755533613264561 2014.1495953090489 182.83561917953193 92.777680013328791 387.1311297789216 327.80892538279295
leaf_count=6827 298 7885 21258 5732 3747 4191 23038 48879 9994 12442 1518 11220 50 31808 4969 79 5644 6712 419 2961 146 230 19580 3939 1193 5691 5550
internal_value=0 0.000425611 -0.000467576 -0.00137738 -0.00173201 0.00198635 0.00102967 -0.00234816 -0.000725586 0.00363288 0.00145276 0.00112623 -0.00335706 -0.00273387 0.00101967 -0.00222518 0.00114089 0.00167217 0.00341561 0.000169007 0.0185459 0.00430291 0.000748573 -0.00388488 0.00222344 0.00136668 0.000598148
internal_weight=0 14896.7 9470.89 6052.88 5637.79 5425.79 3435.54 4609.09 1770.72 1990.25 3182.61 3018.11 2838.37 2356.09 1028.7 1218.6 3418.01 2909.35 415.093 2111.17 12.6283 392.353 2046.25 2506.23 818.659 725.881 332.137
internal_count=246000 207365 144110 111876 105495 63255 42928 89895 31477 20327 38737 37219 58418 38635 15600 21483 32234 26590 6381 25999 225 5962 19878 52818 11853 10660 5600
is_linear=0
shrinkage=0.0152673


Tree=189
num_leaves=28
num_cat=0
split_feature=20 21 128 7 8 167 0 13 21 392 122 20 19 119 47 109 19 486 53 249 112 449 20 390 414 129 136
split_gain=85.216 78.4648 65.1051 47.7165 95.1391 44.2073 39.6692 35.4507 33.362 30.4657 28.2122 28.1142 28.0966 26.9304 24.4564 24.3423 24.289 22.8572 21.2455 21.0667 20.7928 20.6811 20.3991 20.3924 19.96 19.3195 18.2137
threshold=-1.055547744992388 0.64988196944952348 1.0677241379310347 0.085712508552590674 1.0000000180025095e-35 0.75000000000000011 1.0000000180025095e-35 1.100940560457675 -1.8457901202353957 0.51955975696655743 4.7068965517241388 -2.0580407920971773 1.0000000180025095e-35 0.6641835518474376 0.0085499999999999968 0.41666666666666669 -0.31045995720902853 1.0000000180025095e-35 0.04355000000000004 -262710039.24001595 0.067214356740375972 1.0000000180025095e-35 0.58744417577269659 0.70381212032294349 -1.0000000180025095e-35 -0.018990947648287643 -0.3666067146282973
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=10 2 3 5 9 7 13 8 25 -5 11 -1 22 18 17 -15 -4 21 24 -11 -17 -13 -10 -3 -6 -2 -25
right_child=1 23 16 4 6 -7 -8 -9 12 19 -12 14 -14 15 -16 20 -18 -19 -20 -21 -22 -23 -24 26 -26 -27 -28
leaf_value=0.0086955582592586934 -3.6228825375564789e-05 -0.004437422175309646 0.0043232914368975511 0.0078330880013012926 -0.002380653026059954 0.0057199325827650442 -0.0099683660924766108 0.0041022190423798659 -0.00088209896950681706 -0.0032545409075793218 -0.0019905218853228379 0.0011165246414408037 -0.0045511156505633346 0.0013832876975904222 -0.00099693205980176387 -0.00011264918474887688 -0.0034167229900446783 0.0054538513784064538 -0.004546476559517872 0.0041719154508345659 0.011474773607651766 0.0040866048511484327 -0.006057499139839548 0.011530842917534071 0.0010556909310050681 0.0070212310255018335 -0.0025051032400438982
leaf_weight=150.32091259211302 193.25658191367984 1366.9478925522417 99.225805442780256 552.48196319118142 545.64703147485852 241.02868119813502 88.59431242570281 302.51494611613452 3705.7041507288814 107.13054940104485 409.55119954794645 2076.7918201498687 658.40455383621156 561.50454352982342 557.81195445358753 49.49859700165689 1605.2067033927888 503.0732260402292 259.83594544045627 492.17446024343371 119.23233555816114 748.83365128934383 187.11596030928195 35.566215012222528 1414.1256894078106 165.56765300780535 52.266100043430924
leaf_count=867 1335 38099 886 5816 10330 2474 1933 4045 50993 1169 3743 18183 14123 8093 5113 598 27525 3777 4664 5567 1563 5472 4384 883 21982 1153 1230
internal_value=0 -0.000638164 -0.000209348 0.000275952 0.00150175 -0.000664222 8.21998e-05 -0.00096139 -0.00127539 0.00523794 0.00181508 0.00220352 -0.00163012 0.000387815 0.00194963 0.0029323 -0.0029603 0.00244619 -0.000445367 0.00282845 0.00802517 0.00190712 -0.00113352 -0.00397643 9.41126e-05 0.00319679 0.00308774
internal_weight=0 12803 11348.3 9643.82 4190.23 5453.59 3038.44 5212.56 4910.05 1151.79 4446.38 4036.83 4551.22 2949.84 3886.51 730.235 1704.43 3328.7 2219.61 599.305 168.731 2825.63 3892.82 1454.78 1959.77 358.824 87.8323
internal_count=246000 208845 168633 140222 61715 78507 49163 76033 71988 12552 37155 33412 69500 47230 32545 10254 28411 27432 36976 6736 2161 23655 55377 40212 32312 2488 2113
is_linear=0
shrinkage=0.0152673


Tree=190
num_leaves=28
num_cat=0
split_feature=14 1 19 128 86 10 13 21 8 158 10 387 119 390 10 387 7 13 498 149 112 43 19 6 8 57 90
split_gain=84.3512 85.8885 65.126 53.8427 44.8994 44.8681 46.7243 44.0673 41.2544 32.4011 31.0294 28.0301 27.9834 27.8452 25.8178 25.2193 26.9772 24.8948 22.1335 22.1277 21.7162 21.379 20.9681 20.8103 20.8171 20.5817 20.3785
threshold=-1.0000000180025095e-35 1.0000000180025095e-35 -0.23999248241935275 1.0677241379310347 1.0000000180025095e-35 0.72043675319324285 -0.37525453311354595 -0.34878907985240648 0.51063775510204101 1125.3375000000003 0.68088174701277315 0.27862778654634074 0.72377830750893934 0.2802937305696464 0.41841779975278132 1.172264132231464 -0.55072463768115931 0.62542422185591018 1.0000000180025095e-35 -0.057167895928611136 -0.67605315908265851 0.14580000000000004 -0.3060815920516391 -0.39267335004177101 0.50865306122448983 0.19790000000000005 -1.0000000180025095e-35
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=11 2 14 4 7 6 23 12 15 13 -6 26 20 17 -2 16 -8 -9 25 21 -4 -15 -13 -3 -25 -18 -1
right_child=1 5 3 -5 10 -7 8 9 -10 -11 -12 22 -14 19 -16 -17 18 -19 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=-0.0039312289059138155 0.0094322597250244781 -0.0029103251803339939 0.0054248552888817312 -0.0038670598395550205 0.0059186757844915316 -0.0007841864865163954 0.0018561805767598146 -0.003972668895959864 0.00023357754194570698 0.0032566811565493989 -0.0013357277533276308 0.0056069926672010035 0.003001824511067579 0.002464614449642966 0.0023909291085719639 7.5125488910816286e-06 0.006196875251750519 -0.00010043689584711616 0.022253091745761087 -0.0023935789585854514 -0.00069455084287283874 -0.0056951374720448956 -0.0056323339186628886 0.0034085631259681373 -0.0012485024270110798 -0.0020483342722428955 -0.00024151350880463357
leaf_weight=531.70665298774838 154.86585936695337 360.58778309449553 145.10532655753195 1177.8066843748093 422.40679572150111 1109.1909870058298 467.23839721269906 1833.9847419392318 645.49197041243315 278.03713472560048 200.85313409939408 39.834907855838537 872.04470589011908 621.27497684955597 591.41580387204885 253.8368052393198 1594.4020940456539 496.69885534234345 19.608493743464351 671.59130313247442 1912.4088518284261 84.373791808262467 746.48194458894432 523.74415491893888 386.65866526216269 72.023694237694144 1031.4643151946366
leaf_count=8953 1449 4951 1359 21588 5530 9842 5911 40571 9616 3796 2099 420 8158 9729 5037 3464 16414 9463 196 12392 21408 1531 14474 6057 5879 925 14788
internal_value=0 0.000418315 -0.000459318 -0.000830813 -0.000355145 0.00194863 0.00265184 -0.000709999 0.00367606 -0.00175545 0.00356648 -0.00269417 0.000709335 -0.00213391 0.00386653 0.00459529 0.00513181 -0.00315146 0.00603381 -0.000405062 -0.000258045 0.00147465 -0.00505002 0.00018453 0.00142075 0.00583481 -0.00150276
internal_weight=0 14895.7 9462.87 8716.59 7538.78 5432.78 4323.59 6915.52 3052.6 3985.96 623.26 2349.49 2929.56 3707.92 746.282 2407.11 2153.27 2330.68 1686.03 1377.24 2057.51 705.649 786.317 1270.99 910.403 1666.43 1563.17
internal_count=246000 207365 144110 137624 116036 63255 53413 108407 36526 77482 7629 38635 30925 73686 6486 26910 23446 50034 17535 23652 22767 11260 14894 16887 11936 17339 23741
is_linear=0
shrinkage=0.0152673


Tree=191
num_leaves=28
num_cat=0
split_feature=19 130 126 141 19 111 0 119 414 2 111 109 69 416 147 155 109 55 409 10 19 139 498 10 19 120 154
split_gain=82.7704 76.2643 68.7885 53.7863 42.2607 38.4991 34.5725 36.6886 34.2007 32.5382 31.8785 30.5697 29.9334 30.4719 25.9848 34.1118 27.2194 25.4887 25.1309 25.8694 23.7577 23.7064 21.3672 20.9649 31.9695 20.7551 20.3239
threshold=0.19388630579008007 1.0000000180025095e-35 -0.36265548339813924 0.16666666666666669 -0.31528071226839544 5660.5500000000002 1.0000000180025095e-35 -0.092669845053635264 -1.0000000180025095e-35 1.0000000180025095e-35 12221.156250000002 1.7500000000000002 1.0000000180025095e-35 -1.0000000180025095e-35 -0.067567567567567557 33998.602500000008 -0.24999999999999997 1.0000000180025095e-35 -1.0000000180025095e-35 0.81712676830105768 -0.24312884957925313 0.41630029536861807 1.0000000180025095e-35 0.32007965938744681 -0.29454836982932453 -0.66407678244972568 0.2142857142857143
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 9 5 -3 8 7 -6 -4 10 14 17 13 22 16 -16 -1 18 -9 -20 -5 -11 -10 24 -15 -12 -27
right_child=-2 4 3 20 6 -7 -8 11 12 21 25 -13 -14 23 15 -17 -18 -19 19 -21 -22 -23 -24 -25 -26 26 -28
leaf_value=0.005449183614122605 -0.004488540072178142 0.0079058292457200204 -0.0028424551369799294 0.0011244320056346029 -0.00030885423757380807 0.0044707516736618201 -0.0031689364548115567 0.0013734107324932412 0.0012969425462628235 0.0010607245627869768 -0.0022579024305802316 0.010927096942992954 0.0044832360512794753 0.015013361843649693 -0.0013995891747309178 0.0036556837379999227 0.0011970380364977264 -0.0009237367482507336 0.0051666668030744527 -0.0024761235778369192 -0.0036976267442266255 -0.0030840954954730279 0.030844371690520043 0.00033445221262591118 -0.0034137228476596947 0.024682478448314851 0.0015350970446617563
leaf_weight=689.26505193859339 909.22187591902912 256.62805924937129 1323.5720991715789 264.38513428904116 1220.0866503939033 351.42909606359899 336.4373732060194 1066.7887609731406 1212.9324346389621 689.98148927651346 14.528290953487156 105.39533752016723 321.68944432213902 22.045821405947208 909.7869967687875 472.03574848920107 728.7593837454915 420.10101816430688 1231.3955441173166 110.86664456129074 2162.6188690606505 598.98472258076072 5.5626350529491893 714.58096477948129 1057.1800790093839 32.24411865323782 13.388691699132321
leaf_count=7316 23005 1874 22309 2699 19739 4496 5161 13585 15307 8431 193 1046 3740 209 13105 4794 9341 5756 12804 882 36345 8415 56 7655 17288 306 143
internal_value=0 0.000243866 -0.000423357 -0.00130269 0.00187385 -0.000396722 0.0015268 0.00190939 -0.000766133 0.0011504 0.00205897 0.00283474 5.5527e-05 -0.000414542 0.00181837 0.000320962 0.00327083 0.00252928 0.00313527 0.0045283 -0.00316851 -0.000858454 0.00144439 -0.0016824 -0.00302611 0.0130615 0.0181272
internal_weight=0 16332.7 11585 7436 4747.7 5008.99 4491.07 4154.63 4657.56 4148.97 2860.01 2934.55 3333.99 3012.3 2799.85 1381.82 1418.02 2829.15 2409.05 1342.26 2427 1288.97 1218.5 1793.81 1079.23 60.1611 45.6328
internal_count=246000 222995 162148 110104 60847 71060 58973 53812 66564 52044 35198 34073 44255 40515 34556 17899 16657 33027 27271 13686 39044 16846 15363 25152 17497 642 449
is_linear=0
shrinkage=0.0152673


Tree=192
num_leaves=28
num_cat=0
split_feature=21 14 1 391 128 10 416 19 130 157 86 21 17 390 13 10 13 13 7 387 130 391 387 27 111 10 19
split_gain=81.6365 74.8786 69.1978 63.2038 55.8103 51.7935 66.5528 45.3691 42.259 38.9113 35.9071 34.5547 30.2163 27.7733 27.222 24.455 24.0188 23.8803 23.8146 23.3124 24.5236 23.2803 23.0834 22.5188 20.2218 19.9475 19.4406
threshold=0.77609554057632191 -1.0000000180025095e-35 1.0000000180025095e-35 -0.84913404291403738 1.0677241379310347 0.72043675319324285 -1.0000000180025095e-35 -0.23674106267790407 2.2916666666666674 1.0000000180025095e-35 1.0000000180025095e-35 -1.8457901202353957 -1.0000000180025095e-35 0.27425222522499298 -0.37952099292155528 0.75738222771597319 0.19528750121206248 1.100940560457675 -0.51240903153573414 1.435028161452883 1.1250000000000002 -0.92257102786474277 0.29019879267634097 0.084600000000000022 15435.472500000002 0.68088174701277315 -0.31528071226839544
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 22 3 21 7 6 16 15 9 10 11 -9 -8 17 18 -5 -4 -13 -14 20 24 -3 -1 -15 -16 -12 -24
right_child=-2 2 5 4 -6 -7 12 8 -10 -11 25 13 14 23 19 -17 -18 -19 -20 -21 -22 -23 26 -25 -26 -27 -28
leaf_value=-0.0012375465483566402 -0.0035263054633051759 -0.0018351035890395741 0.0042236300028369771 0.0071828717504758312 -0.0030577238185998234 -0.00080129932128990527 -0.0039805888753275667 0.0038974219196484454 0.003971560773422751 0.0053078095121089066 0.0058157260528595364 -0.0023998875309777625 -0.0063177749027989952 0.00093496294577132325 0.0024744623789344543 0.0010315518881748593 0.0086503070047969019 0.0034429252233912086 0.0008849929348383952 -0.0024725643399577794 0.0077552168227421787 -0.008221383825195645 0.0063857211677288868 -0.0048622469904698318 0.015102106493071714 -0.00062604203738146397 -0.0052265664508848748
leaf_weight=1450.242862727493 1409.453113861382 262.47038830816746 780.69540316611528 367.02643330022693 1044.3987352866679 1081.3673531506211 206.79953841865063 344.6073349416256 668.86746153049171 296.01904443092644 319.87434920296073 2682.3782782014459 129.1011067610234 1626.7427718471736 1266.6312780156732 262.06916604936123 465.07321193814278 172.18491946533322 615.84639427438378 155.7575892098248 284.93093558587134 279.62569577619433 34.541289635002613 172.31722829677165 30.410527560859919 168.62650013901293 660.62015310488641
leaf_count=20754 35594 3774 8213 3067 16895 9399 3367 2282 8034 2899 3998 44881 1769 21258 14354 2119 4618 2497 7514 2151 2891 6480 341 2826 333 1704 11988
internal_value=0 0.000307865 0.000724162 -0.000100818 0.000234914 0.00215125 0.00296491 0.000721942 0.000338726 -8.00077e-05 -0.000372543 -0.000760216 0.00160873 -0.00110724 0.00207828 0.00463605 0.00588468 -0.00204403 -0.000352331 0.00312545 0.00368265 -0.005148 -0.00234291 0.000374126 0.00277988 0.00357399 -0.00463473
internal_weight=0 15829.2 13683.8 8667.21 8125.11 5016.61 3935.25 7080.71 6451.62 5782.75 5486.73 4998.23 2689.48 4653.62 2482.68 629.096 1245.77 2854.56 744.948 1737.73 1581.97 542.096 2145.4 1799.06 1297.04 488.501 695.161
internal_count=246000 210406 177323 122714 112460 54609 45210 95565 90379 82345 79446 73744 32379 71462 29012 5186 12831 47378 9283 19729 17578 10254 33083 24084 14687 5702 12329
is_linear=0
shrinkage=0.0152673


Tree=193
num_leaves=28
num_cat=0
split_feature=20 130 141 111 1 19 416 165 19 149 7 162 27 8 138 125 2 135 145 109 21 316 51 140 2 118 301
split_gain=82.3055 73.276 75.0911 55.7091 40.5813 39.1956 39.1603 37.8786 36.6694 34.6594 34.5455 32.0811 31.2298 34.3917 32.9605 29.9364 28.2031 28.0723 27.5085 24.4861 24.3007 23.5732 23.1614 22.6709 22.3212 21.4848 24.3236
threshold=0.51688161336547822 1.0000000180025095e-35 0.055555555555555559 3790.8787500000003 1.0000000180025095e-35 -0.31936837048240385 -1.0000000180025095e-35 103718.70000000003 -0.0026085327808550436 0.30500127255505449 -0.46140449088760332 899.19000000000017 0.011600000000000001 1.0000000180025095e-35 1.5000000000000002 -0.20743732295039877 1.0000000180025095e-35 0.86482381530984209 1.0000000180025095e-35 -1.0000000180025095e-35 -0.80033360143826193 -57967.999999999993 0.036950000000000004 -0.15099009900990096 1.0000000180025095e-35 -0.82194244604316535 -94505808447.206451
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 4 9 -3 8 18 -6 16 17 -9 13 14 -12 19 22 -7 20 -5 -4 -15 -1 -2 -8 26 -23
right_child=23 5 7 15 6 10 24 11 -10 -11 12 -13 -14 21 -16 -17 -18 -19 -20 -21 -22 25 -24 -25 -26 -27 -28
leaf_value=0.0011784275266395641 -0.0013253931719971533 0.0079399146489382809 -0.00072709185322239651 0.014095399884261381 0.00010243871133700118 -0.0020964513934495031 0.0019906045093227472 0.018666067163057114 0.0058737737337277961 -0.00345870992068601 0.0035398802177126531 0.0010504582477031711 -0.0010404220157753813 0.0065386666765832515 0.0095681955049942476 0.0020273187447836967 -0.0031632422517515165 0.003814220971801059 0.0078815916193354183 0.0046349055751785592 -0.0034941769867355469 0.054341136696561092 -0.0045557287892270476 -0.0054589949031255153 -0.001556471697085495 0.0015897720594505315 -0.0043336546945425183
leaf_weight=2061.1128093767911 541.91250607930124 238.37789741158485 1050.4134652856737 116.51387752965093 408.09536814503372 846.80163938738406 763.7907602544874 25.358753679320216 706.37633890286088 918.03060716949403 932.58222306892276 461.28895521908998 530.71991300582886 191.73909432068467 277.55959869921207 362.7655674982816 541.50829564966261 239.59604081138968 57.616287913173437 150.32908237725496 2577.6174024473876 1.4407866243273009 177.73099695704877 742.74434961751103 900.77677760086954 1214.4209640901536 197.76492678932846
leaf_count=27181 13132 1683 9797 1144 3643 11922 8282 260 7069 15087 9421 5153 7672 2324 3038 4403 7800 2623 841 1679 46668 28 2756 20348 12192 16245 3609
internal_value=0 0.000293807 -0.000371437 0.000582026 0.000159078 0.00190212 0.00155428 -0.0019977 0.00376905 -0.000886855 0.001575 0.0019945 0.00234363 0.0029848 0.00493146 0.00491734 -3.41846e-05 -0.000784009 -0.00252739 0.00880749 -0.00269564 0.00151125 0.000718763 -0.00372291 6.56537e-05 0.000822039 -0.00380926
internal_weight=0 15950.3 11279.3 7107.03 6477.42 4671 2779.04 4172.29 1114.47 3698.38 4432.63 486.648 3346.23 2815.51 1210.14 629.609 2780.35 1086.4 3685.65 266.843 3628.03 1605.37 2238.84 1284.66 1664.57 1413.63 199.206
internal_count=246000 212520 153955 91236 84010 58565 31186 62719 10712 52824 56882 5413 42337 34665 12459 7226 37737 14545 57306 2823 56465 22206 29937 33480 20474 19882 3637
is_linear=0
shrinkage=0.0152673


Tree=194
num_leaves=28
num_cat=0
split_feature=20 130 19 387 19 125 111 140 122 20 171 411 19 10 128 388 261 111 128 125 19 388 140 140 144 64 134
split_gain=80.2601 66.2361 58.0188 51.5395 40.2088 31.8198 30.892 27.6234 27.2786 26.777 26.5278 25.7384 25.2539 26.3227 26.8281 23.7638 23.2417 23.2949 23.0184 21.9432 23.2202 21.5569 21.1385 20.3146 19.7207 19.1062 19.5472
threshold=-1.055547744992388 1.0000000180025095e-35 0.14515642090416706 -0.085097128818110032 -0.31528071226839544 -0.20131979434156846 11386.102500000003 0.4727722772277228 0.39655172413793111 -1.6973680938911146 -3.7499999999999996 1.0000000180025095e-35 -0.4294617065977519 0.81712676830105768 -0.067758620689655158 0.45678925033826762 15.625000000000002 2925.1462500000002 2.1148275862068968 0.09714228683588938 -0.26283576276536469 0.45678925033826762 0.066831683168316849 -0.29950495049504944 -0.41964285714285704 6.9218750000000115 214.07126030624266
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=8 2 3 6 -3 16 10 18 9 -1 -2 21 -12 14 19 -10 17 -5 -6 23 -21 -7 -11 -14 -18 26 -25
right_child=1 4 -4 5 7 11 -8 -9 15 22 12 -13 13 -15 -16 -17 24 -19 -20 20 -22 -23 -24 25 -26 -27 -28
leaf_value=0.0044046884737327912 -0.0040072227926035405 0.0081415233418327473 -0.0055005269294985792 -0.0012886862893030134 0.0018073170429327649 -0.0013656760819090411 0.0075779586212499847 -0.0018185077740438256 0.0011518083338615801 0.0027977155063143209 0.013476395159614378 -0.0061071443434838084 0.010119945878081148 -0.0029050776398685174 -0.00028649412476842984 -0.0036787955778174557 0.057987709830620897 0.004529607240819339 -0.0035331758561247635 0.012256555610968238 -0.0015743268594826116 -0.0049787860555885665 -0.00020309175998519229 0.002505074454406243 0.0076604975450828162 -0.0031602548700606406 0.0091542326634230786
leaf_weight=1104.5477512255311 341.2305128145963 178.74801251664758 717.56057193875313 1712.1491925660521 2624.261040719226 1376.2086234167218 131.33555477298796 780.09975490532815 797.81627686321735 1246.0919300466776 34.203752834349871 568.62715595029294 115.58222869038582 500.99485241621733 1763.2456306666136 337.23865323886275 2.5518619511276484 176.28791954182088 201.4007356390357 30.71598569303751 328.50024700164795 540.76674689725041 965.80506581626832 413.29422592557967 7.2680834885686618 94.643117252737284 140.31689820438623
leaf_count=7311 5128 1415 19636 29379 39335 25117 1663 13066 6678 11265 246 12767 1238 5484 25209 2869 29 2613 3536 286 4768 9835 9032 5227 75 1336 1457
internal_value=0 -0.000620498 -0.00133386 -0.000971444 0.00107266 -0.00210706 0.000304699 0.000719265 0.00175988 0.00245931 4.80065e-05 -0.00324455 0.000455328 0.000320353 0.00088355 -0.000275749 -0.0006126 -0.000740269 0.00142321 0.00272845 -0.000360022 -0.0023901 0.0014834 0.0041926 0.0225494 0.00311885 0.00420959
internal_weight=0 12780 8995.48 8277.92 3784.51 4383.86 3894.06 3605.76 4451.5 3316.44 3762.73 2485.6 3421.5 3387.29 2886.3 1135.05 1898.26 1888.44 2825.66 1123.05 359.216 1916.98 2211.9 763.836 9.81995 648.254 553.611
internal_count=246000 208845 151493 131857 57352 79815 52042 55937 37155 27608 50379 47719 45251 45005 39521 9547 32096 31992 42871 14312 5054 34952 20297 9258 104 8020 6684
is_linear=0
shrinkage=0.0152673


Tree=195
num_leaves=28
num_cat=0
split_feature=20 11 7 0 391 391 391 391 391 10 141 135 130 141 128 111 75 20 119 145 11 17 111 391 391 151 20
split_gain=79.3694 70.6613 73.5012 56.3066 58.5324 73.2722 56.6304 49.9953 49.8022 44.8104 44.023 32.8879 28.9977 28.6853 27.8159 27.0159 26.7586 24.2587 22.4554 22.0401 21.4793 29.8727 20.9163 20.8474 41.3799 29.6818 21.7556
threshold=0.51688161336547822 -1.6047854785478546 -0.46140449088760332 1.0000000180025095e-35 0.12742144408804593 -0.80185022711144738 -0.92257102786474277 0.48751167347278374 0.51300508801153255 0.81712676830105768 0.055555555555555559 0.83748481166464173 2.0416666666666674 -0.42592592592592587 0.31656551724137938 1849.8262500000003 1.0000000180025095e-35 -1.8843834570786695 0.72377830750893934 0.75000000000000011 0.61248624862486267 1.0000000180025095e-35 6567.232500000001 1.5250622576103898 1.4279133011046368 -0.43489289740698983 0.12356881070161159
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 -1 11 4 5 6 -4 -6 -9 10 14 13 20 -3 15 -7 17 -10 -2 -18 -12 -22 -8 24 -19 26 -26
right_child=18 2 3 -5 7 9 22 8 16 -11 12 -13 -14 -15 -16 -17 19 23 -20 -21 21 -23 -24 -25 25 -27 -28
leaf_value=-0.003094939828131295 -0.0047766625752623014 0.00076964314922550335 0.0018391011528920481 -0.0057184495218489811 -0.0028079758563922174 0.0049864135505657539 -0.0069432266340786128 0.0086619827286935781 0.0085790004892854887 -0.0006404521528691839 0.00036292515950053761 0.0023080685492805693 0.0072214006169339755 -0.0026464391537848585 0.0024413306429487856 0.010347034969488357 -0.0029697057246822031 0.0010289633085269604 0 0.033859562746858717 0.0027601433701209669 0.016441845753567708 0.0082918211850139863 -0.0051130607673077356 0.025728401550247828 0.0039772017133693095 0.089899565199746539
leaf_weight=1319.1130587104708 982.08680992387235 743.6799475364387 444.56548170931637 265.02746722474694 1095.2184061594307 1730.3226651307195 374.49547174945474 185.12052146345377 98.76329755410552 706.87383228540421 1516.6472645457834 514.33906232565641 200.7405724786222 2440.5495065450668 913.44804008305073 255.76257856190205 505.87697523087263 2186.4674869850278 296.83219930157065 3.5802706498652688 240.52957024239004 44.507880922406912 21.548823805525899 128.48550741001964 4.3422989696264267 6.9516284987330419 2.1958549860864878
leaf_count=22963 27027 9809 5407 4644 17411 16771 7765 1945 667 5512 18363 5390 2011 35242 9994 2216 7753 32857 6453 56 2535 384 389 2178 70 127 61
internal_value=0 0.000287947 0.000593629 0.0012235 0.00139695 0.00231145 -0.00188505 0 0.000982936 0.00294206 0.00346054 -0.00126552 0.00171204 -0.00184573 0.0046647 0.00568232 0.00049519 0.00116553 -0.00366466 -0.00267972 0.00109238 0.00493865 -0.0060874 0.000846433 0.00119909 0.0276861 0.0506686
internal_weight=0 15949.2 14630 10931.5 10666.4 6449.44 840.61 4217 3121.78 5608.83 4901.96 3698.57 2002.43 3184.23 2899.53 1986.09 2936.66 2427.21 1278.92 509.457 1801.68 285.037 396.044 2328.44 2199.96 13.4898 6.53815
internal_count=246000 212520 189557 139116 134472 71347 13561 63125 45714 57786 52274 50441 23293 45051 28981 18987 43769 35960 33480 7809 21282 2919 8154 35293 33115 258 131
is_linear=0
shrinkage=0.0152673


Tree=196
num_leaves=28
num_cat=0
split_feature=411 119 10 1 416 19 19 19 135 109 11 10 19 387 13 118 10 70 10 390 111 17 10 13 144 21 9
split_gain=77.8734 60.7347 57.4975 55.0552 45.8931 44.4621 65.3561 46.6899 41.4568 40.3618 32.5746 30.1941 36.4064 26.5435 25.2087 24.9544 26.2442 24.6444 24.537 24.0869 23.8756 23.2797 22.7446 22.0205 21.8327 21.7515 21.535
threshold=1.0000000180025095e-35 0.72377830750893934 0.067367119901112493 1.0000000180025095e-35 -1.0000000180025095e-35 -1.0000000180025095e-35 0.0028346554504373738 -0.31528071226839544 0.5653098420413124 0.75000000000000011 -0.78685368536853673 0.79185551435242429 -0.31528071226839544 1.6747903497335972 0.93687578784058967 0.3140287769784173 0.26473011948908126 0.55559845559845578 0.84308474110699094 0.30932035181648104 3790.8787500000003 -1.0000000180025095e-35 0.87096552671336369 0.24027925918743337 0.20535714285714288 -0.23406711614192396 0.70188133140376296
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 2 3 8 -5 7 13 -4 -1 25 -2 12 -12 17 21 -11 -17 18 23 -19 -16 -14 -9 -7 -25 26 -3
right_child=10 9 5 4 -6 6 -8 22 -10 15 11 -13 14 -15 20 16 -18 19 -20 -21 -22 -23 -24 24 -26 -27 -28
leaf_value=-0.003178970499931778 -0.0052494697972837292 0.0034736805001963178 0.0030684287731525023 0.0051855573145728421 -0.00044984573087955592 0.0021375515143677824 -0.0029106673046055158 -0.0011330069488676979 0.00079535569605584337 0.0021643832035650504 0.0083638396751029732 -0.0052105773127790024 -0.0059549285458739745 -0.002456068540657004 0.0016884376422965726 0.016780714777155745 0.0037956343163536212 0.0028982818074202547 -0.0013708293903606807 0.00906622470853026 0.016905983593756072 -0.0010469127863312053 -0.0063880902330572887 0.0027450686827074455 0.008804972844369173 -2.0608318614311878e-05 -0.0017332592221727151
leaf_weight=2716.7290392983705 624.53830800019205 1571.3667150195688 622.2309440150857 458.33184289373457 1260.5120296701789 1135.6470202784985 495.27111312747002 1587.0966807287186 785.06143226660788 102.56066418625414 98.659754406660795 406.38764862343669 262.09400309436023 185.09717099368572 248.02261511422694 99.490825351327658 60.533766241744161 282.27517516352236 294.99620467983186 323.14675212651491 26.729116249829531 1664.582582835108 219.74215733446181 278.38362929970026 288.09050557762384 919.49230933748186 207.25940945371985
leaf_count=52823 13961 12946 4863 5711 18753 13470 8990 18296 11441 1237 885 5250 5970 2704 4166 942 467 2901 2657 2884 377 29303 2119 3045 2643 15007 2189
internal_value=0 0.00049726 -2.72317e-05 -0.00118615 0.00104794 0.0010304 0.00218955 -0.000532482 -0.00228536 0.00243695 -0.00210185 -0.00137179 -0.000689168 0.00309912 -0.00109977 0.00815929 0.0119368 0.00349789 0.00267136 0.00620748 0.00321341 -0.00171987 -0.00177782 0.00337737 0.00584513 0.00187608 0.00286165
internal_weight=0 13893.3 10932.6 5220.63 1718.84 5711.98 3282.91 2429.07 3501.79 2960.7 3331.01 2706.48 2300.09 2787.64 2201.43 262.585 160.025 2602.54 1997.12 605.422 274.752 1926.68 1806.84 1702.12 566.474 2698.12 1778.63
internal_count=246000 186088 153300 88728 24464 64572 39294 25278 64264 32788 59912 45951 40701 30304 39816 2646 1409 27600 21815 5785 4543 35273 20415 19158 5688 30142 15135
is_linear=0
shrinkage=0.0152673


Tree=197
num_leaves=28
num_cat=0
split_feature=14 1 128 19 135 10 416 6 11 149 154 29 129 390 387 147 21 157 129 10 140 143 111 19 387 111 135
split_gain=77.5642 76.6895 59.4508 54.1154 45.7381 42.1592 66.6528 40.4809 34.7095 33.6002 33.3827 30.0819 26.682 34.6762 26.0831 25.5425 24.1765 24.1424 21.8374 21.6881 20.8534 20.4791 20.055 19.4908 19.1429 24.1616 19.257
threshold=-1.0000000180025095e-35 1.0000000180025095e-35 1.0677241379310347 -0.23999248241935275 0.5653098420413124 0.72043675319324285 -1.0000000180025095e-35 -0.44430242272347531 -0.78685368536853673 -0.057167895928611136 3.785714285714286 0.19895000000000004 0.64574091477933993 -0.42634925740084223 0.27862778654634074 0.98648648648648662 0.020441442567955586 1.0000000180025095e-35 -0.64973388325923598 0.75738222771597319 0.43811881188118817 -1.3888888888888886 11094.075000000003 -0.3060815920516391 0.42612580082725582 25323.367500000004 222.35996354799516
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=14 2 3 19 7 6 15 16 -9 10 -10 12 13 -8 -1 18 -5 20 -3 -2 -6 -7 -23 -16 25 26 -15
right_child=1 5 -4 4 17 21 11 8 9 -11 -12 -13 -14 24 23 -17 -18 -19 -20 -21 -22 22 -24 -25 -26 -27 -28
leaf_value=-0.0014453874511975275 0.0065089266132586929 0.014212871101917438 -0.0035358443855029549 -0.0019153267308338116 0.0021378306839106376 0.0288109895962602 -0.0024721128759920522 -0.0029365683039870049 0.0029871431273353968 -0.00097971687020384219 -0.0029466409260221265 -0.0056606049599507713 0.0041009089755041656 0.0030116336164452383 0.0053288360678255342 0.00029501681957426311 -0.0062334448258383104 0.0068742766946188897 0.0056439669054501916 0.00088518582499214201 -0.0023078374075267798 -0.0013176758263003707 0.011113453713803083 -0.0054575130812257065 -0.00090165917600617575 0.024681393306841923 -0.010149978712934646
leaf_weight=1556.8106195535511 392.83124430477619 75.8080162871629 1247.9016447588801 1139.115355886519 1176.0130914002657 5.1951558887958518 576.99435672163963 863.46565939486027 1397.9728834237903 1756.1797643266618 260.81239109486341 139.37291888706386 732.56493027508259 1095.2115933969617 40.2247026078403 202.84247441403568 416.94574475288391 199.80795153602958 1072.4654418472201 276.50604239851236 308.99089340865612 1073.3515911865979 30.807232916355133 735.65996775217354 409.23537417687476 11.690802738070486 26.04879860021174
leaf_count=23741 3401 721 22387 15396 14957 48 8402 16271 18947 28911 4177 2253 9108 12822 420 2364 11369 1782 11564 2286 4226 9529 265 14474 5838 119 222
internal_value=0 0.000400222 -0.00043184 4.01483e-05 -0.000329062 0.00184214 0.00252125 -0.000969963 -0.000200694 0.000488514 0.0020484 0.0012458 0.00158692 0.000713252 -0.00259379 0.00533747 -0.0030789 0.00188479 0.00622003 0.00420038 0.00120645 -0.000807743 -0.000960589 -0.00488528 0.00191113 0.00293521 0.00269594
internal_weight=0 14888.1 9436.54 8188.64 7519.3 5451.59 4342.23 5834.49 4278.43 3414.97 1658.79 2991.12 2851.75 2119.18 2332.7 1351.12 1556.06 1684.81 1148.27 669.337 1485 1109.35 1104.16 775.885 1542.19 1132.95 1121.26
internal_count=246000 207365 144110 121723 116036 63255 53413 95071 68306 52035 23124 38764 36511 27403 38635 14649 26765 20965 12285 5687 19183 9842 9794 14894 19001 13163 13044
is_linear=0
shrinkage=0.0152673


Tree=198
num_leaves=28
num_cat=0
split_feature=391 391 128 90 391 391 391 391 391 391 391 391 391 391 165 30 391 391 7 163 148 21 151 67 119 20 119
split_gain=77.281 104.989 73.3633 68.8056 71.5522 80.7025 73.7882 62.6687 107.256 71.0456 62.5126 54.0649 63.4305 41.1687 33.8763 35.1688 33.2541 32.5633 31.7373 28.9706 28.917 25.5997 24.3379 26.2145 25.8041 23.8825 23.8479
threshold=-0.80185022711144738 -0.63378138164839226 1.0360344827586208 -1.0000000180025095e-35 0.12742144408804593 -0.16577837173759505 -0.30091084657271944 -0.47078515063125309 -0.45016581085748902 -0.31654866915794927 -0.92257102786474277 0.48751167347278374 0.51300508801153255 -0.54098017844301649 127121.60250000002 0.024399999999999995 1.5250622576103898 -0.65476695674678731 -0.48528954406916708 -0.56249999999999989 -0.75435796269727373 -1.0000000180025095e-35 0.64064261555806101 1.5000000000000002 0.90315852205005964 -1.055547744992388 -1.0998212157330152
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=10 17 3 14 5 6 7 13 18 -10 -1 -6 -13 -5 15 22 25 -2 -9 -7 -16 -19 23 24 -3 -14 -20
right_child=1 2 -4 4 11 19 -8 8 9 -11 -12 12 16 -15 20 -17 -18 21 26 -21 -22 -23 -24 -25 -26 -27 -28
leaf_value=-0.00021381748862107797 0.00097920586018541349 -0.0025790844742964261 -0.0026897666600051362 -0.00026821048136536923 -0.0035063456730331146 -0.00029717457244974715 -0.0062387086548154067 0.0052663542087074307 -0.0013775372774005783 0.0085539945236020355 -0.006544021990200744 0.0098399594844764682 0.0030095011290784237 -0.0096341170489194338 0.040637488744327752 -0.0066410731717646797 -0.0066664478171923952 0.0040459781468628808 0.041095032918739109 0.0043797351597755791 0.0040177146025930097 0.0094784241481175209 0.005736273501688669 0.0078277816035483856 0.0013889080652177935 -0.00036785630675311717 0.015092521366143684
leaf_weight=735.10007935389876 422.60223052836955 2112.0777776930481 2119.6836440097541 363.65559902228415 1015.9648333117366 344.55243092216551 369.93608839064837 93.631693625822663 727.00968953594565 217.80539719760418 725.44320868514478 162.47009555995464 642.45036517083645 157.59880059957504 5.0741107426583758 325.06192857585847 162.42890108004212 528.80850264057517 9.1607151571661216 2693.2166538760066 156.16251186467707 337.9362314324826 108.63921231217682 66.238989798352122 462.98331268131733 2015.9946833960712 136.35421593673527
leaf_count=9953 4424 35002 34904 4142 17115 4287 6061 900 8507 1905 16520 1732 5772 2674 41 6096 2892 4102 94 27995 1836 3734 1378 919 6312 35698 1005
internal_value=0 0.000306072 -6.53524e-05 0.000384437 0.00106419 0.00226098 -5.54205e-05 0.00128121 0.00322689 0.000903581 -0.00336473 -0.000463589 0.000569704 -0.00312012 -0.00152665 -0.00188664 3.18706e-05 0.0044804 0.0123591 0.00384627 0.0052758 0.00617631 -0.00132086 -0.001615 -0.00186205 0.000445049 0.0168465
internal_weight=0 15757.5 14468.2 12348.5 9112.23 5112.92 2075.15 1705.22 1183.96 944.815 1460.54 3999.31 2983.34 521.254 3236.24 3075 2820.87 1289.35 239.147 3037.77 161.237 866.745 2749.94 2641.3 2575.06 2658.45 145.515
internal_count=246000 219527 207267 172363 120779 57570 25288 19227 12411 10412 26473 63209 46094 6816 51584 49707 44362 12260 1999 32282 1877 7836 43611 42233 41314 41470 1099
is_linear=0
shrinkage=0.0152673


Tree=199
num_leaves=28
num_cat=0
split_feature=67 21 17 19 128 111 164 2 129 133 12 389 10 19 19 10 141 414 135 387 149 5 21 7 19 135 130
split_gain=76.7906 73.0166 66.7478 56.8656 44.9096 39.6525 46.1792 28.748 28.6106 28.2303 27.2249 28.7183 27.0779 29.2329 27.2727 26.6225 24.9366 23.7991 22.8497 22.385 22.3056 21.8797 21.3251 20.4187 20.338 20.0234 19.5669
threshold=1.0000000180025095e-35 -1.4231812591257043 1.0000000180025095e-35 1.0000000180025095e-35 0.96213793103448286 1849.8262500000003 39122.122500000005 1.0000000180025095e-35 -0.74775638996693616 0.20584615384615387 -0.82350255661066463 0.043981449847253752 -0.52623266034885308 -1.0000000180025095e-35 -0.20494525875886938 0.79913473423980241 -0.055555555555555546 -1.0000000180025095e-35 0.46445929526123947 -0.32722301719736219 -0.44132996434222038 -0.85124999999999995 -2.0089485232886477 -0.087951732288362242 -0.30194024828142119 -0.20139732685297687 2.2916666666666674
decision_type=2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
left_child=1 22 3 4 5 6 7 8 25 -8 -4 20 -10 14 15 -14 17 21 -5 -2 -12 -15 -1 -7 -24 -3 -9
right_child=19 2 10 18 -6 23 9 26 12 -11 11 -13 13 16 -16 -17 -18 -19 -20 -21 -22 -23 24 -25 -26 -27 -28
leaf_value=0.0047967569862760106 0.0047895270381150814 0.020302549514260783 -0.0035827854852286374 -0.0049871658630568135 -0.0032529849171551999 0.00027030033339921189 -4.1703607333989398e-05 -0.0032219403683887687 -0.002914034717138512 0.0054302564494810059 0.0074236108530622074 -6.5524498212272806e-05 0.0029484934218763389 0.034882979203577948 -0.0043240054841666205 -0.0043887562573350801 -0.00067308425821913033 0.0041148872496802715 -0.0007390196464341942 0.0015325007819850976 0.0024420225956820348 -0.002340059797932646 0.0064370029789993571 0.0055912810566624048 0.00075805454618310642 0 0.0028219509165239988
leaf_weight=534.84473429620266 757.75610357709229 25.795968785881996 218.56327837891877 1246.2629418056458 1530.5263818651438 318.78343214653432 463.37019860744476 1742.0726498700678 918.80279475823045 412.24390327185392 274.78143769316375 851.64592462778091 354.12730268575251 3.5251564551144829 540.84685962833464 170.2325118035078 836.56433863006532 787.44444906152785 393.72822268307209 1439.8194121159613 930.31819012016058 206.57433005049825 162.84799104183912 364.6332873981446 1573.2311007529497 21.584130300208926 132.72198572009802
leaf_count=3355 7897 350 3511 31141 25697 4546 5815 27847 18953 3762 2979 10892 3766 53 8053 1629 12932 9437 8065 20147 11413 3499 915 5140 12119 249 1838
internal_value=0 -0.000395438 -0.000845347 -0.00136087 -0.000874581 -0.000374545 -0.000737356 -0.00123661 -0.000481252 0.00252472 0.00152271 0.00207 -0.000630114 9.066e-05 -0.00191734 0.00054824 0.00126193 0.00289368 -0.00397307 0.00266007 0.00358655 -0.00163937 0.00212542 0.00312349 0.00129671 0.0112745 -0.00278894
internal_weight=0 15016.1 12745.1 10469.8 8829.85 7299.32 6615.91 5740.29 3865.5 875.614 2275.31 2056.75 3818.12 2899.31 1065.21 524.36 1834.11 997.544 1639.99 2197.58 1205.1 210.099 2270.92 683.417 1736.08 47.3801 1874.79
internal_count=246000 217956 201567 172772 133566 107869 98183 88606 58921 9577 28795 25284 58322 39369 13448 5395 25921 12989 39206 28044 14392 3552 16389 9686 13034 599 29685
is_linear=0
shrinkage=0.0152673


end of trees

feature_importances:
Column_20=482
Column_19=456
Column_391=455
Column_21=450
Column_10=212
Column_7=168
Column_1=152
Column_8=145
Column_149=142
Column_11=138
Column_130=126
Column_135=126
Column_143=116
Column_141=113
Column_6=112
Column_411=111
Column_155=95
Column_119=89
Column_90=84
Column_390=83
Column_109=75
Column_387=72
Column_164=61
Column_128=57
Column_414=52
Column_2=48
Column_14=47
Column_118=47
Column_111=44
Column_13=42
Column_389=42
Column_17=40
Column_165=40
Column_67=36
Column_0=33
Column_416=33
Column_70=30
Column_140=29
Column_392=29
Column_157=27
Column_120=25
Column_154=24
Column_124=23
Column_388=23
Column_147=22
Column_112=21
Column_129=21
Column_168=20
Column_409=19
Column_69=18
Column_166=18
Column_125=17
Column_152=17
Column_171=17
Column_163=16
Column_86=15
Column_126=14
Column_150=13
Column_167=13
Column_52=11
Column_122=11
Column_12=10
Column_29=10
Column_137=10
Column_151=10
Column_16=9
Column_148=9
Column_172=9
Column_47=8
Column_64=8
Column_161=8
Column_139=7
Column_158=7
Column_248=7
Column_9=6
Column_24=6
Column_38=6
Column_60=6
Column_61=6
Column_113=6
Column_138=6
Column_144=6
Column_57=5
Column_131=5
Column_142=5
Column_162=5
Column_261=5
Column_127=4
Column_133=4
Column_145=4
Column_434=4
Column_513=4
Column_25=3
Column_27=3
Column_33=3
Column_134=3
Column_498=3
Column_23=2
Column_30=2
Column_32=2
Column_35=2
Column_36=2
Column_43=2
Column_49=2
Column_51=2
Column_75=2
Column_110=2
Column_136=2
Column_209=2
Column_231=2
Column_245=2
Column_264=2
Column_429=2
Column_430=2
Column_5=1
Column_15=1
Column_18=1
Column_22=1
Column_37=1
Column_45=1
Column_46=1
Column_50=1
Column_53=1
Column_55=1
Column_63=1
Column_66=1
Column_115=1
Column_132=1
Column_160=1
Column_219=1
Column_223=1
Column_249=1
Column_301=1
Column_303=1
Column_316=1
Column_336=1
Column_393=1
Column_417=1
Column_449=1
Column_451=1
Column_480=1
Column_486=1
Column_506=1

parameters:
[boosting: gbdt]
[objective: binary]
[metric: binary_logloss]
[tree_learner: serial]
[device_type: cpu]
[data: ]
[valid: ]
[num_iterations: 200]
[learning_rate: 0.0152673]
[num_leaves: 28]
[num_threads: -1]
[deterministic: 0]
[force_col_wise: 0]
[force_row_wise: 0]
[histogram_pool_size: -1]
[max_depth: 16]
[min_data_in_leaf: 20]
[min_sum_hessian_in_leaf: 0.001]
[bagging_fraction: 0.2]
[pos_bagging_fraction: 1]
[neg_bagging_fraction: 1]
[bagging_freq: 0]
[bagging_seed: 3]
[feature_fraction: 0.7]
[feature_fraction_bynode: 1]
[feature_fraction_seed: 2]
[extra_trees: 0]
[extra_seed: 6]
[early_stopping_round: 0]
[first_metric_only: 0]
[max_delta_step: 0]
[lambda_l1: 0.6]
[lambda_l2: 0.2]
[linear_lambda: 0]
[min_gain_to_split: 0]
[drop_rate: 0.1]
[max_drop: 50]
[skip_drop: 0.5]
[xgboost_dart_mode: 0]
[uniform_drop: 0]
[drop_seed: 4]
[top_rate: 0.2]
[other_rate: 0.1]
[min_data_per_group: 100]
[max_cat_threshold: 32]
[cat_l2: 10]
[cat_smooth: 10]
[max_cat_to_onehot: 4]
[top_k: 20]
[monotone_constraints: ]
[monotone_constraints_method: basic]
[monotone_penalty: 0]
[feature_contri: ]
[forcedsplits_filename: ]
[refit_decay_rate: 0.9]
[cegb_tradeoff: 1]
[cegb_penalty_split: 0]
[cegb_penalty_feature_lazy: ]
[cegb_penalty_feature_coupled: ]
[path_smooth: 0]
[interaction_constraints: ]
[verbosity: -1]
[saved_feature_importance_type: 0]
[linear_tree: 0]
[max_bin: 255]
[max_bin_by_feature: ]
[min_data_in_bin: 3]
[bin_construct_sample_cnt: 200000]
[data_random_seed: 1]
[is_enable_sparse: 1]
[enable_bundle: 1]
[use_missing: 1]
[zero_as_missing: 0]
[feature_pre_filter: 1]
[pre_partition: 0]
[two_round: 0]
[header: 0]
[label_column: ]
[weight_column: ]
[group_column: ]
[ignore_column: ]
[categorical_feature: ]
[forcedbins_filename: ]
[precise_float_parser: 0]
[objective_seed: 5]
[num_class: 1]
[is_unbalance: 0]
[scale_pos_weight: 1]
[sigmoid: 1]
[boost_from_average: 1]
[reg_sqrt: 0]
[alpha: 0.9]
[fair_c: 1]
[poisson_max_delta_step: 0.7]
[tweedie_variance_power: 1.5]
[lambdarank_truncation_level: 30]
[lambdarank_norm: 1]
[label_gain: ]
[eval_at: ]
[multi_error_top_k: 1]
[auc_mu_weights: ]
[num_machines: 1]
[local_listen_port: 12400]
[time_out: 120]
[machine_list_filename: ]
[machines: ]
[gpu_platform_id: -1]
[gpu_device_id: -1]
[gpu_use_dp: 0]
[num_gpu: 1]

end of parameters

pandas_categorical:null
??      ??network???_Booster__need_reload_eval_info???_train_data_name??training??_Booster__attr?}??_Booster__set_objective_to_none???best_iteration?K ?
best_score??collections??defaultdict???j?  ?OrderedDict?????R??name_valid_sets?]??_Booster__num_dataset?K ?_Booster__init_predictor?N?_Booster__num_class?K?_Booster__inner_predict_buffer?]??_Booster__is_predicted_cur_iter?]??_Booster__num_inner_eval?K?_Booster__name_inner_eval?]??binary_logloss?a?"_Booster__higher_better_inner_eval?]??a?pandas_categorical?N?train_set_version?K?params?}?(jd  je  jy  jk  j:  Cgfffff?????R?ji  jk  j:  C??k?tD?????R?jh  Kjs  Kjr  G?PbM????jq  G        j?  J????jg  Kj?  Nj}  jk  j:  C433333?????R?j?  jk  j:  C???????????R?jt  jk  j:  C???????????R?jp  J@ jx  K hJ????jf  ?binary??metric?]?j?  a?num_iterations?KȌearly_stopping_round?Nuub?_evals_result?N?_best_score?j?  ?_best_iteration?N?_other_params?}?(jo  K?jh  Kji  jn  jt  jw  jy  j|  jg  Kj}  j?  j?  j?  u?
_objective?j?  ?class_weight?N?_class_weight?N?
_class_map?}?(jk  j:  C        ???R?jk  h%?i8?????R?(Kj;  NNNJ????J????K t?bC        ???R?jk  j:  C      ?????R?jk  j?  C       ???R?u?_n_features?M?_n_features_in?M?_classes?hhK ??h ??R?(KK??j:  ?C              ???t?b?
_n_classes?K?_le??sklearn.preprocessing._label??LabelEncoder???)??}?(?classes_?j?  j?  j@  ub?_fobj?N?fitted_??ub??ej\  Nh?j?  j@  ub.