<Type Name="AzureReachabilityReport" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReport">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReport extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReport" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReport = class" />
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
            <span data-ttu-id="5d57b-101">Azure の到達可能性の詳細 レポートします。</span><span class="sxs-lookup"><span data-stu-id="5d57b-101">Azure reachability report details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReport ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d57b-102">AzureReachabilityReport クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5d57b-102">Initializes a new instance of the AzureReachabilityReport class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReport (string aggregationLevel, Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; reachabilityReport);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string aggregationLevel, class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; reachabilityReport) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.#ctor(System.String,Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (aggregationLevel As String, providerLocation As AzureReachabilityReportLocation, reachabilityReport As IList(Of AzureReachabilityReportItem))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReport : string * Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReport" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReport (aggregationLevel, providerLocation, reachabilityReport)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="aggregationLevel" Type="System.String" />
        <Parameter Name="providerLocation" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation" />
        <Parameter Name="reachabilityReport" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt;" />
      </Parameters>
      <Docs>
        <param name="aggregationLevel"><span data-ttu-id="5d57b-103">Azure の到達可能性情レポートの集計レベル。</span><span class="sxs-lookup"><span data-stu-id="5d57b-103">The aggregation level of Azure reachability report.</span></span> <span data-ttu-id="5d57b-104">国、都道府県、または市区町村を指定できます。</span><span class="sxs-lookup"><span data-stu-id="5d57b-104">Can be Country, State or City.</span></span></param>
        <param name="providerLocation">To be added.</param>
        <param name="reachabilityReport"><span data-ttu-id="5d57b-105">Azure の到達可能性情レポート アイテムの一覧です。</span><span class="sxs-lookup"><span data-stu-id="5d57b-105">List of Azure reachability report items.</span></span></param>
        <summary>
            <span data-ttu-id="5d57b-106">AzureReachabilityReport クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5d57b-106">Initializes a new instance of the AzureReachabilityReport class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AggregationLevel">
      <MemberSignature Language="C#" Value="public string AggregationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AggregationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.AggregationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property AggregationLevel As String" />
      <MemberSignature Language="F#" Value="member this.AggregationLevel : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.AggregationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="aggregationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d57b-107">取得または Azure 到達可能性情レポートの集計レベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="5d57b-107">Gets or sets the aggregation level of Azure reachability report.</span></span>
            <span data-ttu-id="5d57b-108">国、都道府県、または市区町村を指定できます。</span><span class="sxs-lookup"><span data-stu-id="5d57b-108">Can be Country, State or City.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProviderLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.ProviderLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property ProviderLocation As AzureReachabilityReportLocation" />
      <MemberSignature Language="F#" Value="member this.ProviderLocation : Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.ProviderLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providerLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReachabilityReport">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; ReachabilityReport { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; ReachabilityReport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.ReachabilityReport" />
      <MemberSignature Language="VB.NET" Value="Public Property ReachabilityReport As IList(Of AzureReachabilityReportItem)" />
      <MemberSignature Language="F#" Value="member this.ReachabilityReport : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.ReachabilityReport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reachabilityReport")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AzureReachabilityReportItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d57b-109">取得または Azure 到達可能性情レポート アイテムの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="5d57b-109">Gets or sets list of Azure reachability report items.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReport.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureReachabilityReport.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d57b-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="5d57b-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d57b-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d57b-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>