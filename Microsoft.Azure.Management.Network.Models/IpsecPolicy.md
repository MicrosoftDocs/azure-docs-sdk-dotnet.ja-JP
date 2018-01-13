<Type Name="IpsecPolicy" FullName="Microsoft.Azure.Management.Network.Models.IpsecPolicy">
  <TypeSignature Language="C#" Value="public class IpsecPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IpsecPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.IpsecPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class IpsecPolicy" />
  <TypeSignature Language="F#" Value="type IpsecPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="60c1e-101">仮想ネットワーク ゲートウェイ接続用の IPSec ポリシーの構成</span><span class="sxs-lookup"><span data-stu-id="60c1e-101">An IPSec Policy configuration for a virtual network gateway connection</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpsecPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-102">IpsecPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-102">Initializes a new instance of the IpsecPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpsecPolicy (int saLifeTimeSeconds, int saDataSizeKilobytes, string ipsecEncryption, string ipsecIntegrity, string ikeEncryption, string ikeIntegrity, string dhGroup, string pfsGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 saLifeTimeSeconds, int32 saDataSizeKilobytes, string ipsecEncryption, string ipsecIntegrity, string ikeEncryption, string ikeIntegrity, string dhGroup, string pfsGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.#ctor(System.Int32,System.Int32,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (saLifeTimeSeconds As Integer, saDataSizeKilobytes As Integer, ipsecEncryption As String, ipsecIntegrity As String, ikeEncryption As String, ikeIntegrity As String, dhGroup As String, pfsGroup As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.IpsecPolicy : int * int * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.IpsecPolicy" Usage="new Microsoft.Azure.Management.Network.Models.IpsecPolicy (saLifeTimeSeconds, saDataSizeKilobytes, ipsecEncryption, ipsecIntegrity, ikeEncryption, ikeIntegrity, dhGroup, pfsGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="saLifeTimeSeconds" Type="System.Int32" />
        <Parameter Name="saDataSizeKilobytes" Type="System.Int32" />
        <Parameter Name="ipsecEncryption" Type="System.String" />
        <Parameter Name="ipsecIntegrity" Type="System.String" />
        <Parameter Name="ikeEncryption" Type="System.String" />
        <Parameter Name="ikeIntegrity" Type="System.String" />
        <Parameter Name="dhGroup" Type="System.String" />
        <Parameter Name="pfsGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="saLifeTimeSeconds"><span data-ttu-id="60c1e-103">サイト間 VPN トンネルを秒単位で (クイック モードまたはフェーズ 2 SA とも呼ばれます) の IPSec セキュリティ アソシエーションの有効期間。</span><span class="sxs-lookup"><span data-stu-id="60c1e-103">The IPSec Security Association (also called Quick Mode or Phase 2 SA) lifetime in seconds for a site to site VPN tunnel.</span></span></param>
        <param name="saDataSizeKilobytes"><span data-ttu-id="60c1e-104">IPSec セキュリティ アソシエーション (クイック モードまたはフェーズ 2 の SA をとも呼ばれます) のペイロードのサイズ (KB 単位)、サイト間 VPN トンネルします。</span><span class="sxs-lookup"><span data-stu-id="60c1e-104">The IPSec Security Association (also called Quick Mode or Phase 2 SA) payload size in KB for a site to site VPN tunnel.</span></span></param>
        <param name="ipsecEncryption"><span data-ttu-id="60c1e-105">IPSec の暗号化アルゴリズム (IKE フェーズ 1) です。</span><span class="sxs-lookup"><span data-stu-id="60c1e-105">The IPSec encryption algorithm (IKE phase 1).</span></span> <span data-ttu-id="60c1e-106">使用可能な値が含まれます 'None'、'DES'、'DES3'、'AES128'、'AES192'、'AES256'、'GCMAES128'、'GCMAES192'、'GCMAES256'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-106">Possible values include: 'None', 'DES', 'DES3', 'AES128', 'AES192', 'AES256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span></param>
        <param name="ipsecIntegrity"><span data-ttu-id="60c1e-107">IPSec 整合性アルゴリズム (IKE フェーズ 1) です。</span><span class="sxs-lookup"><span data-stu-id="60c1e-107">The IPSec integrity algorithm (IKE phase 1).</span></span> <span data-ttu-id="60c1e-108">使用可能な値が含まれます: 'MD5'、'SHA1'、'SHA256'、'GCMAES128'、'GCMAES192'、'GCMAES256'</span><span class="sxs-lookup"><span data-stu-id="60c1e-108">Possible values include: 'MD5', 'SHA1', 'SHA256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span></param>
        <param name="ikeEncryption"><span data-ttu-id="60c1e-109">IKE の暗号化アルゴリズム (IKE フェーズ 2)。</span><span class="sxs-lookup"><span data-stu-id="60c1e-109">The IKE encryption algorithm (IKE phase 2).</span></span> <span data-ttu-id="60c1e-110">使用可能な値が含まれます: 'DES'、'DES3'、'AES128'、'AES192'、'AES256'</span><span class="sxs-lookup"><span data-stu-id="60c1e-110">Possible values include: 'DES', 'DES3', 'AES128', 'AES192', 'AES256'</span></span></param>
        <param name="ikeIntegrity"><span data-ttu-id="60c1e-111">IKE 整合性アルゴリズム (IKE フェーズ 2)。</span><span class="sxs-lookup"><span data-stu-id="60c1e-111">The IKE integrity algorithm (IKE phase 2).</span></span> <span data-ttu-id="60c1e-112">使用可能な値が含まれます: 'MD5'、'SHA1'、'SHA256'、'SHA384'</span><span class="sxs-lookup"><span data-stu-id="60c1e-112">Possible values include: 'MD5', 'SHA1', 'SHA256', 'SHA384'</span></span></param>
        <param name="dhGroup"><span data-ttu-id="60c1e-113">DH グループは、初期 SA の IKE フェーズ 1 で使用します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-113">The DH Groups used in IKE Phase 1 for initial SA.</span></span> <span data-ttu-id="60c1e-114">使用可能な値が含まれます 'None'、'DHGroup1'、'DHGroup2'、'DHGroup14'、'DHGroup2048'、'ECP256'、'ECP384'、'DHGroup24'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-114">Possible values include: 'None', 'DHGroup1', 'DHGroup2', 'DHGroup14', 'DHGroup2048', 'ECP256', 'ECP384', 'DHGroup24'</span></span></param>
        <param name="pfsGroup"><span data-ttu-id="60c1e-115">DH グループは、新しい子 SA の IKE フェーズ 2 で使用します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-115">The DH Groups used in IKE Phase 2 for new child SA.</span></span> <span data-ttu-id="60c1e-116">使用可能な値が含まれます 'None'、'PFS1'、'PFS2'、'PFS2048'、'ECP256'、'ECP384'、'PFS24'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-116">Possible values include: 'None', 'PFS1', 'PFS2', 'PFS2048', 'ECP256', 'ECP384', 'PFS24'</span></span></param>
        <summary>
            <span data-ttu-id="60c1e-117">IpsecPolicy クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-117">Initializes a new instance of the IpsecPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhGroup">
      <MemberSignature Language="C#" Value="public string DhGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DhGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.DhGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property DhGroup As String" />
      <MemberSignature Language="F#" Value="member this.DhGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.DhGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dhGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-118">取得または初期 SA の IKE フェーズ 1 で使用される DH グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-118">Gets or sets the DH Groups used in IKE Phase 1 for initial SA.</span></span>
            <span data-ttu-id="60c1e-119">使用可能な値が含まれます 'None'、'DHGroup1'、'DHGroup2'、'DHGroup14'、'DHGroup2048'、'ECP256'、'ECP384'、'DHGroup24'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-119">Possible values include: 'None', 'DHGroup1', 'DHGroup2', 'DHGroup14', 'DHGroup2048', 'ECP256', 'ECP384', 'DHGroup24'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IkeEncryption">
      <MemberSignature Language="C#" Value="public string IkeEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IkeEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property IkeEncryption As String" />
      <MemberSignature Language="F#" Value="member this.IkeEncryption : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ikeEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-120">取得または暗号化アルゴリズム (IKE フェーズ 2) を IKE に設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-120">Gets or sets the IKE encryption algorithm (IKE phase 2).</span></span> <span data-ttu-id="60c1e-121">使用可能な値が含まれます: 'DES'、'DES3'、'AES128'、'AES192'、'AES256'</span><span class="sxs-lookup"><span data-stu-id="60c1e-121">Possible values include: 'DES', 'DES3', 'AES128', 'AES192', 'AES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IkeIntegrity">
      <MemberSignature Language="C#" Value="public string IkeIntegrity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IkeIntegrity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeIntegrity" />
      <MemberSignature Language="VB.NET" Value="Public Property IkeIntegrity As String" />
      <MemberSignature Language="F#" Value="member this.IkeIntegrity : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IkeIntegrity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ikeIntegrity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-122">取得または IKE 整合性アルゴリズム (IKE フェーズ 2) を設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-122">Gets or sets the IKE integrity algorithm (IKE phase 2).</span></span> <span data-ttu-id="60c1e-123">使用可能な値が含まれます: 'MD5'、'SHA1'、'SHA256'、'SHA384'</span><span class="sxs-lookup"><span data-stu-id="60c1e-123">Possible values include: 'MD5', 'SHA1', 'SHA256', 'SHA384'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecEncryption">
      <MemberSignature Language="C#" Value="public string IpsecEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpsecEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecEncryption As String" />
      <MemberSignature Language="F#" Value="member this.IpsecEncryption : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipsecEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-124">取得または IPSec の暗号化アルゴリズム (IKE フェーズ 1) を設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-124">Gets or sets the IPSec encryption algorithm (IKE phase 1).</span></span> <span data-ttu-id="60c1e-125">使用可能な値が含まれます 'None'、'DES'、'DES3'、'AES128'、'AES192'、'AES256'、'GCMAES128'、'GCMAES192'、'GCMAES256'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-125">Possible values include: 'None', 'DES', 'DES3', 'AES128', 'AES192', 'AES256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsecIntegrity">
      <MemberSignature Language="C#" Value="public string IpsecIntegrity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpsecIntegrity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecIntegrity" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsecIntegrity As String" />
      <MemberSignature Language="F#" Value="member this.IpsecIntegrity : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.IpsecIntegrity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipsecIntegrity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-126">取得または IPSec 整合性アルゴリズム (IKE フェーズ 1) を設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-126">Gets or sets the IPSec integrity algorithm (IKE phase 1).</span></span> <span data-ttu-id="60c1e-127">使用可能な値が含まれます: 'MD5'、'SHA1'、'SHA256'、'GCMAES128'、'GCMAES192'、'GCMAES256'</span><span class="sxs-lookup"><span data-stu-id="60c1e-127">Possible values include: 'MD5', 'SHA1', 'SHA256', 'GCMAES128', 'GCMAES192', 'GCMAES256'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PfsGroup">
      <MemberSignature Language="C#" Value="public string PfsGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PfsGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.PfsGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property PfsGroup As String" />
      <MemberSignature Language="F#" Value="member this.PfsGroup : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.PfsGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pfsGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-128">取得または新しい子 SA の IKE フェーズ 2 で使用される DH グループを設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-128">Gets or sets the DH Groups used in IKE Phase 2 for new child SA.</span></span>
            <span data-ttu-id="60c1e-129">使用可能な値が含まれます 'None'、'PFS1'、'PFS2'、'PFS2048'、'ECP256'、'ECP384'、'PFS24'。</span><span class="sxs-lookup"><span data-stu-id="60c1e-129">Possible values include: 'None', 'PFS1', 'PFS2', 'PFS2048', 'ECP256', 'ECP384', 'PFS24'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaDataSizeKilobytes">
      <MemberSignature Language="C#" Value="public int SaDataSizeKilobytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SaDataSizeKilobytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaDataSizeKilobytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SaDataSizeKilobytes As Integer" />
      <MemberSignature Language="F#" Value="member this.SaDataSizeKilobytes : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaDataSizeKilobytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="saDataSizeKilobytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-130">取得またはサイト間 VPN トンネルの IPSec セキュリティ アソシエーションの (クイック モードまたはフェーズ 2 SA とも呼ばれます) のペイロードのサイズを kb 単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-130">Gets or sets the IPSec Security Association (also called Quick Mode or Phase 2 SA) payload size in KB for a site to site VPN tunnel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaLifeTimeSeconds">
      <MemberSignature Language="C#" Value="public int SaLifeTimeSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 SaLifeTimeSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaLifeTimeSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property SaLifeTimeSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.SaLifeTimeSeconds : int with get, set" Usage="Microsoft.Azure.Management.Network.Models.IpsecPolicy.SaLifeTimeSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="saLifeTimeSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-131">取得またはサイト間 VPN トンネルを秒単位で、IPSec セキュリティ アソシエーション (クイック モードまたはフェーズ 2 SA とも呼ばれます) 有効期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-131">Gets or sets the IPSec Security Association (also called Quick Mode or Phase 2 SA) lifetime in seconds for a site to site VPN tunnel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.IpsecPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="ipsecPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="60c1e-132">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="60c1e-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="60c1e-133">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="60c1e-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>