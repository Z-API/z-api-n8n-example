# Z-API + n8n — WhatsApp Workflow Example

Bring WhatsApp into your n8n workflows with Z-API. Import this example, configure your instance, and use it as a starting point for your own automations.

![Z-API and n8n workflow example](https://raw.githubusercontent.com/Z-API/z-api-n8n-example/main/imagem.png)

## Prerequisites

- Access to an n8n instance.
- A [Z-API account](https://z-api.io) with an instance connected to WhatsApp.

## Getting Started

### 1. Download the workflow

Download [`exemplo_zapi_n8n.json`](./exemplo_zapi_n8n.json) from this repository.

### 2. Import it into n8n

1. Open n8n and create a new workflow.
2. Open the three-dot menu in the upper-right corner.
3. Select **Import from File…** and choose the downloaded JSON file.

### 3. Configure your instance

Open the **`Constantes`** node and replace the example values with your Z-API instance details.

The node names in this example are in Portuguese. **`Constantes`** means **Constants**.

### 4. Connect the webhook

Open the first node, copy its webhook URL, and configure it in your Z-API instance.

Make sure the webhook URL is reachable by Z-API.

### 5. Test and customize

Test the workflow in n8n and review the execution results. Once the connection is working, adapt the workflow to your use case.

## Resources

- [Z-API Documentation](https://developer.z-api.io)
- [Z-API Website](https://z-api.io)

## Credits

Example contributed by [Kim Tiago Baptista](https://github.com/kimtiago).
