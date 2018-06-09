# [Performance Counters](performance-counters-portal.md)
## [What's New](performance-counters-what-s-new.md)
## [About Performance Counters](about-performance-counters.md)
### [64-bit Support](64-bit-support.md)
### [Limited User Access Support](limited-user-access-support.md)
### [Accessing Remote Counter Data](accessing-remote-counter-data.md)
## [Using Performance Counters](using-performance-counters.md)
### [Consuming Counter Data](consuming-counter-data.md)
#### [Using the PDH Functions to Consume Counter Data](using-the-pdh-functions-to-consume-counter-data.md)
##### [Creating a Query](creating-a-query.md)
###### [Specifying a Counter Path](specifying-a-counter-path.md)
###### [Obtaining Counter Path Elements from a Counter Path](obtaining-counter-path-elements-from-a-counter-path.md)
###### [Browsing Counters](browsing-counters.md)
###### [Determining Whether a Counter Is Located on a Computer](determining-whether-a-counter-is-located-on-a-machine.md)
##### [Collecting Performance Data](collecting-performance-data.md)
##### [Displaying Performance Data](displaying-performance-data.md)
##### [Working with Log Files](working-with-log-files.md)
###### [Setting a Time Range for a Query](setting-a-time-range-for-a-query.md)
###### [Getting the Size of a Log File](getting-the-size-of-a-log-file.md)
##### [Checking PDH Interface Return Values](checking-pdh-interface-return-values.md)
##### [Getting Counter Information](getting-counter-information.md)
##### [PDH Examples](examples.md)
###### [Enumerating Process Objects](enumerating-process-objects.md)
###### [Browsing Performance Counters](browsing-performance-counters.md)
###### [Writing Performance Data to a Log File](writing-performance-data-to-a-log-file.md)
###### [Reading Performance Data from a Log File](reading-performance-data-from-a-log-file.md)
###### [Converting Data from a Binary-format Log File to a CSV-format Log File](transferring-data-from-a-perfmon-format-log-file-to-a-csv-format-log-file.md)
#### [Using the Registry Functions to Consume Counter Data](using-the-registry-functions-to-consume-counter-data.md)
##### [Retrieving Counter Names and Help Text](retrieving-counter-names-and-explanations.md)
##### [Displaying Object, Instance, and Counter Names](displaying-object-instance-and-counter-names.md)
##### [Retrieving Counter Data](retrieving-counter-data.md)
##### [Calculating Counter Values](calculating-counter-values.md)
##### [Handling Duplicate Instance Names](handling-duplicate-instance-names.md)
##### [Performance Data Format](performance-data-format.md)
### [Providing Counter Data](providing-counter-data.md)
#### [Providing Counter Data Using Version 2.0](providing-counter-data-using-version-2-0.md)
#### [Providing Counter Data Using a Performance DLL](providing-counter-data-using-a-performance-dll.md)
##### [Adding Performance Counters](adding-performance-counters.md)
###### [Object and Counter Design](object-and-counter-design.md)
###### [Adding Counter Names and Descriptions to the Registry](adding-counter-names-and-descriptions-to-the-registry.md)
###### [Creating the Application’s Performance Key](creating-the-applications-performance-key.md)
###### [Creating Other Registry Entries](creating-other-registry-entries.md)
##### [Deleting Performance Counters](deleting-performance-counters.md)
###### [Removing Counter Names and Descriptions from the Registry](removing-counter-names-and-descriptions-from-the-registry.md)
##### [Creating a Performance Extension DLL](creating-a-performance-extension-dll.md)
###### [Implementing OpenPerformanceData](implementing-openperformancedata.md)
###### [Implementing CollectPerformanceData](implementing-collectperformancedata.md)
###### [Communicating With Your Application](communicating-with-your-application.md)
###### [Error Handling in the DLL](error-handling-in-the-dll.md)
###### [Restricting Access to Performance Extension  DLLs](restricting-access-to-performance-extension--dlls.md)
###### [Performance DLL Samples](performance-dll-samples.md)
## [Performance Counters Reference](performance-counters-reference.md)
### [Performance Counters Functions for Visual Basic](performance-counters-functions-for-visual-basic.md)
#### [PdhVbAddCounter](pdhvbaddcounter.md)
#### [PdhVbCreateCounterPathList](pdhvbcreatecounterpathlist.md)
#### [PdhVbGetCounterPathElements](pdhvbgetcounterpathelements.md)
#### [PdhVbGetCounterPathFromList](pdhvbgetcounterpathfromlist.md)
#### [PdhVbGetDoubleCounterValue](pdhvbgetdoublecountervalue.md)
#### [PdhVbGetLogFileSize](pdhvbgetlogfilesize.md)
#### [PdhVbGetOneCounterPath](pdhvbgetonecounterpath.md)
#### [PdhVbIsGoodStatus](pdhvbisgoodstatus.md)
#### [PdhVbOpenLog](pdhvbopenlog.md)
#### [PdhVbOpenQuery](pdhvbopenquery.md)
#### [PdhVbUpdateLog](pdhvbupdatelog.md)
### [Performance Counters Schema](performance-counters-schema.md)
#### [Performance Counters Elements](performance-counters-elements.md)
##### [counter (counterSet) Element](performance-counters-counter--counterset--element.md)
##### [counterAttribute (counterAttributes) Element](performance-counters-counterattribute--counterattributes--element.md)
##### [counterAttributes (counter) Element](performance-counters-counterattributes--counter--element.md)
##### [counters Element](performance-counters-counters-element.md)
##### [counterSet (provider) Element](performance-counters-counterset--provider--element.md)
##### [provider (counters) Element](performance-counters-provider--counters--element.md)
##### [struct (structs) Element](performance-counters-struct--structs--element.md)
##### [structs (counterSet) Element](performance-counters-structs--counterset--element.md)
#### [Performance Counters Simple Types](performance-counters-simple-types.md)
##### [CSymbolType Simple Type](performance-counters-csymboltype-simple-type.md)
##### [GUIDType Simple Type](performance-counters-guidtype-simple-type.md)
##### [HexInt32Type Simple Type](performance-counters-hexint32type-simple-type.md)
##### [UInt32Type Simple Type](performance-counters-uint32type-simple-type.md)
#### [Performance Counters Complex Types](performance-counters-complex-types.md)
##### [counter Complex Type](performance-counters-counter-complex-type.md)
##### [counterAttribute Complex Type](performance-counters-counterattribute-complex-type.md)
##### [counterAttributes Complex Type](performance-counters-counterattributes-complex-type.md)
##### [counters Complex Type](performance-counters-counters-complex-type.md)
##### [counterSet Complex Type](performance-counters-counterset-complex-type.md)
##### [provider Complex Type](performance-counters-provider-complex-type.md)
##### [struct Complex Type](performance-counters-struct-complex-type.md)
##### [structs Complex Type](performance-counters-structs-complex-type.md)
### [Performance Counter Enumerations](performance-counter-enumerations.md)
#### [PerfCounterDataType](/windows/desktop/api/Perflib/ne-perflib-_perfcounterdatatype)
#### [PerfRegInfoType](/windows/desktop/api/Perflib/ne-perflib-_perfreginfotype)
### [Performance Counters Structures](performance-counters-structures.md)
#### [PDH_BROWSE_DLG_CONFIG](/windows/desktop/api/Pdh/ns-pdh-_browsedlgconfig_a)
#### [PDH_BROWSE_DLG_CONFIG_H](/windows/desktop/api/Pdh/ns-pdh-_browsedlgconfig_ha)
#### [PDH_COUNTER_INFO](/windows/desktop/api/Pdh/ns-pdh-_pdh_counter_info_a)
#### [PDH_COUNTER_PATH_ELEMENTS](/windows/desktop/api/Pdh/ns-pdh-_pdh_counter_path_elements_a)
#### [PDH_DATA_ITEM_PATH_ELEMENTS](/windows/desktop/api/Pdh/ns-pdh-_pdh_data_item_path_elements_a)
#### [PDH_FMT_COUNTERVALUE](/windows/desktop/api/Pdh/ns-pdh-_pdh_fmt_countervalue)
#### [PDH_FMT_COUNTERVALUE_ITEM](/windows/desktop/api/Pdh/ns-pdh-_pdh_fmt_countervalue_item_a)
#### [PDH_RAW_COUNTER](/windows/desktop/api/Pdh/ns-pdh-_pdh_raw_counter)
#### [PDH_RAW_COUNTER_ITEM](/windows/desktop/api/Pdh/ns-pdh-_pdh_raw_counter_item_a)
#### [PDH_RAW_LOG_RECORD](/windows/desktop/api/Pdh/ns-pdh-_pdh_raw_log_record)
#### [PDH_STATISTICS](/windows/desktop/api/Pdh/ns-pdh-_pdh_statistics)
#### [PDH_TIME_INFO](/windows/desktop/api/Pdh/ns-pdh-_pdh_time_info)
#### [PERF_COUNTER_BLOCK](/windows/desktop/api/Winperf/ns-winperf-_perf_counter_block)
#### [PERF_COUNTER_DATA](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_data)
#### [PERF_COUNTER_DEFINITION](/windows/desktop/api/Winperf/ns-winperf-_perf_counter_definition)
#### [PERF_COUNTER_HEADER](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_header)
#### [PERF_COUNTER_IDENTIFIER](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_identifier)
#### [PERF_COUNTER_IDENTITY](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_identity)
#### [PERF_COUNTER_INFO](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_info)
#### [PERF_COUNTER_REG_INFO](/windows/desktop/api/Perflib/ns-perflib-_perf_counter_reg_info)
#### [PERF_COUNTERSET_INFO](/windows/desktop/api/Perflib/ns-perflib-_perf_counterset_info)
#### [PERF_COUNTERSET_INSTANCE](/windows/desktop/api/Perflib/ns-perflib-_perf_counterset_instance)
#### [PERF_COUNTERSET_REG_INFO](/windows/desktop/api/Perflib/ns-perflib-_perf_counterset_reg_info)
#### [PERF_DATA_BLOCK](/windows/desktop/api/Winperf/ns-winperf-_perf_data_block)
#### [PERF_DATA_HEADER](/windows/desktop/api/Perflib/ns-perflib-_perf_data_header)
#### [PERF_INSTANCE_DEFINITION](/windows/desktop/api/Winperf/ns-winperf-_perf_instance_definition)
#### [PERF_INSTANCE_HEADER](/windows/desktop/api/Perflib/ns-perflib-_perf_instance_header)
#### [PERF_MULTI_COUNTERS](/windows/desktop/api/Perflib/ns-perflib-_perf_multi_counters)
#### [PERF_MULTI_INSTANCES](/windows/desktop/api/Perflib/ns-perflib-_perf_multi_instances)
#### [PERF_OBJECT_TYPE](/windows/desktop/api/Winperf/ns-winperf-_perf_object_type)
#### [PERF_PROVIDER_CONTEXT](/windows/desktop/api/Perflib/ns-perflib-_provider_context)
#### [PERF_STRING_BUFFER_HEADER](/windows/desktop/api/Perflib/ns-perflib-_string_buffer_header)
#### [PERF_STRING_COUNTER_HEADER](/windows/desktop/api/Perflib/ns-perflib-_string_counter_header)
### [Performance Counters Tools](performance-counters-tools.md)
#### [CTRPP](ctrpp.md)
### [Performance Counters Data Types](performance-counters-types.md)
### [Performance Data Helper Error Codes](pdh-error-codes.md)
### [SQL Log File Schema](sql-log-file-schema.md)
#### [CounterData](counterdata.md)
#### [CounterDetails](counterdetails.md)
#### [DisplayToID](displaytoid.md)
### [Performance Counters Functions](performance-counters-functions.md)
#### [PERF_MEM_ALLOC](/windows/desktop/api/Perflib/nc-perflib-perf_mem_alloc)
#### [PERF_MEM_FREE](/windows/desktop/api/Perflib/nc-perflib-perf_mem_free)
#### [PM_CLOSE_PROC](/windows/desktop/api/Winperf/nc-winperf-pm_close_proc)
#### [PM_COLLECT_PROC](/windows/desktop/api/Winperf/nc-winperf-pm_collect_proc)
#### [PERFLIBREQUEST](/windows/desktop/api/Perflib/nc-perflib-perflibrequest)
#### [CounterCleanup](countercleanup.md)
#### [CounterInitialize](counterinitialize.md)
#### [CounterPathCallBack](/windows/desktop/api/Pdh/nc-pdh-counterpathcallback)
#### [LoadPerfCounterTextStrings](/windows/desktop/api/Loadperf/nf-loadperf-loadperfcountertextstringsa)
#### [PM_OPEN_PROC](/windows/desktop/api/Winperf/)
#### [PdhAddCounter](/windows/desktop/api/Pdh/nf-pdh-pdhaddcountera)
#### [PdhAddEnglishCounter](/windows/desktop/api/Pdh/nf-pdh-pdhaddenglishcountera)
#### [PdhBindInputDataSource](/windows/desktop/api/Pdh/nf-pdh-pdhbindinputdatasourcea)
#### [PdhBrowseCounters](/windows/desktop/api/Pdh/nf-pdh-pdhbrowsecountersa)
#### [PdhBrowseCountersH](/windows/desktop/api/Pdh/nf-pdh-pdhbrowsecountersha)
#### [PdhCalculateCounterFromRawValue](/windows/desktop/api/Pdh/nf-pdh-pdhcalculatecounterfromrawvalue)
#### [PdhCloseLog](/windows/desktop/api/Pdh/nf-pdh-pdhcloselog)
#### [PdhCloseQuery](/windows/desktop/api/Pdh/nf-pdh-pdhclosequery)
#### [PdhCollectQueryData](/windows/desktop/api/Pdh/nf-pdh-pdhcollectquerydata)
#### [PdhCollectQueryDataEx](/windows/desktop/api/Pdh/nf-pdh-pdhcollectquerydataex)
#### [PdhCollectQueryDataWithTime](/windows/desktop/api/Pdh/nf-pdh-pdhcollectquerydatawithtime)
#### [PdhComputeCounterStatistics](/windows/desktop/api/Pdh/nf-pdh-pdhcomputecounterstatistics)
#### [PdhConnectMachine](/windows/desktop/api/Pdh/nf-pdh-pdhconnectmachinea)
#### [PdhEnumLogSetNames](/windows/desktop/api/Pdh/nf-pdh-pdhenumlogsetnamesa)
#### [PdhEnumMachines](/windows/desktop/api/Pdh/nf-pdh-pdhenummachinesa)
#### [PdhEnumMachinesH](/windows/desktop/api/Pdh/nf-pdh-pdhenummachinesha)
#### [PdhEnumObjectItems](/windows/desktop/api/Pdh/nf-pdh-pdhenumobjectitemsa)
#### [PdhEnumObjectItemsH](/windows/desktop/api/Pdh/nf-pdh-pdhenumobjectitemsha)
#### [PdhEnumObjects](/windows/desktop/api/Pdh/nf-pdh-pdhenumobjectsa)
#### [PdhEnumObjectsH](/windows/desktop/api/Pdh/nf-pdh-pdhenumobjectsha)
#### [PdhExpandCounterPath](/windows/desktop/api/Pdh/nf-pdh-pdhexpandcounterpatha)
#### [PdhExpandWildCardPath](/windows/desktop/api/Pdh/nf-pdh-pdhexpandwildcardpatha)
#### [PdhExpandWildCardPathH](/windows/desktop/api/Pdh/nf-pdh-pdhexpandwildcardpathha)
#### [PdhFormatFromRawValue](/windows/desktop/api/Pdh/nf-pdh-pdhformatfromrawvalue)
#### [PdhGetCounterInfo](/windows/desktop/api/Pdh/nf-pdh-pdhgetcounterinfoa)
#### [PdhGetCounterTimeBase](/windows/desktop/api/Pdh/nf-pdh-pdhgetcountertimebase)
#### [PdhGetDataSourceTimeRange](/windows/desktop/api/Pdh/nf-pdh-pdhgetdatasourcetimerangea)
#### [PdhGetDataSourceTimeRangeH](/windows/desktop/api/Pdh/nf-pdh-pdhgetdatasourcetimerangeh)
#### [PdhGetDefaultPerfCounter](/windows/desktop/api/Pdh/nf-pdh-pdhgetdefaultperfcountera)
#### [PdhGetDefaultPerfCounterH](/windows/desktop/api/Pdh/nf-pdh-pdhgetdefaultperfcounterha)
#### [PdhGetDefaultPerfObject](/windows/desktop/api/Pdh/nf-pdh-pdhgetdefaultperfobjecta)
#### [PdhGetDefaultPerfObjectH](/windows/desktop/api/Pdh/nf-pdh-pdhgetdefaultperfobjectha)
#### [PdhGetDllVersion](/windows/desktop/api/Pdh/nf-pdh-pdhgetdllversion)
#### [PdhGetFormattedCounterArray](/windows/desktop/api/Pdh/nf-pdh-pdhgetformattedcounterarraya)
#### [PdhGetFormattedCounterValue](/windows/desktop/api/Pdh/nf-pdh-pdhgetformattedcountervalue)
#### [PdhGetLogFileSize](/windows/desktop/api/Pdh/nf-pdh-pdhgetlogfilesize)
#### [PdhGetRawCounterArray](/windows/desktop/api/Pdh/nf-pdh-pdhgetrawcounterarraya)
#### [PdhGetRawCounterValue](/windows/desktop/api/Pdh/nf-pdh-pdhgetrawcountervalue)
#### [PdhIsRealTimeQuery](/windows/desktop/api/Pdh/nf-pdh-pdhisrealtimequery)
#### [PdhLookupPerfIndexByName](/windows/desktop/api/Pdh/nf-pdh-pdhlookupperfindexbynamea)
#### [PdhLookupPerfNameByIndex](/windows/desktop/api/Pdh/nf-pdh-pdhlookupperfnamebyindexa)
#### [PdhMakeCounterPath](/windows/desktop/api/Pdh/nf-pdh-pdhmakecounterpatha)
#### [PdhOpenLog](/windows/desktop/api/Pdh/nf-pdh-pdhopenloga)
#### [PdhOpenQuery](/windows/desktop/api/Pdh/nf-pdh-pdhopenquerya)
#### [PdhOpenQueryH](/windows/desktop/api/Pdh/nf-pdh-pdhopenqueryh)
#### [PdhParseCounterPath](/windows/desktop/api/Pdh/nf-pdh-pdhparsecounterpatha)
#### [PdhParseInstanceName](/windows/desktop/api/Pdh/nf-pdh-pdhparseinstancenamea)
#### [PdhReadRawLogRecord](/windows/desktop/api/Pdh/nf-pdh-pdhreadrawlogrecord)
#### [PdhRemoveCounter](/windows/desktop/api/Pdh/nf-pdh-pdhremovecounter)
#### [PdhSelectDataSource](/windows/desktop/api/Pdh/nf-pdh-pdhselectdatasourcea)
#### [PdhSetCounterScaleFactor](/windows/desktop/api/Pdh/nf-pdh-pdhsetcounterscalefactor)
#### [PdhSetDefaultRealTimeDataSource](/windows/desktop/api/Pdh/nf-pdh-pdhsetdefaultrealtimedatasource)
#### [PdhSetQueryTimeRange](/windows/desktop/api/Pdh/nf-pdh-pdhsetquerytimerange)
#### [PdhUpdateLog](/windows/desktop/api/Pdh/nf-pdh-pdhupdateloga)
#### [PdhUpdateLogFileCatalog](/windows/desktop/api/Pdh/nf-pdh-pdhupdatelogfilecatalog)
#### [PdhValidatePath](/windows/desktop/api/Pdh/nf-pdh-pdhvalidatepatha)
#### [PdhValidatePathEx](/windows/desktop/api/Pdh/nf-pdh-pdhvalidatepathexa)
#### [PerfAddCounters](/windows/desktop/api/Perflib/nf-perflib-perfaddcounters)
#### [PerfCloseQueryHandle](/windows/desktop/api/Perflib/nf-perflib-perfclosequeryhandle)
#### [PerfCreateInstance](/windows/desktop/api/Perflib/nf-perflib-perfcreateinstance)
#### [PerfDecrementULongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfdecrementulongcountervalue)
#### [PerfDecrementULongLongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfdecrementulonglongcountervalue)
#### [PerfDeleteCounters](/windows/desktop/api/Perflib/nf-perflib-perfdeletecounters)
#### [PerfDeleteInstance](/windows/desktop/api/Perflib/nf-perflib-perfdeleteinstance)
#### [PerfEnumerateCounterSet](/windows/desktop/api/Perflib/nf-perflib-perfenumeratecounterset)
#### [PerfEnumerateCounterSetInstances](/windows/desktop/api/Perflib/nf-perflib-perfenumeratecountersetinstances)
#### [PerfIncrementULongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfincrementulongcountervalue)
#### [PerfIncrementULongLongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfincrementulonglongcountervalue)
#### [PerfOpenQueryHandle](/windows/desktop/api/Perflib/nf-perflib-perfopenqueryhandle)
#### [PerfQueryCounterData](/windows/desktop/api/Perflib/nf-perflib-perfquerycounterdata)
#### [PerfQueryCounterInfo](/windows/desktop/api/Perflib/nf-perflib-perfquerycounterinfo)
#### [PerfQueryCounterSetRegistrationInfo](/windows/desktop/api/Perflib/nf-perflib-perfquerycountersetregistrationinfo)
#### [PerfQueryInstance](/windows/desktop/api/Perflib/nf-perflib-perfqueryinstance)
#### [PerfSetCounterRefValue](/windows/desktop/api/Perflib/nf-perflib-perfsetcounterrefvalue)
#### [PerfSetCounterSetInfo](/windows/desktop/api/Perflib/nf-perflib-perfsetcountersetinfo)
#### [PerfSetULongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfsetulongcountervalue)
#### [PerfSetULongLongCounterValue](/windows/desktop/api/Perflib/nf-perflib-perfsetulonglongcountervalue)
#### [PerfStartProvider](/windows/desktop/api/Perflib/nf-perflib-perfstartprovider)
#### [PerfStartProviderEx](/windows/desktop/api/Perflib/nf-perflib-perfstartproviderex)
#### [PerfStopProvider](/windows/desktop/api/Perflib/nf-perflib-perfstopprovider)
#### [UnloadPerfCounterTextStrings](/windows/desktop/api/Loadperf/nf-loadperf-unloadperfcountertextstringsa)
