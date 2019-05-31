### FHIR EI Connector

The FHIR [Connector](https://docs.wso2.com/display/EI650/Working+with+Connectors) allows you to work with resources in FHIR are the modular components of FHIR. The connector uses the FHIR RESTFul Api  to interact with FHIR.

## Compatibility

| Connector version | Supported FHIR version | Supported WSO2 ESB/EI version |
| ------------- | ------------- | ------------- |
| [1.0.2](https://github.com/wso2-extensions/esb-connector-fhir/tree/org.wso2.carbon.connector.fhir-1.0.2) | 4.0.0 | EI 6.5.0 |


## Getting started

#### Download and install the connector

1. Download the connector from the [WSO2 Store](https://store.wso2.com/store/assets/esbconnector/details/b4b29e84-37ad-4c2d-99d0-5a2a3ab4bc52) by clicking the Download Connector button.
2. Then you can follow this [Documentation](https://docs.wso2.com/display/EI650/Working+with+Connectors+via+the+Management+Console) to add and enable the connector via the Management Console in your EI instance.
3. For more information on using connectors and their operations in your EI configurations, see [Using a Connector](https://docs.wso2.com/display/EI650/Using+a+Connector).
4. If you want to work with connectors via EI tooling, see [Working with Connectors via Tooling](https://docs.wso2.com/display/EI650/Working+with+Connectors+via+Tooling).

## Building From the Source

Follow the steps given below to build the FHIR connector from the source code:

1. Get a clone or download the source from [Github](https://github.com/wso2-extensions/esb-connector-fhir).
2. Run the following Maven command from the `esb-connector-fhir` directory: `mvn clean install`.
3. The FHIR connector zip file is created in the `esb-connector-fhir/target` directory

## How You Can Contribute

As an open source project, WSO2 extensions welcome contributions from the community.
Check the [issue tracker](https://github.com/wso2-extensions/esb-connector-fhir/issues) for open issues that interest you. We look forward to receiving your contributions.