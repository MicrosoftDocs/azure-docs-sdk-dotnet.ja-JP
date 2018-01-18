<Type Name="AppServiceEnvironmentResourceInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner">
  <TypeSignature Language="C#" Value="public class AppServiceEnvironmentResourceInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceEnvironmentResourceInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceEnvironmentResourceInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentResourceInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="70dac-101">App Service 環境の ARM リソースです。</span><span class="sxs-lookup"><span data-stu-id="70dac-101">App Service Environment ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentResourceInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70dac-102">AppServiceEnvironmentResourceInner クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="70dac-102">Initializes a new instance of the AppServiceEnvironmentResourceInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentResourceInner (string appServiceEnvironmentResourceName, string appServiceEnvironmentResourceLocation, Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile virtualNetwork, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; workerPools, string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt; status = null, string vnetName = null, string vnetResourceGroupName = null, string vnetSubnetName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode = null, string multiSize = null, Nullable&lt;int&gt; multiRoleCount = null, Nullable&lt;int&gt; ipsslAddressCount = null, string databaseEdition = null, string databaseServiceObjective = null, Nullable&lt;int&gt; upgradeDomains = null, string subscriptionId = null, string dnsSuffix = null, string lastAction = null, string lastActionResult = null, string allowedMultiSizes = null, string allowedWorkerSizes = null, Nullable&lt;int&gt; maximumNumberOfMachines = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; vipMappings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt; environmentCapacities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; networkAccessControlList = null, Nullable&lt;bool&gt; environmentIsHealthy = null, string environmentStatus = null, string resourceGroup = null, Nullable&lt;int&gt; frontEndScaleFactor = null, Nullable&lt;int&gt; defaultFrontEndScaleFactor = null, string apiManagementAccountId = null, Nullable&lt;bool&gt; suspended = null, Nullable&lt;bool&gt; dynamicCacheEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; clusterSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string appServiceEnvironmentResourceName, string appServiceEnvironmentResourceLocation, class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile virtualNetwork, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; workerPools, string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt; status, string vnetName, string vnetResourceGroupName, string vnetSubnetName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode, string multiSize, valuetype System.Nullable`1&lt;int32&gt; multiRoleCount, valuetype System.Nullable`1&lt;int32&gt; ipsslAddressCount, string databaseEdition, string databaseServiceObjective, valuetype System.Nullable`1&lt;int32&gt; upgradeDomains, string subscriptionId, string dnsSuffix, string lastAction, string lastActionResult, string allowedMultiSizes, string allowedWorkerSizes, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfMachines, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; vipMappings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt; environmentCapacities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; networkAccessControlList, valuetype System.Nullable`1&lt;bool&gt; environmentIsHealthy, string environmentStatus, string resourceGroup, valuetype System.Nullable`1&lt;int32&gt; frontEndScaleFactor, valuetype System.Nullable`1&lt;int32&gt; defaultFrontEndScaleFactor, string apiManagementAccountId, valuetype System.Nullable`1&lt;bool&gt; suspended, valuetype System.Nullable`1&lt;bool&gt; dynamicCacheEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; clusterSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.#ctor(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (appServiceEnvironmentResourceName As String, appServiceEnvironmentResourceLocation As String, virtualNetwork As VirtualNetworkProfile, workerPools As IList(Of WorkerPool), Optional location As String = null, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of HostingEnvironmentStatus) = null, Optional vnetName As String = null, Optional vnetResourceGroupName As String = null, Optional vnetSubnetName As String = null, Optional internalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode) = null, Optional multiSize As String = null, Optional multiRoleCount As Nullable(Of Integer) = null, Optional ipsslAddressCount As Nullable(Of Integer) = null, Optional databaseEdition As String = null, Optional databaseServiceObjective As String = null, Optional upgradeDomains As Nullable(Of Integer) = null, Optional subscriptionId As String = null, Optional dnsSuffix As String = null, Optional lastAction As String = null, Optional lastActionResult As String = null, Optional allowedMultiSizes As String = null, Optional allowedWorkerSizes As String = null, Optional maximumNumberOfMachines As Nullable(Of Integer) = null, Optional vipMappings As IList(Of VirtualIPMapping) = null, Optional environmentCapacities As IList(Of StampCapacity) = null, Optional networkAccessControlList As IList(Of NetworkAccessControlEntry) = null, Optional environmentIsHealthy As Nullable(Of Boolean) = null, Optional environmentStatus As String = null, Optional resourceGroup As String = null, Optional frontEndScaleFactor As Nullable(Of Integer) = null, Optional defaultFrontEndScaleFactor As Nullable(Of Integer) = null, Optional apiManagementAccountId As String = null, Optional suspended As Nullable(Of Boolean) = null, Optional dynamicCacheEnabled As Nullable(Of Boolean) = null, Optional clusterSettings As IList(Of NameValuePair) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * string * string * string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner (appServiceEnvironmentResourceName, appServiceEnvironmentResourceLocation, virtualNetwork, workerPools, location, id, name, type, tags, provisioningState, status, vnetName, vnetResourceGroupName, vnetSubnetName, internalLoadBalancingMode, multiSize, multiRoleCount, ipsslAddressCount, databaseEdition, databaseServiceObjective, upgradeDomains, subscriptionId, dnsSuffix, lastAction, lastActionResult, allowedMultiSizes, allowedWorkerSizes, maximumNumberOfMachines, vipMappings, environmentCapacities, networkAccessControlList, environmentIsHealthy, environmentStatus, resourceGroup, frontEndScaleFactor, defaultFrontEndScaleFactor, apiManagementAccountId, suspended, dynamicCacheEnabled, clusterSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="appServiceEnvironmentResourceName" Type="System.String" />
        <Parameter Name="appServiceEnvironmentResourceLocation" Type="System.String" />
        <Parameter Name="virtualNetwork" Type="Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile" />
        <Parameter Name="workerPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt;" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt;" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vnetResourceGroupName" Type="System.String" />
        <Parameter Name="vnetSubnetName" Type="System.String" />
        <Parameter Name="internalLoadBalancingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt;" />
        <Parameter Name="multiSize" Type="System.String" />
        <Parameter Name="multiRoleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="ipsslAddressCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="databaseServiceObjective" Type="System.String" />
        <Parameter Name="upgradeDomains" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="dnsSuffix" Type="System.String" />
        <Parameter Name="lastAction" Type="System.String" />
        <Parameter Name="lastActionResult" Type="System.String" />
        <Parameter Name="allowedMultiSizes" Type="System.String" />
        <Parameter Name="allowedWorkerSizes" Type="System.String" />
        <Parameter Name="maximumNumberOfMachines" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="vipMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt;" />
        <Parameter Name="environmentCapacities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;" />
        <Parameter Name="networkAccessControlList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt;" />
        <Parameter Name="environmentIsHealthy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="environmentStatus" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="frontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultFrontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="apiManagementAccountId" Type="System.String" />
        <Parameter Name="suspended" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dynamicCacheEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clusterSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;" />
      </Parameters>
      <Docs>
        <param name="appServiceEnvironmentResourceName">To be added.</param>
        <param name="appServiceEnvironmentResourceLocation">To be added.</param>
        <param name="virtualNetwork">To be added.</param>
        <param name="workerPools">To be added.</param>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="status">To be added.</param>
        <param name="vnetName">To be added.</param>
        <param name="vnetResourceGroupName">To be added.</param>
        <param name="vnetSubnetName">To be added.</param>
        <param name="internalLoadBalancingMode">To be added.</param>
        <param name="multiSize">To be added.</param>
        <param name="multiRoleCount">To be added.</param>
        <param name="ipsslAddressCount">To be added.</param>
        <param name="databaseEdition">To be added.</param>
        <param name="databaseServiceObjective">To be added.</param>
        <param name="upgradeDomains">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <param name="dnsSuffix">To be added.</param>
        <param name="lastAction">To be added.</param>
        <param name="lastActionResult">To be added.</param>
        <param name="allowedMultiSizes">To be added.</param>
        <param name="allowedWorkerSizes">To be added.</param>
        <param name="maximumNumberOfMachines">To be added.</param>
        <param name="vipMappings">To be added.</param>
        <param name="environmentCapacities">To be added.</param>
        <param name="networkAccessControlList">To be added.</param>
        <param name="environmentIsHealthy">To be added.</param>
        <param name="environmentStatus">To be added.</param>
        <param name="resourceGroup">To be added.</param>
        <param name="frontEndScaleFactor">To be added.</param>
        <param name="defaultFrontEndScaleFactor">To be added.</param>
        <param name="apiManagementAccountId">To be added.</param>
        <param name="suspended">To be added.</param>
        <param name="dynamicCacheEnabled">To be added.</param>
        <param name="clusterSettings">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedMultiSizes">
      <MemberSignature Language="C#" Value="public string AllowedMultiSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedMultiSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AllowedMultiSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedMultiSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedMultiSizes : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AllowedMultiSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedMultiSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-103">コンマ区切りの文字列の一覧を取得フロント エンドの VM サイズが許可されている記述します。</span><span class="sxs-lookup"><span data-stu-id="70dac-103">Gets list of comma separated strings describing which VM sizes are allowed for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedWorkerSizes">
      <MemberSignature Language="C#" Value="public string AllowedWorkerSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedWorkerSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AllowedWorkerSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedWorkerSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedWorkerSizes : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AllowedWorkerSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedWorkerSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-104">取得コンマ区切りの文字列の一覧の記述作業者の VM サイズが許可されます。</span><span class="sxs-lookup"><span data-stu-id="70dac-104">Gets list of comma separated strings describing which VM sizes are allowed for workers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiManagementAccountId">
      <MemberSignature Language="C#" Value="public string ApiManagementAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiManagementAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ApiManagementAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiManagementAccountId As String" />
      <MemberSignature Language="F#" Value="member this.ApiManagementAccountId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ApiManagementAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiManagementAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-105">取得または App Service 環境に関連付けられている API 管理アカウントを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-105">Gets or sets API Management Account associated with the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironmentResourceLocation">
      <MemberSignature Language="C#" Value="public string AppServiceEnvironmentResourceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServiceEnvironmentResourceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AppServiceEnvironmentResourceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServiceEnvironmentResourceLocation As String" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironmentResourceLocation : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AppServiceEnvironmentResourceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-106">取得またはなどの App Service 環境の場所を設定"West US"です。</span><span class="sxs-lookup"><span data-stu-id="70dac-106">Gets or sets location of the App Service Environment, e.g. "West US".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironmentResourceName">
      <MemberSignature Language="C#" Value="public string AppServiceEnvironmentResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServiceEnvironmentResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AppServiceEnvironmentResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServiceEnvironmentResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironmentResourceName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.AppServiceEnvironmentResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-107">取得または App Service 環境の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-107">Gets or sets name of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; ClusterSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; ClusterSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ClusterSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ClusterSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ClusterSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-108">取得または App Service 環境の動作を変更するためのカスタム設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-108">Gets or sets custom settings for changing the behavior of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-109">例: App Service 環境のメタデータ データベースのエディションを取得します。「標準」です。</span><span class="sxs-lookup"><span data-stu-id="70dac-109">Gets edition of the metadata database for the App Service Environment, e.g. "Standard".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseServiceObjective">
      <MemberSignature Language="C#" Value="public string DatabaseServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DatabaseServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseServiceObjective : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DatabaseServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-110">例: メタデータ データベースのサービス目標を App Service 環境の取得します。"S0"です。</span><span class="sxs-lookup"><span data-stu-id="70dac-110">Gets service objective of the metadata database for the App Service Environment, e.g. "S0".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultFrontEndScaleFactor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultFrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DefaultFrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultFrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultFrontEndScaleFactor : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DefaultFrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultFrontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-111">フロント エンドに対して既定のスケール ファクターを取得。</span><span class="sxs-lookup"><span data-stu-id="70dac-111">Gets default Scale Factor for FrontEnds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSuffix">
      <MemberSignature Language="C#" Value="public string DnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.DnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-112">取得または App Service 環境の DNS サフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-112">Gets or sets DNS suffix of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCacheEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DynamicCacheEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DynamicCacheEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DynamicCacheEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCacheEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DynamicCacheEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.DynamicCacheEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicCacheEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-113">取得または App Service 環境が中断されているかどうかを示す true または false を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-113">Gets or sets true/false indicating whether the App Service Environment is suspended.</span></span> <span data-ttu-id="70dac-114">環境を指定できます中断などと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="70dac-114">The environment can be suspended e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentCapacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt; EnvironmentCapacities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt; EnvironmentCapacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentCapacities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentCapacities As IList(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentCapacities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentCapacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentCapacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-115">現在の合計、使用、および使用可能なワーカーの容量を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-115">Gets current total, used, and available worker capacities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentIsHealthy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnvironmentIsHealthy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnvironmentIsHealthy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentIsHealthy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentIsHealthy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentIsHealthy : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentIsHealthy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentIsHealthy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-116">App Service 環境が正常かどうかを示す true または false を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-116">Gets true/false indicating whether the App Service Environment is healthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentStatus">
      <MemberSignature Language="C#" Value="public string EnvironmentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnvironmentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentStatus As String" />
      <MemberSignature Language="F#" Value="member this.EnvironmentStatus : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.EnvironmentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-117">取得についての詳細メッセージの App Service 環境の最後のチェックの結果。</span><span class="sxs-lookup"><span data-stu-id="70dac-117">Gets detailed message about with results of the last check of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontEndScaleFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.FrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontEndScaleFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.FrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-118">取得またはフロント エンドのスケール ファクターを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-118">Gets or sets scale factor for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalLoadBalancingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.InternalLoadBalancingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode)" />
      <MemberSignature Language="F#" Value="member this.InternalLoadBalancingMode : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.InternalLoadBalancingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.internalLoadBalancingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.InternalLoadBalancingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-119">取得または設定は、App Service 環境の仮想ネットワークで内部的に機能するには、どのエンドポイントを指定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-119">Gets or sets specifies which endpoints to serve internally in the Virtual Network for the App Service Environment.</span></span> <span data-ttu-id="70dac-120">使用可能な値が含まれます 'None'、'Web'、'公開'。</span><span class="sxs-lookup"><span data-stu-id="70dac-120">Possible values include: 'None', 'Web', 'Publishing'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsslAddressCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IpsslAddressCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IpsslAddressCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.IpsslAddressCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsslAddressCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IpsslAddressCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.IpsslAddressCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipsslAddressCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-121">取得または予約済みの App Service 環境の IP SSL アドレスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-121">Gets or sets number of IP SSL addresses reserved for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAction">
      <MemberSignature Language="C#" Value="public string LastAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.LastAction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAction As String" />
      <MemberSignature Language="F#" Value="member this.LastAction : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.LastAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-122">取得の最後の App Service 環境の展開操作します。</span><span class="sxs-lookup"><span data-stu-id="70dac-122">Gets last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActionResult">
      <MemberSignature Language="C#" Value="public string LastActionResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastActionResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.LastActionResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActionResult As String" />
      <MemberSignature Language="F#" Value="member this.LastActionResult : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.LastActionResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastActionResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-123">App Service 環境の最後の展開の操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-123">Gets result of the last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfMachines">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MaximumNumberOfMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfMachines As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfMachines : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MaximumNumberOfMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfMachines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-124">App Service Environment で Vm の最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-124">Gets maximum number of VMs in the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiRoleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MultiRoleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MultiRoleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MultiRoleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiRoleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MultiRoleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MultiRoleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiRoleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-125">取得またはフロント エンド インスタンスの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-125">Gets or sets number of front-end instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiSize">
      <MemberSignature Language="C#" Value="public string MultiSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MultiSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MultiSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiSize As String" />
      <MemberSignature Language="F#" Value="member this.MultiSize : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.MultiSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-126">例: フロント エンドの VM サイズの設定を取得または「中」、"Large"です。</span><span class="sxs-lookup"><span data-stu-id="70dac-126">Gets or sets front-end VM size, e.g. "Medium", "Large".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAccessControlList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.NetworkAccessControlList" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAccessControlList As IList(Of NetworkAccessControlEntry)" />
      <MemberSignature Language="F#" Value="member this.NetworkAccessControlList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.NetworkAccessControlList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAccessControlList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.NetworkAccessControlEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-127">取得または App Service 環境へのトラフィックを制御するためのアクセス制御リストを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-127">Gets or sets access control list for controlling traffic to the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-128">App Service 環境の状態のプロビジョニングを取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-128">Gets provisioning state of the App Service Environment.</span></span> <span data-ttu-id="70dac-129">使用可能な値が含まれます: 'は Succeeded'、'失敗'、'キャンセル'、'処理中'、'削除'</span><span class="sxs-lookup"><span data-stu-id="70dac-129">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-130">App Service 環境のリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-130">Gets resource group of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of HostingEnvironmentStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-131">App Service 環境の現在の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-131">Gets current status of the App Service Environment.</span></span> <span data-ttu-id="70dac-132">使用可能な値が含まれます: 'を準備する'、'準備完了'、'スケーリング'、'削除'</span><span class="sxs-lookup"><span data-stu-id="70dac-132">Possible values include: 'Preparing', 'Ready', 'Scaling', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-133">App Service 環境のサブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-133">Gets subscription of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspended">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Suspended { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Suspended" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.Suspended" />
      <MemberSignature Language="VB.NET" Value="Public Property Suspended As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Suspended : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.Suspended" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspended")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-134">取得または設定&amp;lt; コード&amp;gt 以外の場合は true&amp;lt;/code&amp;gt; App Service 環境が中断されている、それ以外の場合は&amp;lt; コード&amp;gt; false&amp;lt;/code&amp;。gt;。</span><span class="sxs-lookup"><span data-stu-id="70dac-134">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the App Service Environment is suspended; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="70dac-135">環境を中断することができますなどと、管理エンドポイントは現在利用できません (最も可能性の高い NSG には、着信トラフィックがブロックされているため)。</span><span class="sxs-lookup"><span data-stu-id="70dac-135">The environment can be suspended, e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeDomains")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-136">App Service Environment のアップグレード ドメインの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-136">Gets number of upgrade domains of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServiceEnvironmentResourceInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="70dac-137">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="70dac-137">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="70dac-138">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="70dac-138">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VipMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; VipMappings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt; VipMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VipMappings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VipMappings As IList(Of VirtualIPMapping)" />
      <MemberSignature Language="F#" Value="member this.VipMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VipMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vipMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.VirtualIPMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-139">App Service 環境のマッピングの IP SSL の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="70dac-139">Gets description of IP SSL mapping for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile VirtualNetwork { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile VirtualNetwork" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VirtualNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetwork As VirtualNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualNetwork : Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VirtualNetwork" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetwork")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.VirtualNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-140">取得または仮想ネットワークの説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-140">Gets or sets description of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-141">取得または App Service 環境の仮想ネットワークの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-141">Gets or sets name of the Virtual Network for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceGroupName">
      <MemberSignature Language="C#" Value="public string VnetResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-142">取得または仮想ネットワークのリソース グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-142">Gets or sets resource group of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetSubnetName">
      <MemberSignature Language="C#" Value="public string VnetSubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetSubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetSubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetSubnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetSubnetName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.VnetSubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetSubnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-143">取得または仮想ネットワークのサブネットを設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-143">Gets or sets subnet of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; WorkerPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; WorkerPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.WorkerPools" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerPools As IList(Of WorkerPool)" />
      <MemberSignature Language="F#" Value="member this.WorkerPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceEnvironmentResourceInner.WorkerPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.WorkerPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="70dac-144">取得または各プールでワーカー サイズ Id のワーカー プールの説明、VM サイズ、およびワーカーの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="70dac-144">Gets or sets description of worker pools with worker size IDs, VM sizes, and number of workers in each pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>