<Type Name="ContainerServiceAgentPoolProfile" FullName="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile">
  <TypeSignature Language="C#" Value="public class ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerServiceAgentPoolProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerServiceAgentPoolProfile" />
  <TypeSignature Language="F#" Value="type ContainerServiceAgentPoolProfile = class" />
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
            <span data-ttu-id="4aacd-101">コンテナー サービスのエージェント プールのプロファイル。</span><span class="sxs-lookup"><span data-stu-id="4aacd-101">Profile for the container service agent pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceAgentPoolProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.#ctor" />
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
            <span data-ttu-id="4aacd-102">ContainerServiceAgentPoolProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-102">Initializes a new instance of the ContainerServiceAgentPoolProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerServiceAgentPoolProfile (string name, int count, string vmSize, string dnsPrefix, string fqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 count, string vmSize, string dnsPrefix, string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.#ctor(System.String,System.Int32,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, count As Integer, vmSize As String, dnsPrefix As String, Optional fqdn As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile : string * int * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile" Usage="new Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile (name, count, vmSize, dnsPrefix, fqdn)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="count" Type="System.Int32" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="dnsPrefix" Type="System.String" />
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4aacd-103">サブスクリプションとリソース グループのコンテキストでは、エージェント プール プロファイルの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="4aacd-103">Unique name of the agent pool profile in the context of the subscription and resource group.</span></span></param>
        <param name="count"><span data-ttu-id="4aacd-104">Docker コンテナーのホストにエージェント (Vm) の数。</span><span class="sxs-lookup"><span data-stu-id="4aacd-104">Number of agents (VMs) to host docker containers.</span></span> <span data-ttu-id="4aacd-105">有効な値は、1 ~ 100 (包括) の範囲でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="4aacd-105">Allowed values must be in the range of 1 to 100 (inclusive).</span></span> <span data-ttu-id="4aacd-106">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="4aacd-106">The default value is 1.</span></span> </param>
        <param name="vmSize"><span data-ttu-id="4aacd-107">エージェントの Vm のサイズです。</span><span class="sxs-lookup"><span data-stu-id="4aacd-107">Size of agent VMs.</span></span> <span data-ttu-id="4aacd-108">使用可能な値が含まれます: 'Standard_A0'、'Standard_A1'、'Standard_A2'、'Standard_A3'、'Standard_A4'、'Standard_A5'、'Standard_A6'、'Standard_A7'、'Standard_A8'、'Standard_A9'、'Standard_A10'、'Standard_A11'、'Standard_D1'、'Standard_D2'、'Standard_D3'、'Standard_D4'、'Standard_D11'、'Standard_D12'、'Standard_D13'、'Standard_D14'、'Standard_D1_v2'、'Standard_D2_v2'、'Standard_D3_v2'、'Standard_D4_v2'、'Standard_D5_v2'、'Standard_D11_v2'、'Standard_D12_v2'、'Standard_D13_v2'、'Standard_D14_v2'、'Standard_G1'、'Standard_G2'、'Standard_G3'、'Standard_G4'、'Standard_G5'、'Standard_DS1'、'Standard_DS2'、'Standard_DS3'、'Standard_DS4'、'Standard_DS11'、'Standard_DS12'、'Standard_DS13'、'Standard_DS14'、' Standard_GS1'、'Standard_GS2'、'Standard_GS3'、'Standard_GS4'、'Standard_GS5'</span><span class="sxs-lookup"><span data-stu-id="4aacd-108">Possible values include: 'Standard_A0', 'Standard_A1', 'Standard_A2', 'Standard_A3', 'Standard_A4', 'Standard_A5', 'Standard_A6', 'Standard_A7', 'Standard_A8', 'Standard_A9', 'Standard_A10', 'Standard_A11', 'Standard_D1', 'Standard_D2', 'Standard_D3', 'Standard_D4', 'Standard_D11', 'Standard_D12', 'Standard_D13', 'Standard_D14', 'Standard_D1_v2', 'Standard_D2_v2', 'Standard_D3_v2', 'Standard_D4_v2', 'Standard_D5_v2', 'Standard_D11_v2', 'Standard_D12_v2', 'Standard_D13_v2', 'Standard_D14_v2', 'Standard_G1', 'Standard_G2', 'Standard_G3', 'Standard_G4', 'Standard_G5', 'Standard_DS1', 'Standard_DS2', 'Standard_DS3', 'Standard_DS4', 'Standard_DS11', 'Standard_DS12', 'Standard_DS13', 'Standard_DS14', 'Standard_GS1', 'Standard_GS2', 'Standard_GS3', 'Standard_GS4', 'Standard_GS5'</span></span></param>
        <param name="dnsPrefix"><span data-ttu-id="4aacd-109">エージェント プールに対応する FQDN を作成するために使用する DNS プレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="4aacd-109">DNS prefix to be used to create the FQDN for the agent pool.</span></span></param>
        <param name="fqdn"><span data-ttu-id="4aacd-110">エージェント プールの fdqn のサンプルです。</span><span class="sxs-lookup"><span data-stu-id="4aacd-110">FDQN for the agent pool.</span></span></param>
        <summary>
            <span data-ttu-id="4aacd-111">ContainerServiceAgentPoolProfile クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-111">Initializes a new instance of the ContainerServiceAgentPoolProfile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aacd-112">取得または docker コンテナーのホストにエージェント (Vm) の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-112">Gets or sets number of agents (VMs) to host docker containers.</span></span>
            <span data-ttu-id="4aacd-113">有効な値は、1 ~ 100 (包括) の範囲でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="4aacd-113">Allowed values must be in the range of 1 to 100 (inclusive).</span></span> <span data-ttu-id="4aacd-114">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="4aacd-114">The default value is 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsPrefix">
      <MemberSignature Language="C#" Value="public string DnsPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.DnsPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DnsPrefix : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.DnsPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aacd-115">取得またはエージェント プールに対応する FQDN を作成するために使用する DNS プレフィックスを設定します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-115">Gets or sets DNS prefix to be used to create the FQDN for the agent pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aacd-116">エージェント プールの fdqn のサンプルを取得します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-116">Gets FDQN for the agent pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4aacd-117">取得またはサブスクリプションとリソース グループのコンテキストでは、エージェント プール プロファイルの一意の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-117">Gets or sets unique name of the agent pool profile in the context of the subscription and resource group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerServiceAgentPoolProfile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4aacd-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4aacd-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4aacd-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.ContainerServiceAgentPoolProfile.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4aacd-120">取得またはエージェント Vm のサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="4aacd-120">Gets or sets size of agent VMs.</span></span> <span data-ttu-id="4aacd-121">使用可能な値が含まれます: 'Standard_A0'、'Standard_A1'、'Standard_A2'、'Standard_A3'、'Standard_A4'、'Standard_A5'、'Standard_A6'、'Standard_A7'、'Standard_A8'、'Standard_A9'、'Standard_A10'、'Standard_A11'、'Standard_D1'、'Standard_D2'、'Standard_D3'、'Standard_D4'、'Standard_D11'、'Standard_D12'、'Standard_D13'、'Standard_D14'、'Standard_D1_v2'、'Standard_D2_v2'、'Standard_D3_v2'、'Standard_D4_v2'、'Standard_D5_v2'、'Standard_D11_v2'、'Standard_D12_v2'、'Standard_D13_v2'、'Standard_D14_v2'、'Standard_G1'、'Standard_G2'、'Standard_G3'、'Standard_G4'、'Standard_G5'、'Standard_DS1'、'Standard_DS2'、'Standard_DS3'、'Standard_DS4'、'Standard_DS11'、'Standard_DS12'、'Standard_DS13'、'Standard_DS14'、' Standard_GS1'、'Standard_GS2'、'Standard_GS3'、'Standard_GS4'、'Standard_GS5'</span><span class="sxs-lookup"><span data-stu-id="4aacd-121">Possible values include: 'Standard_A0', 'Standard_A1', 'Standard_A2', 'Standard_A3', 'Standard_A4', 'Standard_A5', 'Standard_A6', 'Standard_A7', 'Standard_A8', 'Standard_A9', 'Standard_A10', 'Standard_A11', 'Standard_D1', 'Standard_D2', 'Standard_D3', 'Standard_D4', 'Standard_D11', 'Standard_D12', 'Standard_D13', 'Standard_D14', 'Standard_D1_v2', 'Standard_D2_v2', 'Standard_D3_v2', 'Standard_D4_v2', 'Standard_D5_v2', 'Standard_D11_v2', 'Standard_D12_v2', 'Standard_D13_v2', 'Standard_D14_v2', 'Standard_G1', 'Standard_G2', 'Standard_G3', 'Standard_G4', 'Standard_G5', 'Standard_DS1', 'Standard_DS2', 'Standard_DS3', 'Standard_DS4', 'Standard_DS11', 'Standard_DS12', 'Standard_DS13', 'Standard_DS14', 'Standard_GS1', 'Standard_GS2', 'Standard_GS3', 'Standard_GS4', 'Standard_GS5'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>