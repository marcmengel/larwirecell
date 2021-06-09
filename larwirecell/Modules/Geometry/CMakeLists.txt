#add_subdirectory(tools)

art_make( MODULE_LIBRARIES larcorealg_Geometry
                           larcore_Geometry_Geometry_service
                           lardataobj_Simulation
                           lardata_Utilities
                           larevt_Filters
                           lardataobj_RawData
                           larevt_CalibrationDBI_Providers
                           art::Framwork_Core
                           art::Framework_Principal
                           art::Framework_Services_Registry
                           art::Framework_Services_System_FileCatalogMetadata_service art::Framework_Services_System_FloatingPointControl_service art::Framework_Services_System_TriggerNamesService_service
                           art::Framework_Services_System_FloatingPointControl_service
                           art_root_io::TFileService_service_plugin
                           art_Persistency_Common
                           art_Persistency_Provenance
                           art_Utilities
                           canvas
                           messagefacility::MF_MessageLogger
                           messagefacility::headers
                           fhiclcpp::fhiclcpp fhiclcpp::types
                           ${CETLIB}
                           cetlib_except
                           
                           ${ROOT_GEOM}
                           ${ROOT_XMLIO}
                           ${ROOT_GDML}
                           ${ROOT_BASIC_LIB_LIST}
        )

#install_headers()
# install_fhicl()
install_source()
