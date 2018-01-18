<Type Name="VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration">
  <TypeSignature Language="C#" Value="public class VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineScaleSetUpdatePublicIPAddressConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetUpdatePublicIPAddressConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="700eb-101">説明の仮想マシンのスケールは、IP 構成の PublicIPAddress 構成を設定</span><span class="sxs-lookup"><span data-stu-id="700eb-101">Describes a virtual machines scale set IP Configuration's PublicIPAddress configuration</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdatePublicIPAddressConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="700eb-102">VirtualMachineScaleSetUpdatePublicIPAddressConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="700eb-102">Initializes a new instance of the VirtualMachineScaleSetUpdatePublicIPAddressConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineScaleSetUpdatePublicIPAddressConfiguration (string name = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings dnsSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings dnsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.#ctor(System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional idleTimeoutInMinutes As Nullable(Of Integer) = null, Optional dnsSettings As VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration : string * Nullable&lt;int&gt; * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration (name, idleTimeoutInMinutes, dnsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="700eb-103">パブリック Ip アドレスの構成名。</span><span class="sxs-lookup"><span data-stu-id="700eb-103">The publicIP address configuration name.</span></span></param>
        <param name="idleTimeoutInMinutes"><span data-ttu-id="700eb-104">パブリック IP アドレスのアイドル タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="700eb-104">The idle timeout of the public IP address.</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="700eb-105">パブリック Ip アドレスに適用する dns 設定。</span><span class="sxs-lookup"><span data-stu-id="700eb-105">The dns settings to be applied on the publicIP addresses .</span></span></param>
        <summary>
            <span data-ttu-id="700eb-106">VirtualMachineScaleSetUpdatePublicIPAddressConfiguration クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="700eb-106">Initializes a new instance of the VirtualMachineScaleSetUpdatePublicIPAddressConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetPublicIPAddressConfigurationDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="700eb-107">取得またはパブリック Ip アドレスに適用する dns 設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="700eb-107">Gets or sets the dns settings to be applied on the publicIP addresses .</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="700eb-108">取得またはパブリック IP アドレスのアイドル タイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="700eb-108">Gets or sets the idle timeout of the public IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="700eb-109">取得またはパブリック Ip アドレス構成の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="700eb-109">Gets or sets the publicIP address configuration name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdatePublicIPAddressConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="virtualMachineScaleSetUpdatePublicIPAddressConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="700eb-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="700eb-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="700eb-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="700eb-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>