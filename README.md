# Survey of MoErging Methods

Paper list accompanying <br> [A Survey on Model MoErging: Recycling and Routing
Among Specialized Experts for Collaborative Learning](https://www.arxiv.org/pdf/2408.07057)

### AdapterFusion

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Private     | Target          | Step              | Module            | Dense            | Output             | In-Distribution| Full        |

### AdapterSoup

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Custom          | Private     | None            | Task              | Model             | Sparse           | Parameter          | Out-of-Distribution | Few-Shot    |

### Airoboros and LlamaIndex

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Multiple        | Private     | None            | Example           | Model             | Sparse           | None               | Multiple       | Zero-Shot   |

### Arrow

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Private     | None            | Step              | Module            | Sparse           | Parameter          | Out-of-Distribution | Zero-Shot   |

### Branch-Train-Mix

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Shared      | Expert          | Step              | Module            | Sparse           | Output             | In-Distribution| Multiple    |

### CALM

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Multiple    | Multiple        | Task              | N/A               | None             | Output             | Multiple       | Full        |

### Co-LLM

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Custom          | Private     | Target          | Step              | Model             | Sparse           | None               | In-Distribution| Full        |

### Dynamic Adapter Merging

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Custom          | Private     | None            | Example           | Model             | Dense            | Parameter          | In-Distribution| Zero-Shot   |

### LoraHub

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Private     | Target          | Task              | Model             | Sparse           | Parameter          | Out-of-Distribution | Few-Shot    |

### LoraRetriever

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Shared      | Expert          | Example           | Model             | Sparse           | Multiple           | Multiple       | Full        |

### LoRA-Flow

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Private     | Target          | Step              | Module            | Dense            | Output             | Out-of-Distribution | Few-Shot    |

### MeteoRA

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Shared      | Expert          | Step              | Module            | Sparse           | Output             | In-Distribution| Full        |

### MixDA

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Custom          | Private     | Target          | Example           | Module            | Dense            | Output             | In-Distribution| Full        |

### Mixture of LoRA Experts (MoLE)

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Private     | Target          | Step              | Module            | Dense            | Output             | Multiple       | Few-Shot    |

### Mo’LoRA

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Custom          | Private     | None            | Example           | Model             | Dense            | Parameter          | Out-of-Distribution | Zero-Shot   |

### PEMT

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Custom          | Private     | Target          | Task              | Module            | Dense            | Output             | Out-of-Distribution | Multiple    |

### PHATGOOSE

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Custom          | Private     | None            | Step              | Module            | Sparse           | Output             | Out-of-Distribution | Zero-Shot   |

### PWE MoE

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Shared      | Expert          | N/A               | Module            | Dense            | Parameter          | In-Distribution| Full        |

### Retrieval of Experts

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Custom          | Private     | None            | Task              | Model             | Sparse           | None               | Out-of-Distribution | Zero-Shot   |

### RouteLLM

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Private     | Multiple        | Example           | Model             | Sparse           | None               | Multiple       | Zero-Shot   |

### Routoo

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Private     | Multiple        | Example           | Model             | Sparse           | None               | Out-of-Distribution | Few-Shot    |

### Token-Level Adaptation of LoRA Adapters

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Custom          | Private     | None            | Step              | Model             | Dense            | Parameter          | In-Distribution| Zero-Shot   |

### Twin-Merging

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Shared      | Target          | Example           | Model             | Dense            | Parameter          | Multiple       | Full        |

### Weight-Ensembling MoE

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|----------------|-------------|
| Standard        | Private     | Target          | Example           | Module            | Dense            | Parameter          | Multiple       | Zero-Shot   |

### What the Weight?

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Multiple    | Multiple        | Example           | Module            | Sparse           | Multiple           | Out-of-Distribution | Zero-Shot   |

### Zooter

| Expert Training | Expert Data | Routing Dataset | Input Granularity | Depth Granularity | Expert Selection | Expert Aggregation | Generalization     | User Dataset |
|-----------------|-------------|-----------------|-------------------|-------------------|------------------|--------------------|--------------------|-------------|
| Standard        | Private     | General         | Example           | Model             | Sparse           | None               | Out-of-Distribution | Zero-Shot   |


