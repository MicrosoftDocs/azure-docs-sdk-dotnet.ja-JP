<Type Name="UpdateFirewallRuleParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters">
  <TypeSignature Language="C#" Value="public class UpdateFirewallRuleParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateFirewallRuleParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateFirewallRuleParameters" />
  <TypeSignature Language="F#" Value="type UpdateFirewallRuleParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="baa3c-101">Data Lake Analytics ファイアウォール ルールの更新プログラムのパラメーター</span><span class="sxs-lookup"><span data-stu-id="baa3c-101">Data Lake Analytics firewall rule update parameters</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateFirewallRuleParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="baa3c-102">UpdateFirewallRuleParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="baa3c-102">Initializes a new instance of the UpdateFirewallRuleParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateFirewallRuleParameters (string startIpAddress = null, string endIpAddress = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string startIpAddress, string endIpAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional startIpAddress As String = null, Optional endIpAddress As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters : string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters (startIpAddress, endIpAddress)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="startIpAddress" Type="System.String" />
        <Parameter Name="endIpAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIpAddress"><span data-ttu-id="baa3c-103">ファイアウォール ルールの開始 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="baa3c-103">the start IP address for the firewall rule.</span></span> <span data-ttu-id="baa3c-104">Ipv4 または ipv6 のいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="baa3c-104">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="baa3c-105">始点と終点が同じプロトコルでなければなりません。</span><span class="sxs-lookup"><span data-stu-id="baa3c-105">Start and End should be in the same protocol.</span></span></param>
        <param name="endIpAddress"><span data-ttu-id="baa3c-106">ファイアウォール規則の終了 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="baa3c-106">the end IP address for the firewall rule.</span></span> <span data-ttu-id="baa3c-107">Ipv4 または ipv6 のいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="baa3c-107">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="baa3c-108">始点と終点が同じプロトコルでなければなりません。</span><span class="sxs-lookup"><span data-stu-id="baa3c-108">Start and End should be in the same protocol.</span></span></param>
        <summary>
            <span data-ttu-id="baa3c-109">UpdateFirewallRuleParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="baa3c-109">Initializes a new instance of the UpdateFirewallRuleParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIpAddress">
      <MemberSignature Language="C#" Value="public string EndIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.EndIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property EndIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.EndIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="baa3c-110">取得またはファイアウォール ルールの終了 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="baa3c-110">Gets or sets the end IP address for the firewall rule.</span></span> <span data-ttu-id="baa3c-111">Ipv4 または ipv6 のいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="baa3c-111">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="baa3c-112">始点と終点が同じプロトコルでなければなりません。</span><span class="sxs-lookup"><span data-stu-id="baa3c-112">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIpAddress">
      <MemberSignature Language="C#" Value="public string StartIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.StartIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property StartIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIpAddress : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.UpdateFirewallRuleParameters.StartIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="baa3c-113">取得またはファイアウォール ルールの開始 IP アドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="baa3c-113">Gets or sets the start IP address for the firewall rule.</span></span> <span data-ttu-id="baa3c-114">Ipv4 または ipv6 のいずれかを指定できます。</span><span class="sxs-lookup"><span data-stu-id="baa3c-114">This can be either ipv4 or ipv6.</span></span> <span data-ttu-id="baa3c-115">始点と終点が同じプロトコルでなければなりません。</span><span class="sxs-lookup"><span data-stu-id="baa3c-115">Start and End should be in the same protocol.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>