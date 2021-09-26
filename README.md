# Phyllo Postman Collections
Welcome to the Postman Collections Quickstart Guide! If you're looking for a quick and easy way to get started with the Phyllo API with no additional code, this is the place for you. [Postman](https://www.getpostman.com/product/api-client) is a great tool that allows users explore API functionality by manually sending API requests and receiving responses. We have created a collection of pre-populated HTTP requests that can be sent to the Phyllo API. This quickstart is a step-by-step guide that will get you up and running with Postman and the Phyllo’s Postman [collection](https://learning.postman.com/docs/postman/collections/intro-to-collections/) to enable you for ad-hoc exploration and testing.

If you are looking for a more in-depth guide and reference for the Phyllo API, please refer to the [Phyllo API documentation](https://docs.getphyllo.com).

![phyllo-postman-overview](/images/phyllo-postman-overview.png)

## Getting started
Follow these steps to quickly get started with the [Phyllo API](https://docs.getphyllo.com):

1. To request access to the [Phyllo API](https://docs.getphyllo.com), please contact contact@getphyllo.com. Phyllo will email you API Keys.
2. Download and install the [Postman app](https://www.getpostman.com/downloads/)
3. Install the Phyllo Postman Collection. Click the "Run in Postman" button below to install the Phyllo collection!
  

    [![Run in Postman](https://run.pstmn.io/button.svg)](https://god.postman.co/run-collection/15154090-7bfc0733-4f52-41df-8ec9-70f2042aa9c6?action=collection%2Ffork&collection-url=entityId%3D15154090-7bfc0733-4f52-41df-8ec9-70f2042aa9c6%26entityType%3Dcollection#?env%5BPhyllo%20Sandbox%5D=W3sia2V5IjoiQkFTRV9VUkwiLCJ2YWx1ZSI6Imh0dHBzOi8vYXBpLXNhbmRib3guZ2V0cGh5bGxvLmNvbSIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiQ0xJRU5UX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkNMSUVOVF9TRUNSRVQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiU0RLX1RPS0VOIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IlVTRVJfSUQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiRVhURVJOQUxfSUQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiV09SS19QTEFURk9STV9JRCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJDT05URU5UX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkNPTlRFTlRfR1JPVVBfSUQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiUFJPRklMRV9JRCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJBQ0NPVU5UX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IklOQ09NRV9GUk9NX0RBVEUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiSU5DT01FX1RPX0RBVEUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiUkVQVVRBVElPTl9GUk9NX0RBVEUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiUkVQVVRBVElPTl9UT19EQVRFIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IkxJTUlUIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6Ik9GRlNFVCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZX0seyJrZXkiOiJXRUJIT09LX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IllPVVRVQkVfV09SS1BMQVRGT1JNX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IklOU1RBR1JBTV9XT1JLUExBVEZPUk1fSUQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiRkFDRUJPT0tfV09SS1BMQVRGT1JNX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6IlRXSVRURVJfV09SS1BMQVRGT1JNX0lEIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfV0=)

4. Once both the collection and the environment variables are imported into Postman, see the [Configuration](https://github.com/getphyllo/phyllo-postman#configuration) section on how to correctly configure API keys with the collection.

### Configuration
The Phyllo Postman collection uses [Postman environment variables](https://learning.getpostman.com/docs/postman/environments_and_globals/intro_to_environments_and_globals/) to simplify each API request. More information on managing Postman environments can be found at [Setting up an environment with variables](https://learning.getpostman.com/docs/postman/environments_and_globals/manage_environments/).

![phyllo-postman-configuration](/images/phyllo-postman-config.png)

1. Select the `Phyllo Sandbox` environment in the top right corner
2. Click the `eye` icon to open the environment settings
3. Copy in your Phyllo API keys into each field:
  - `CLIENT_ID`
  - `CLIENT_SECRET`
4. Save your changes and start making Phyllo API requests!

