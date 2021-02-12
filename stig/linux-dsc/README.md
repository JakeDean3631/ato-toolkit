# Deploy Azure Virtual Machine (Linux) and apply STIG

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fprojchairliftstorageacct.blob.core.windows.net%2Fprojchairliftstoragecontainer%2FmainTemplate.json%3Fsv%3D2019-02-02%26sr%3Dc%26sig%3DxLFf67FDIM4rlnp%252Bd20lyQP7qB%252FpJuPu9RXdSePU0i4%253D%26se%3D2021-02-12T12%253A44%253A40Z%26sp%3Drwdl/createUIDefinitionUri/https%3A%2F%2Fprojchairliftstorageacct.blob.core.windows.net%2Fprojchairliftstoragecontainer%2FcreateUiDefinition.json%3Fsv%3D2019-02-02%26sr%3Dc%26sig%3DxLFf67FDIM4rlnp%252Bd20lyQP7qB%252FpJuPu9RXdSePU0i4%253D%26se%3D2021-02-12T12%253A44%253A40Z%26sp%3Drwdl)
[![Deploy To Azure Gov](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fprojchairliftstorageacct.blob.core.windows.net%2Fprojchairliftstoragecontainer%2FmainTemplate.json%3Fsv%3D2019-02-02%26sr%3Dc%26sig%3DxLFf67FDIM4rlnp%252Bd20lyQP7qB%252FpJuPu9RXdSePU0i4%253D%26se%3D2021-02-12T12%253A44%253A40Z%26sp%3Drwdl/createUIDefinitionUri/https%3A%2F%2Fprojchairliftstorageacct.blob.core.windows.net%2Fprojchairliftstoragecontainer%2FcreateUiDefinition.json%3Fsv%3D2019-02-02%26sr%3Dc%26sig%3DxLFf67FDIM4rlnp%252Bd20lyQP7qB%252FpJuPu9RXdSePU0i4%253D%26se%3D2021-02-12T12%253A44%253A40Z%26sp%3Drwdl)

Use this template to deploy Azure Virtual Machine with select Red Hat Enterprise Linux 7 and CentOS 7 Operating Systems. Template executes automation developed by [ComplianceAsCode](https://github.com/ComplianceAsCode/content) via [Azure Custom Scripts Extension](https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-linux) to apply [STIG](https://public.cyber.mil/stigs/).

If you're new to Azure virtual machines, see:

- [Azure Virtual Machines](https://azure.microsoft.com/services/virtual-machines/)
- [Azure Linux Virtual Machines documentation](https://docs.microsoft.com/azure/virtual-machines/linux/)
- [Template reference](https://docs.microsoft.com/azure/templates/microsoft.compute/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/?resourceType=Microsoft.Compute&pageNumber=1&sort=Popular)

If you're new to template deployment, see:

- [Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)
- [Quickstart: Create a Linux virtual machine using an ARM template](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-template)