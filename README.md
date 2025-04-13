# Description

A script to poll and fetch Kubernetes based container for 5G-call related KPI data package and Export package to KPIReport for test call results visualization

# How to run the code

Compile the code using the following command:

```bash
g++ -o 5GmetricsDataExporter 5GmetricsDataExporter.cpp .
```

Run the code using the following command:

```bash
./5GmetricsDataExporter <input.json> <output.csv>
```