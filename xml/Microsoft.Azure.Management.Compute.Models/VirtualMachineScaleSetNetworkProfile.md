<Type Name="VirtualMachineScaleSetNetworkProfile" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetNetworkProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetNetworkProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetNetworkProfile" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetNetworkProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4e56f-101">仮想マシン スケール セットのネットワーク プロファイルを説明します。</span><span class="sxs-lookup"><span data-stu-id="4e56f-101">Describes a virtual machine scale set network profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e56f-102">VirtualMachineScaleSetNetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e56f-102">Initializes a new instance of the VirtualMachineScaleSetNetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetNetworkProfile (Microsoft.Azure.Management.Compute.Models.ApiEntityReference healthProbe = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; networkInterfaceConfigurations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Models.ApiEntityReference healthProbe, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; networkInterfaceConfigurations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.#ctor(Microsoft.Azure.Management.Compute.Models.ApiEntityReference,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional healthProbe As ApiEntityReference = null, Optional networkInterfaceConfigurations As IList(Of VirtualMachineScaleSetNetworkConfiguration) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile : Microsoft.Azure.Management.Compute.Models.ApiEntityReference * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile (healthProbe, networkInterfaceConfigurations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="healthProbe" Type="Microsoft.Azure.Management.Compute.Models.ApiEntityReference" />
        <Parameter Name="networkInterfaceConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt;" />
      </Parameters>
      <Docs>
        <param name="healthProbe"><span data-ttu-id="4e56f-103">仮想マシン スケール セット内のインスタンスの状態を判断するために使用するロード バランサーのプローブへの参照。</span><span class="sxs-lookup"><span data-stu-id="4e56f-103">A reference to a load balancer probe used to determine the health of an instance in the virtual machine scale set.</span></span> <span data-ttu-id="4e56f-104">参照は、形式になります。 '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}/probes/{probeName}'。</span><span class="sxs-lookup"><span data-stu-id="4e56f-104">The reference will be in the form: '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}/probes/{probeName}'.</span></span></param>
        <param name="networkInterfaceConfigurations"><span data-ttu-id="4e56f-105">ネットワークの構成の一覧。</span><span class="sxs-lookup"><span data-stu-id="4e56f-105">The list of network configurations.</span></span></param>
        <summary>
            <span data-ttu-id="4e56f-106">VirtualMachineScaleSetNetworkProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e56f-106">Initializes a new instance of the VirtualMachineScaleSetNetworkProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.ApiEntityReference HealthProbe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.ApiEntityReference HealthProbe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.HealthProbe" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthProbe As ApiEntityReference" />
      <MemberSignature Language="F#" Value="member this.HealthProbe : Microsoft.Azure.Management.Compute.Models.ApiEntityReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.HealthProbe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthProbe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.ApiEntityReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e56f-107">取得または仮想マシン スケール セット内のインスタンスの状態を判断するために使用するロード バランサーのプローブへの参照を設定します。</span><span class="sxs-lookup"><span data-stu-id="4e56f-107">Gets or sets a reference to a load balancer probe used to determine the health of an instance in the virtual machine scale set.</span></span> <span data-ttu-id="4e56f-108">参照は、形式になります。 '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}/probes/{probeName}'。</span><span class="sxs-lookup"><span data-stu-id="4e56f-108">The reference will be in the form: '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Network/loadBalancers/{loadBalancerName}/probes/{probeName}'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; NetworkInterfaceConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; NetworkInterfaceConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.NetworkInterfaceConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceConfigurations As IList(Of VirtualMachineScaleSetNetworkConfiguration)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkProfile.NetworkInterfaceConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaceConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetNetworkConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e56f-109">取得またはネットワーク構成の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="4e56f-109">Gets or sets the list of network configurations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>