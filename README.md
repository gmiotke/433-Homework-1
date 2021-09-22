Homework 1
================
Graham Miotke
9/21/2021

Hello
    There\!\!

``` r
read_csv("MI16.TXT")
```

    ## Rows: 11156 Columns: 135

    ## -- Column specification -------------------------------------------------------------------------------------------------------------------------------------
    ## Delimiter: ","
    ## chr (58): STRUCTURE_NUMBER_008, ROUTE_NUMBER_005D, HIGHWAY_DISTRICT_002, COU...
    ## dbl (72): STATE_CODE_001, RECORD_TYPE_005A, ROUTE_PREFIX_005B, SERVICE_LEVEL...
    ## lgl  (5): CRITICAL_FACILITY_006B, TEMP_STRUCTURE_103, REMARKS, SPECIAL_CODE,...

    ## 
    ## 
    ## i Use `spec()` to retrieve the full column specification for this data.
    ## i Specify the column types or set `show_col_types = FALSE` to quiet this message.

    ## # A tibble: 11,156 x 135
    ##    STATE_CODE_001 STRUCTURE_NUMBE~ RECORD_TYPE_005A ROUTE_PREFIX_00~
    ##             <dbl> <chr>                       <dbl>            <dbl>
    ##  1             26 000000000000007                 1                2
    ##  2             26 000000000000009                 1                4
    ##  3             26 000000000000010                 1                4
    ##  4             26 000000000000011                 1                4
    ##  5             26 000000000000012                 1                4
    ##  6             26 000000000000013                 1                4
    ##  7             26 000000000000014                 1                4
    ##  8             26 000000000000015                 1                4
    ##  9             26 000000000000016                 1                4
    ## 10             26 000000000000017                 1                4
    ## # ... with 11,146 more rows, and 131 more variables: SERVICE_LEVEL_005C <dbl>,
    ## #   ROUTE_NUMBER_005D <chr>, DIRECTION_005E <dbl>, HIGHWAY_DISTRICT_002 <chr>,
    ## #   COUNTY_CODE_003 <chr>, PLACE_CODE_004 <dbl>, FEATURES_DESC_006A <chr>,
    ## #   CRITICAL_FACILITY_006B <lgl>, FACILITY_CARRIED_007 <chr>,
    ## #   LOCATION_009 <chr>, MIN_VERT_CLR_010 <dbl>, KILOPOINT_011 <dbl>,
    ## #   BASE_HWY_NETWORK_012 <dbl>, LRS_INV_ROUTE_013A <chr>,
    ## #   SUBROUTE_NO_013B <dbl>, LAT_016 <dbl>, LONG_017 <chr>,
    ## #   DETOUR_KILOS_019 <dbl>, TOLL_020 <dbl>, MAINTENANCE_021 <chr>,
    ## #   OWNER_022 <chr>, FUNCTIONAL_CLASS_026 <chr>, YEAR_BUILT_027 <dbl>,
    ## #   TRAFFIC_LANES_ON_028A <dbl>, TRAFFIC_LANES_UND_028B <dbl>, ADT_029 <dbl>,
    ## #   YEAR_ADT_030 <dbl>, DESIGN_LOAD_031 <chr>, APPR_WIDTH_MT_032 <dbl>,
    ## #   MEDIAN_CODE_033 <dbl>, DEGREES_SKEW_034 <dbl>, STRUCTURE_FLARED_035 <dbl>,
    ## #   RAILINGS_036A <chr>, TRANSITIONS_036B <chr>, APPR_RAIL_036C <chr>,
    ## #   APPR_RAIL_END_036D <chr>, HISTORY_037 <dbl>, NAVIGATION_038 <chr>,
    ## #   NAV_VERT_CLR_MT_039 <dbl>, NAV_HORR_CLR_MT_040 <dbl>,
    ## #   OPEN_CLOSED_POSTED_041 <chr>, SERVICE_ON_042A <dbl>,
    ## #   SERVICE_UND_042B <dbl>, STRUCTURE_KIND_043A <dbl>,
    ## #   STRUCTURE_TYPE_043B <chr>, APPR_KIND_044A <dbl>, APPR_TYPE_044B <chr>,
    ## #   MAIN_UNIT_SPANS_045 <dbl>, APPR_SPANS_046 <dbl>, HORR_CLR_MT_047 <dbl>,
    ## #   MAX_SPAN_LEN_MT_048 <dbl>, STRUCTURE_LEN_MT_049 <dbl>,
    ## #   LEFT_CURB_MT_050A <dbl>, RIGHT_CURB_MT_050B <dbl>,
    ## #   ROADWAY_WIDTH_MT_051 <dbl>, DECK_WIDTH_MT_052 <dbl>,
    ## #   VERT_CLR_OVER_MT_053 <dbl>, VERT_CLR_UND_REF_054A <chr>,
    ## #   VERT_CLR_UND_054B <dbl>, LAT_UND_REF_055A <chr>, LAT_UND_MT_055B <dbl>,
    ## #   LEFT_LAT_UND_MT_056 <dbl>, DECK_COND_058 <chr>,
    ## #   SUPERSTRUCTURE_COND_059 <chr>, SUBSTRUCTURE_COND_060 <chr>,
    ## #   CHANNEL_COND_061 <chr>, CULVERT_COND_062 <chr>, OPR_RATING_METH_063 <chr>,
    ## #   OPERATING_RATING_064 <dbl>, INV_RATING_METH_065 <chr>,
    ## #   INVENTORY_RATING_066 <dbl>, STRUCTURAL_EVAL_067 <chr>,
    ## #   DECK_GEOMETRY_EVAL_068 <chr>, UNDCLRENCE_EVAL_069 <chr>,
    ## #   POSTING_EVAL_070 <dbl>, WATERWAY_EVAL_071 <chr>, APPR_ROAD_EVAL_072 <dbl>,
    ## #   WORK_PROPOSED_075A <dbl>, WORK_DONE_BY_075B <dbl>, IMP_LEN_MT_076 <dbl>,
    ## #   DATE_OF_INSPECT_090 <dbl>, INSPECT_FREQ_MONTHS_091 <dbl>,
    ## #   FRACTURE_092A <chr>, UNDWATER_LOOK_SEE_092B <chr>, SPEC_INSPECT_092C <chr>,
    ## #   FRACTURE_LAST_DATE_093A <chr>, UNDWATER_LAST_DATE_093B <chr>,
    ## #   SPEC_LAST_DATE_093C <chr>, BRIDGE_IMP_COST_094 <dbl>,
    ## #   ROADWAY_IMP_COST_095 <dbl>, TOTAL_IMP_COST_096 <dbl>,
    ## #   YEAR_OF_IMP_097 <dbl>, OTHER_STATE_CODE_098A <dbl>,
    ## #   OTHER_STATE_PCNT_098B <dbl>, OTHR_STATE_STRUC_NO_099 <chr>,
    ## #   STRAHNET_HIGHWAY_100 <dbl>, PARALLEL_STRUCTURE_101 <chr>,
    ## #   TRAFFIC_DIRECTION_102 <dbl>, TEMP_STRUCTURE_103 <lgl>,
    ## #   HIGHWAY_SYSTEM_104 <dbl>, ...
