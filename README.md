# oai_core_helm_charts

### deloy oai 5g core with upf-ebpf mode
```bash
helm install oai-core oai-5g-basic/ -n oai
```

> ***NOTE:*** Everything related to ebpf mode in upf is already configured in `oai_core_charts/oai-5g-core/oai-5g-basic/config.yaml` and `oai_core_charts/oai-5g-core/oai-5g-basic/values.yaml`

### deloy oai gnb
```bash
cd oai-5g-ran/
helm install gnb oai-gnb/ -n oai
```

Refer official [OAI Readme](./Deploy%20SA5G%20HC.md) for more details.

