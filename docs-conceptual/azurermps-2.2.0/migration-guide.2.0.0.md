# <a name="table-of-contents"></a><span data-ttu-id="4b601-101">Innehållsförteckning</span><span class="sxs-lookup"><span data-stu-id="4b601-101">Table of Contents</span></span>
1. [<span data-ttu-id="4b601-102">Borttagning av Force-parametrar</span><span class="sxs-lookup"><span data-stu-id="4b601-102">Removal of Force parameters</span></span>](#removal-of-force-parameters)
2. [<span data-ttu-id="4b601-103">Ändringar för Tag-parametrar</span><span class="sxs-lookup"><span data-stu-id="4b601-103">Change of Tag parameters</span></span>](#change-of-tag-parameters)
3. [<span data-ttu-id="4b601-104">Större ändringar i Storage-cmdletar</span><span class="sxs-lookup"><span data-stu-id="4b601-104">Breaking changes to Storage cmdlets</span></span>](#breaking-changes-to-storage-cmdlets)
4. [<span data-ttu-id="4b601-105">Större ändringar i AD-cmdletar</span><span class="sxs-lookup"><span data-stu-id="4b601-105">Breaking changes to AD cmdlets</span></span>](#breaking-changes-to-ad-cmdlets)

## <a name="removal-of-force-parameters"></a><span data-ttu-id="4b601-106">Borttagning av Force-parametrar</span><span class="sxs-lookup"><span data-stu-id="4b601-106">Removal of Force parameters</span></span>

<span data-ttu-id="4b601-107">I den här uppdateringen har vi tagit bort alla inaktuella `Force`-parametrar från cmdletar och motsvarande varningar om att parametern skulle tas bort i en framtida uppdatering.</span><span class="sxs-lookup"><span data-stu-id="4b601-107">This release, we removed all Obsolete `Force` parameters from cmdlets and the corresponding warnings that the parameter would be removed in a future release.</span></span>

<span data-ttu-id="4b601-108">Följande cmdletar påverkas av den här uppdateringen:</span><span class="sxs-lookup"><span data-stu-id="4b601-108">The following cmdlets are affected by this change:</span></span>

<span data-ttu-id="4b601-109">**ApiManagement**</span><span class="sxs-lookup"><span data-stu-id="4b601-109">**ApiManagement**</span></span>
- <span data-ttu-id="4b601-110">Remove-AzureRmApiManagement</span><span class="sxs-lookup"><span data-stu-id="4b601-110">Remove-AzureRmApiManagement</span></span>
- <span data-ttu-id="4b601-111">Remove-AzureRmApiManagementApi</span><span class="sxs-lookup"><span data-stu-id="4b601-111">Remove-AzureRmApiManagementApi</span></span>
- <span data-ttu-id="4b601-112">Remove-AzureRmApiManagementGroup</span><span class="sxs-lookup"><span data-stu-id="4b601-112">Remove-AzureRmApiManagementGroup</span></span>
- <span data-ttu-id="4b601-113">Remove-AzureRmApiManagementLogger</span><span class="sxs-lookup"><span data-stu-id="4b601-113">Remove-AzureRmApiManagementLogger</span></span>
- <span data-ttu-id="4b601-114">Remove-AzureRmApiManagementOpenIdConnectProvider</span><span class="sxs-lookup"><span data-stu-id="4b601-114">Remove-AzureRmApiManagementOpenIdConnectProvider</span></span>
- <span data-ttu-id="4b601-115">Remove-AzureRmApiManagementOperation</span><span class="sxs-lookup"><span data-stu-id="4b601-115">Remove-AzureRmApiManagementOperation</span></span>
- <span data-ttu-id="4b601-116">Remove-AzureRmApiManagementPolicy</span><span class="sxs-lookup"><span data-stu-id="4b601-116">Remove-AzureRmApiManagementPolicy</span></span>
- <span data-ttu-id="4b601-117">Remove-AzureRmApiManagementProduct</span><span class="sxs-lookup"><span data-stu-id="4b601-117">Remove-AzureRmApiManagementProduct</span></span>
- <span data-ttu-id="4b601-118">Remove-AzureRmApiManagementProperty</span><span class="sxs-lookup"><span data-stu-id="4b601-118">Remove-AzureRmApiManagementProperty</span></span>
- <span data-ttu-id="4b601-119">Remove-AzureRmApiManagementSubscription</span><span class="sxs-lookup"><span data-stu-id="4b601-119">Remove-AzureRmApiManagementSubscription</span></span>
- <span data-ttu-id="4b601-120">Remove-AzureRmApiManagementUser</span><span class="sxs-lookup"><span data-stu-id="4b601-120">Remove-AzureRmApiManagementUser</span></span>

<span data-ttu-id="4b601-121">**Automation**</span><span class="sxs-lookup"><span data-stu-id="4b601-121">**Automation**</span></span>
- <span data-ttu-id="4b601-122">Remove-AzureRmAutomationCertificate</span><span class="sxs-lookup"><span data-stu-id="4b601-122">Remove-AzureRmAutomationCertificate</span></span>
- <span data-ttu-id="4b601-123">Remove-AzureRmAutomationCredential</span><span class="sxs-lookup"><span data-stu-id="4b601-123">Remove-AzureRmAutomationCredential</span></span>
- <span data-ttu-id="4b601-124">Remove-AzureRmAutomationVariable</span><span class="sxs-lookup"><span data-stu-id="4b601-124">Remove-AzureRmAutomationVariable</span></span>
- <span data-ttu-id="4b601-125">Remove-AzureRmAutomationWebhook</span><span class="sxs-lookup"><span data-stu-id="4b601-125">Remove-AzureRmAutomationWebhook</span></span>

<span data-ttu-id="4b601-126">**Batch**</span><span class="sxs-lookup"><span data-stu-id="4b601-126">**Batch**</span></span>
- <span data-ttu-id="4b601-127">Remove-AzureBatchCertificate</span><span class="sxs-lookup"><span data-stu-id="4b601-127">Remove-AzureBatchCertificate</span></span>
- <span data-ttu-id="4b601-128">Remove-AzureBatchComputeNode</span><span class="sxs-lookup"><span data-stu-id="4b601-128">Remove-AzureBatchComputeNode</span></span>
- <span data-ttu-id="4b601-129">Remove-AzureBatchComputeNodeUser</span><span class="sxs-lookup"><span data-stu-id="4b601-129">Remove-AzureBatchComputeNodeUser</span></span>

<span data-ttu-id="4b601-130">**DataFactories**</span><span class="sxs-lookup"><span data-stu-id="4b601-130">**DataFactories**</span></span>
- <span data-ttu-id="4b601-131">Resume-AzureRmDataFactoryPipeline</span><span class="sxs-lookup"><span data-stu-id="4b601-131">Resume-AzureRmDataFactoryPipeline</span></span>
- <span data-ttu-id="4b601-132">Set-AzureRmDataFactoryPipelineActivePeriod</span><span class="sxs-lookup"><span data-stu-id="4b601-132">Set-AzureRmDataFactoryPipelineActivePeriod</span></span>
- <span data-ttu-id="4b601-133">Suspend-AzureRmDataFactoryPipeline</span><span class="sxs-lookup"><span data-stu-id="4b601-133">Suspend-AzureRmDataFactoryPipeline</span></span>

<span data-ttu-id="4b601-134">**DataLakeStore**</span><span class="sxs-lookup"><span data-stu-id="4b601-134">**DataLakeStore**</span></span>
- <span data-ttu-id="4b601-135">Remove-AzureRmDataLakeStoreItemAclEntry</span><span class="sxs-lookup"><span data-stu-id="4b601-135">Remove-AzureRmDataLakeStoreItemAclEntry</span></span>
- <span data-ttu-id="4b601-136">Set-AzureRmDataLakeStoreItemAcl</span><span class="sxs-lookup"><span data-stu-id="4b601-136">Set-AzureRmDataLakeStoreItemAcl</span></span>
- <span data-ttu-id="4b601-137">Set-AzureRmDataLakeStoreItemAclEntry</span><span class="sxs-lookup"><span data-stu-id="4b601-137">Set-AzureRmDataLakeStoreItemAclEntry</span></span>
- <span data-ttu-id="4b601-138">Set-AzureRmDataLakeStoreItemOwner</span><span class="sxs-lookup"><span data-stu-id="4b601-138">Set-AzureRmDataLakeStoreItemOwner</span></span>

<span data-ttu-id="4b601-139">**OperationalInsights**</span><span class="sxs-lookup"><span data-stu-id="4b601-139">**OperationalInsights**</span></span>
- <span data-ttu-id="4b601-140">Remove-AzureRmOperationalInsightsSavedSearch</span><span class="sxs-lookup"><span data-stu-id="4b601-140">Remove-AzureRmOperationalInsightsSavedSearch</span></span>

<span data-ttu-id="4b601-141">**Profil**</span><span class="sxs-lookup"><span data-stu-id="4b601-141">**Profile**</span></span>
- <span data-ttu-id="4b601-142">Remove-AzureRmEnvironment</span><span class="sxs-lookup"><span data-stu-id="4b601-142">Remove-AzureRmEnvironment</span></span>

<span data-ttu-id="4b601-143">**RedisCache**</span><span class="sxs-lookup"><span data-stu-id="4b601-143">**RedisCache**</span></span>
- <span data-ttu-id="4b601-144">Remove-AzureRmRedisCacheDiagnostics</span><span class="sxs-lookup"><span data-stu-id="4b601-144">Remove-AzureRmRedisCacheDiagnostics</span></span>

<span data-ttu-id="4b601-145">**Resurser**</span><span class="sxs-lookup"><span data-stu-id="4b601-145">**Resources**</span></span>
- <span data-ttu-id="4b601-146">Register-AzureRmProviderFeature</span><span class="sxs-lookup"><span data-stu-id="4b601-146">Register-AzureRmProviderFeature</span></span>
- <span data-ttu-id="4b601-147">Register-AzureRmResourceProvider</span><span class="sxs-lookup"><span data-stu-id="4b601-147">Register-AzureRmResourceProvider</span></span>
- <span data-ttu-id="4b601-148">Remove-AzureRmADServicePrincipal</span><span class="sxs-lookup"><span data-stu-id="4b601-148">Remove-AzureRmADServicePrincipal</span></span>
- <span data-ttu-id="4b601-149">Remove-AzureRmPolicyAssignment</span><span class="sxs-lookup"><span data-stu-id="4b601-149">Remove-AzureRmPolicyAssignment</span></span>
- <span data-ttu-id="4b601-150">Remove-AzureRmResourceGroupDeployment</span><span class="sxs-lookup"><span data-stu-id="4b601-150">Remove-AzureRmResourceGroupDeployment</span></span>
- <span data-ttu-id="4b601-151">Remove-AzureRmRoleAssignment</span><span class="sxs-lookup"><span data-stu-id="4b601-151">Remove-AzureRmRoleAssignment</span></span>
- <span data-ttu-id="4b601-152">Stop-AzureRmResourceGroupDeployment</span><span class="sxs-lookup"><span data-stu-id="4b601-152">Stop-AzureRmResourceGroupDeployment</span></span>
- <span data-ttu-id="4b601-153">Unregister-AzureRmResourceProvider</span><span class="sxs-lookup"><span data-stu-id="4b601-153">Unregister-AzureRmResourceProvider</span></span>

<span data-ttu-id="4b601-154">**Storage**</span><span class="sxs-lookup"><span data-stu-id="4b601-154">**Storage**</span></span>
- <span data-ttu-id="4b601-155">Remove-AzureStorageContainerStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="4b601-155">Remove-AzureStorageContainerStoredAccessPolicy</span></span>
- <span data-ttu-id="4b601-156">Remove-AzureStorageQueueStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="4b601-156">Remove-AzureStorageQueueStoredAccessPolicy</span></span>
- <span data-ttu-id="4b601-157">Remove-AzureStorageShareStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="4b601-157">Remove-AzureStorageShareStoredAccessPolicy</span></span>
- <span data-ttu-id="4b601-158">Remove-AzureStorageTableStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="4b601-158">Remove-AzureStorageTableStoredAccessPolicy</span></span>

<span data-ttu-id="4b601-159">**StreamAnalytics**</span><span class="sxs-lookup"><span data-stu-id="4b601-159">**StreamAnalytics**</span></span>
- <span data-ttu-id="4b601-160">Remove-AzureRmStreamAnalyticsFunction</span><span class="sxs-lookup"><span data-stu-id="4b601-160">Remove-AzureRmStreamAnalyticsFunction</span></span>
- <span data-ttu-id="4b601-161">Remove-AzureRmStreamAnalyticsInput</span><span class="sxs-lookup"><span data-stu-id="4b601-161">Remove-AzureRmStreamAnalyticsInput</span></span>
- <span data-ttu-id="4b601-162">Remove-AzureRmStreamAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="4b601-162">Remove-AzureRmStreamAnalyticsJob</span></span>
- <span data-ttu-id="4b601-163">Remove-AzureRmStreamAnalyticsOutput</span><span class="sxs-lookup"><span data-stu-id="4b601-163">Remove-AzureRmStreamAnalyticsOutput</span></span>

<span data-ttu-id="4b601-164">**Tag**</span><span class="sxs-lookup"><span data-stu-id="4b601-164">**Tag**</span></span>
- <span data-ttu-id="4b601-165">Remove-AzureRmTag</span><span class="sxs-lookup"><span data-stu-id="4b601-165">Remove-AzureRmTag</span></span>

<br>

<span data-ttu-id="4b601-166">Om du har ett skript som använder någon av ovanstående cmdletar så kan den stora ändringen åtgärdas genom att helt enkelt ta bort parametern `Force`.</span><span class="sxs-lookup"><span data-stu-id="4b601-166">If you have a script that uses any of the above cmdlets, the breaking change can be fixed by simply removing the `Force` parameter.</span></span>

```powershell
# Old
New-AzureRmResourceGroup -Name $resourceGroupName -Location $location -Force

# New
New-AzureRmResourceGroup -Name $resourceGroupName -Location $location
```

<br>

## <a name="change-of-tag-parameters"></a><span data-ttu-id="4b601-167">Ändringar för Tag-parametrar</span><span class="sxs-lookup"><span data-stu-id="4b601-167">Change of Tag parameters</span></span>

<span data-ttu-id="4b601-168">I den här uppdateringen har parameternamnet `Tags` ändrats till `Tag` och typen har ändrats från `Hashtable[]` till `Hashtable`, vilket har ändrat formatet för nyckel/värde-paret.</span><span class="sxs-lookup"><span data-stu-id="4b601-168">This release, the `Tags` parameter name was changed to `Tag`, and the type was changed from `Hashtable[]` to `Hashtable`, changing the format of the key-value pairings.</span></span>

<span data-ttu-id="4b601-169">Tidigare representerades varje post i `Hashtable[]` av ett enda nyckel/värde-par:</span><span class="sxs-lookup"><span data-stu-id="4b601-169">Previously, each entry in the `Hashtable[]` represented a single key-value pairing:</span></span>

```powershell
$tags = @{ Name = "test1"; Value = "testval1" }, @{ Name = "test2", Value = "testval2" }
$tags[0].Name  # Key for the first entry, "test1"
$tags[0].Value # Value for the first entry, "testval1"
$tags[1].Name  # Key for the second entry, "test2"
$tags[1].Value # Value for the second entry, "testval2"
```

<span data-ttu-id="4b601-170">Nu behövs inte längre `Name` och `Value`, vilket gör att nyckel/värde-par kan skapas genom att tilldela `Key = "Value"` i `Hashtable`:</span><span class="sxs-lookup"><span data-stu-id="4b601-170">Now, `Name` and `Value` are no longer necessary, allowing for key-value pairings to be created by assigning `Key = "Value"` in the `Hashtable`:</span></span>

```powershell
$tag = @{ test1 = "testval1"; test2 = "testval2" }
$tag["test1"] # Gets the value associated with the key "test1"
$tag["test2"] # Gets the value associated with the key "test2"
```

<span data-ttu-id="4b601-171">Följande cmdletar påverkas av den här uppdateringen:</span><span class="sxs-lookup"><span data-stu-id="4b601-171">The following cmdlets are affected by this change:</span></span>

<span data-ttu-id="4b601-172">**Batch**</span><span class="sxs-lookup"><span data-stu-id="4b601-172">**Batch**</span></span>
- <span data-ttu-id="4b601-173">Get-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-173">Get-AzureRmBatchAccount</span></span>
- <span data-ttu-id="4b601-174">New-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-174">New-AzureRmBatchAccount</span></span>
- <span data-ttu-id="4b601-175">Set-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-175">Set-AzureRmBatchAccount</span></span>

<span data-ttu-id="4b601-176">**Compute**</span><span class="sxs-lookup"><span data-stu-id="4b601-176">**Compute**</span></span>
- <span data-ttu-id="4b601-177">New-AzureRmVM</span><span class="sxs-lookup"><span data-stu-id="4b601-177">New-AzureRmVM</span></span>
- <span data-ttu-id="4b601-178">Update-AzureRmVM</span><span class="sxs-lookup"><span data-stu-id="4b601-178">Update-AzureRmVM</span></span>

<span data-ttu-id="4b601-179">**DataLakeAnalytics**</span><span class="sxs-lookup"><span data-stu-id="4b601-179">**DataLakeAnalytics**</span></span>
- <span data-ttu-id="4b601-180">New-AzureRmDataLakeAnalyticsAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-180">New-AzureRmDataLakeAnalyticsAccount</span></span>
- <span data-ttu-id="4b601-181">Set-AzureRmDataLakeAnalyticsAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-181">Set-AzureRmDataLakeAnalyticsAccount</span></span>

<span data-ttu-id="4b601-182">**DataLakeStore**</span><span class="sxs-lookup"><span data-stu-id="4b601-182">**DataLakeStore**</span></span>
- <span data-ttu-id="4b601-183">New-AzureRmDataLakeStoreAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-183">New-AzureRmDataLakeStoreAccount</span></span>
- <span data-ttu-id="4b601-184">Set-AzureRmDataLakeStoreAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-184">Set-AzureRmDataLakeStoreAccount</span></span>

<span data-ttu-id="4b601-185">**DNS**</span><span class="sxs-lookup"><span data-stu-id="4b601-185">**Dns**</span></span>
- <span data-ttu-id="4b601-186">New-AzureRmDnsZone</span><span class="sxs-lookup"><span data-stu-id="4b601-186">New-AzureRmDnsZone</span></span>
- <span data-ttu-id="4b601-187">Set-AzureRmDnsZone</span><span class="sxs-lookup"><span data-stu-id="4b601-187">Set-AzureRmDnsZone</span></span>

<span data-ttu-id="4b601-188">**KeyVault**</span><span class="sxs-lookup"><span data-stu-id="4b601-188">**KeyVault**</span></span>
- <span data-ttu-id="4b601-189">Get-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="4b601-189">Get-AzureRmKeyVault</span></span>
- <span data-ttu-id="4b601-190">New-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="4b601-190">New-AzureRmKeyVault</span></span>

<span data-ttu-id="4b601-191">**Nätverk**</span><span class="sxs-lookup"><span data-stu-id="4b601-191">**Network**</span></span>
- <span data-ttu-id="4b601-192">New-AzureRmApplicationGateway</span><span class="sxs-lookup"><span data-stu-id="4b601-192">New-AzureRmApplicationGateway</span></span>
- <span data-ttu-id="4b601-193">New-AzureRmExpressRouteCircuit</span><span class="sxs-lookup"><span data-stu-id="4b601-193">New-AzureRmExpressRouteCircuit</span></span>
- <span data-ttu-id="4b601-194">New-AzureRmLoadBalancer</span><span class="sxs-lookup"><span data-stu-id="4b601-194">New-AzureRmLoadBalancer</span></span>
- <span data-ttu-id="4b601-195">New-AzureRmLocalNetworkGateway</span><span class="sxs-lookup"><span data-stu-id="4b601-195">New-AzureRmLocalNetworkGateway</span></span>
- <span data-ttu-id="4b601-196">New-AzureRmNetworkInterface</span><span class="sxs-lookup"><span data-stu-id="4b601-196">New-AzureRmNetworkInterface</span></span>
- <span data-ttu-id="4b601-197">New-AzureRmNetworkSecurityGroup</span><span class="sxs-lookup"><span data-stu-id="4b601-197">New-AzureRmNetworkSecurityGroup</span></span>
- <span data-ttu-id="4b601-198">New-AzureRmPublicIpAddress</span><span class="sxs-lookup"><span data-stu-id="4b601-198">New-AzureRmPublicIpAddress</span></span>
- <span data-ttu-id="4b601-199">New-AzureRmRouteTable</span><span class="sxs-lookup"><span data-stu-id="4b601-199">New-AzureRmRouteTable</span></span>
- <span data-ttu-id="4b601-200">New-AzureRmVirtualNetwork</span><span class="sxs-lookup"><span data-stu-id="4b601-200">New-AzureRmVirtualNetwork</span></span>
- <span data-ttu-id="4b601-201">New-AzureRmVirtualNetworkGateway</span><span class="sxs-lookup"><span data-stu-id="4b601-201">New-AzureRmVirtualNetworkGateway</span></span>
- <span data-ttu-id="4b601-202">New-AzureRmVirtualNetworkGatewayConnection</span><span class="sxs-lookup"><span data-stu-id="4b601-202">New-AzureRmVirtualNetworkGatewayConnection</span></span>
- <span data-ttu-id="4b601-203">New-AzureRmVirtualNetworkPeering</span><span class="sxs-lookup"><span data-stu-id="4b601-203">New-AzureRmVirtualNetworkPeering</span></span>

<span data-ttu-id="4b601-204">**Resurser**</span><span class="sxs-lookup"><span data-stu-id="4b601-204">**Resources**</span></span>
- <span data-ttu-id="4b601-205">Find-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="4b601-205">Find-AzureRmResource</span></span>
- <span data-ttu-id="4b601-206">Find-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="4b601-206">Find-AzureRmResourceGroup</span></span>
- <span data-ttu-id="4b601-207">New-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="4b601-207">New-AzureRmResource</span></span>
- <span data-ttu-id="4b601-208">New-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="4b601-208">New-AzureRmResourceGroup</span></span>
- <span data-ttu-id="4b601-209">Set-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="4b601-209">Set-AzureRmResource</span></span>
- <span data-ttu-id="4b601-210">Set-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="4b601-210">Set-AzureRmResourceGroup</span></span>

<span data-ttu-id="4b601-211">**SQL**</span><span class="sxs-lookup"><span data-stu-id="4b601-211">**SQL**</span></span>
- <span data-ttu-id="4b601-212">New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="4b601-212">New-AzureRmSqlDatabase</span></span>
- <span data-ttu-id="4b601-213">New-AzureRmSqlDatabaseCopy</span><span class="sxs-lookup"><span data-stu-id="4b601-213">New-AzureRmSqlDatabaseCopy</span></span>
- <span data-ttu-id="4b601-214">New-AzureRmSqlDatabaseSecondary</span><span class="sxs-lookup"><span data-stu-id="4b601-214">New-AzureRmSqlDatabaseSecondary</span></span>
- <span data-ttu-id="4b601-215">New-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="4b601-215">New-AzureRmSqlElasticPool</span></span>
- <span data-ttu-id="4b601-216">New-AzureRmSqlServer</span><span class="sxs-lookup"><span data-stu-id="4b601-216">New-AzureRmSqlServer</span></span>
- <span data-ttu-id="4b601-217">Set-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="4b601-217">Set-AzureRmSqlDatabase</span></span>
- <span data-ttu-id="4b601-218">Set-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="4b601-218">Set-AzureRmSqlElasticPool</span></span>
- <span data-ttu-id="4b601-219">Set-AzureRmSqlServer</span><span class="sxs-lookup"><span data-stu-id="4b601-219">Set-AzureRmSqlServer</span></span>

<span data-ttu-id="4b601-220">**Storage**</span><span class="sxs-lookup"><span data-stu-id="4b601-220">**Storage**</span></span>
- <span data-ttu-id="4b601-221">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-221">New-AzureRmStorageAccount</span></span>
- <span data-ttu-id="4b601-222">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="4b601-222">Set-AzureRmStorageAccount</span></span>

<span data-ttu-id="4b601-223">**TrafficManager**</span><span class="sxs-lookup"><span data-stu-id="4b601-223">**TrafficManager**</span></span>
- <span data-ttu-id="4b601-224">New-AzureRmTrafficManagerProfile</span><span class="sxs-lookup"><span data-stu-id="4b601-224">New-AzureRmTrafficManagerProfile</span></span>

<br>

<span data-ttu-id="4b601-225">Om du har ett skript som använder någon av ovanstående cmdletar så kan den stora ändringen åtgärdas genom att ändra parametern `Tags` till `Tag` samt ändra `Tag` till det nya formatet.</span><span class="sxs-lookup"><span data-stu-id="4b601-225">If you have a script that uses any of the above cmdlets, the breaking change can be fixed by changing the `Tags` parameter to `Tag`, as well as changing the `Tag` to the new format.</span></span>

```powershell
# Old
New-AzureRmResourceGroup -Name $resourceGroupName -Location -location -Tags @{ Name = "testtag"; Value = "testval" }

# New
New-AzureRmResourceGroup -Name $resourceGroupName -Location -location -Tag @{ testtag = "testval" }
```

<br>

## <a name="breaking-changes-to-storage-cmdlets"></a><span data-ttu-id="4b601-226">Större ändringar i Storage-cmdletar</span><span class="sxs-lookup"><span data-stu-id="4b601-226">Breaking changes to Storage cmdlets</span></span>

<span data-ttu-id="4b601-227">Följande cmdletar påverkades av den här uppdateringen:</span><span class="sxs-lookup"><span data-stu-id="4b601-227">The following cmdlets were affected this release:</span></span>

<span data-ttu-id="4b601-228">**Get-AzureRmStorageAccountKey**</span><span class="sxs-lookup"><span data-stu-id="4b601-228">**Get-AzureRmStorageAccountKey**</span></span>
- <span data-ttu-id="4b601-229">Cmdleten returnerar nu en lista över nycklar i stället för ett objekt med egenskaper för varje nyckel</span><span class="sxs-lookup"><span data-stu-id="4b601-229">The cmdlet now returns a list of keys, rather than an object with properties for each key</span></span>

```powershell
# Old
$key = (Get-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).Key1

# New
$key = (Get-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName)[0].Value
```

<span data-ttu-id="4b601-230">**New-AzureRmStorageAccountKey**</span><span class="sxs-lookup"><span data-stu-id="4b601-230">**New-AzureRmStorageAccountKey**</span></span>
- <span data-ttu-id="4b601-231">`StorageAccountRegenerateKeyResponse`-fältet i den här cmdletens utdata har bytt namn till `StorageAccountListKeysResults`, som nu är en lista över nycklar i stället för ett objekt med egenskaper för varje nyckel</span><span class="sxs-lookup"><span data-stu-id="4b601-231">`StorageAccountRegenerateKeyResponse` field in output of this cmdlet is renamed to `StorageAccountListKeysResults`, which is now a list of keys rather than an object with properties for each key</span></span>

```powershell
# Old
$key = (New-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).StorageAccountKeys.Key1

# New
$key = (New-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).Keys[0].Value
```

<span data-ttu-id="4b601-232">**New/Get/Set-AzureRmStorageAccount**</span><span class="sxs-lookup"><span data-stu-id="4b601-232">**New/Get/Set-AzureRmStorageAccount**</span></span>
- <span data-ttu-id="4b601-233">`AccountType`-fältet i den här cmdletens utdata har bytt namn till `Sku.Name`</span><span class="sxs-lookup"><span data-stu-id="4b601-233">`AccountType` field in output of this cmdlet is renamed to `Sku.Name`</span></span>
- <span data-ttu-id="4b601-234">Typ av utdata för blobar/tabeller/köer/filer för primära slutpunkter/sekundära slutpunkter har ändrats från `Uri` till `String`</span><span class="sxs-lookup"><span data-stu-id="4b601-234">Output type for PrimaryEndpoints/Secondary endpoints blob/table/queue/file changed from `Uri` to `String`</span></span>

```powershell
# Old
$accountType = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).AccountType

# New
$accountType = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).Sku.Name
```

```powershell
# Old 
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.ToString()
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.AbsolutePath

# New
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.ToString()
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob
```

<br>

## <a name="breaking-changes-to-ad-cmdlets"></a><span data-ttu-id="4b601-235">Större ändringar i AD-cmdletar</span><span class="sxs-lookup"><span data-stu-id="4b601-235">Breaking changes to AD cmdlets</span></span>

<span data-ttu-id="4b601-236">Följande cmdletar påverkades av den här uppdateringen:</span><span class="sxs-lookup"><span data-stu-id="4b601-236">The following cmdlets were affected this release:</span></span>

<span data-ttu-id="4b601-237">**Get-AzureRMADServicePrincipal**</span><span class="sxs-lookup"><span data-stu-id="4b601-237">**Get-AzureRMADServicePrincipal**</span></span>
- <span data-ttu-id="4b601-238">`ServicePrincipalName`-fältet i den här cmdletens utdata har bytt namn till `ServicePrincipalNames` och är nu en samling.</span><span class="sxs-lookup"><span data-stu-id="4b601-238">`ServicePrincipalName` field in output of this cmdlet is renamed to `ServicePrincipalNames` and is now a collection.</span></span> <span data-ttu-id="4b601-239">Nu visar den även `ApplicationId` som ett av tjänstens huvudnamn, tillsammans med identifierar-URI.</span><span class="sxs-lookup"><span data-stu-id="4b601-239">It now displays `ApplicationId` also as one of the SPN, along with the identifierUri.</span></span>

```powershell
# Old
$servicePrincipals = Get-AzureRmADServicePrincipal -SearchString $displayName
$spn = $servicePrincipals[0].ServicePrincipalName

# New
$servicePrincipals = Get-AzureRmADServicePrincipal -SearchString $displayName
$spn = $servicePrincipals[0].ServicePrincipalNames[0]
```

<span data-ttu-id="4b601-240">**Get-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="4b601-240">**Get-AzureRmADApplication**</span></span>
- <span data-ttu-id="4b601-241">Parametern `ApplicationObjectId` har bytt namn till `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="4b601-241">Parameter `ApplicationObjectId` is renamed to `ObjectId`.</span></span>
- <span data-ttu-id="4b601-242">I den här cmdletens utdata har `ApplicationObjectId` bytt namn till `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="4b601-242">In output of this cmdlet, `ApplicationObjectId` is renamed to `ObjectId`.</span></span>

```powershell
# Old
$app = Get-AzureRmADApplication -ApplicationObjectId $applicationObjectId
$objectId = $app.ApplicationObjectId

# New
$app = Get-AzureRmADApplication -ObjectId $objectId
$objectId = $app.ObjectId
```

<span data-ttu-id="4b601-243">**Remove-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="4b601-243">**Remove-AzureRmADApplication**</span></span>
- <span data-ttu-id="4b601-244">Parametern `ApplicationObjectId` har bytt namn till `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="4b601-244">Parameter `ApplicationObjectId` is renamed to `ObjectId`.</span></span>

```powershell
# Old
$app = Remove-AzureRmADApplication -ApplicationObjectId $applicationObjectId -Force

# New
$app = Remove-AzureRmADApplication -ObjectId $objectId -Force
```

<span data-ttu-id="4b601-245">**New-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="4b601-245">**New-AzureRmADApplication**</span></span>
- <span data-ttu-id="4b601-246">I den här cmdletens utdata har `ApplicationObjectId` bytt namn till `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="4b601-246">In output of this cmdlet, `ApplicationObjectId` is renamed to `ObjectId`.</span></span>
- <span data-ttu-id="4b601-247">Parametrarna `KeyValue`, `KeyUsage`, `KeyType` har tagits bort.</span><span class="sxs-lookup"><span data-stu-id="4b601-247">`KeyValue`, `KeyUsage`, `KeyType` parameters are removed.</span></span>

```powershell
# Old
$app = New-AzureRmADApplication -DisplayName $displayName -HomePage $homePage -IdentifierUris $identifierUris -KeyValue $kv -KeyType $kt -KeyUsage $ku
$id = $app.ApplicationObjectId

# New
$app = New-AzureRmADApplication -DisplayName $displayName -HomePage $homePage -IdentifierUris $identifierUris
$id = $app.ObjectId
New-AzureRmADAppCredential -ObjectId $id -Password $kv
```

<span data-ttu-id="4b601-248">**Get-AzureRmADGroup**</span><span class="sxs-lookup"><span data-stu-id="4b601-248">**Get-AzureRmADGroup**</span></span>
- <span data-ttu-id="4b601-249">`Mail`-fältet tas bort från utdata.</span><span class="sxs-lookup"><span data-stu-id="4b601-249">`Mail` field is removed from the output.</span></span>

<span data-ttu-id="4b601-250">**Get-AzureRmADUser**</span><span class="sxs-lookup"><span data-stu-id="4b601-250">**Get-AzureRmADUser**</span></span>
- <span data-ttu-id="4b601-251">`Mail`-fältet tas bort från utdata.</span><span class="sxs-lookup"><span data-stu-id="4b601-251">`Mail` field is removed from the output.</span></span>

<span data-ttu-id="4b601-252">**New-AzureRmADServicePrincipal**</span><span class="sxs-lookup"><span data-stu-id="4b601-252">**New-AzureRmADServicePrincipal**</span></span>
- <span data-ttu-id="4b601-253">Parametern `DisableAccount` har tagits bort.</span><span class="sxs-lookup"><span data-stu-id="4b601-253">Removed `DisableAccount` parameter.</span></span>

```powershell
# Old
$servicePrincipal = New-AzureRmADServicePrincipal -DisplayName $displayName -Password $password -DisableAccount true

# New
$servicePrincipal = New-AzureRmADServicePrincipal -DisplayName $displayName -Password $password
Remove-AzureRmADServicePrincipal -ObjectId $servicePrincipal.ObjectId
```