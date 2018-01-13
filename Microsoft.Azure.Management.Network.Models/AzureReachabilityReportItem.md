<Type Name="AzureReachabilityReportItem" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportItem" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b082b-101">指定されたプロバイダーの場所の詳細 レポート azure 到達します。</span><span class="sxs-lookup"><span data-stu-id="b082b-101">Azure reachability report details for a given provider location.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b082b-102">AzureReachabilityReportItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b082b-102">Initializes a new instance of the AzureReachabilityReportItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportItem (string provider = null, string azureLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; latencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string provider, string azureLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; latencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional provider As String = null, Optional azureLocation As String = null, Optional latencies As IList(Of AzureReachabilityReportLatencyInfo) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem (provider, azureLocation, latencies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="azureLocation" Type="System.String" />
        <Parameter Name="latencies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt;" />
      </Parameters>
      <Docs>
        <param name="provider"><span data-ttu-id="b082b-103">インターネット サービス プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="b082b-103">The Internet service provider.</span></span></param>
        <param name="azureLocation"><span data-ttu-id="b082b-104">Azure リージョン。</span><span class="sxs-lookup"><span data-stu-id="b082b-104">The Azure region.</span></span></param>
        <param name="latencies"><span data-ttu-id="b082b-105">各タイム シリーズの待機時間の詳細の一覧です。</span><span class="sxs-lookup"><span data-stu-id="b082b-105">List of latency details for each of the time series.</span></span></param>
        <summary>
            <span data-ttu-id="b082b-106">AzureReachabilityReportItem クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b082b-106">Initializes a new instance of the AzureReachabilityReportItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureLocation">
      <MemberSignature Language="C#" Value="public string AzureLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.AzureLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureLocation As String" />
      <MemberSignature Language="F#" Value="member this.AzureLocation : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.AzureLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b082b-107">取得または Azure の地域を設定します。</span><span class="sxs-lookup"><span data-stu-id="b082b-107">Gets or sets the Azure region.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Latencies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; Latencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; Latencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Latencies" />
      <MemberSignature Language="VB.NET" Value="Public Property Latencies As IList(Of AzureReachabilityReportLatencyInfo)" />
      <MemberSignature Language="F#" Value="member this.Latencies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Latencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="latencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLatencyInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b082b-108">取得または各タイム シリーズの待機時間の詳細の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="b082b-108">Gets or sets list of latency details for each of the time series.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provider")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b082b-109">取得またはインターネット サービス プロバイダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="b082b-109">Gets or sets the Internet service provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>