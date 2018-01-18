<Type Name="AzureReachabilityReportParameters" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportParameters" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportParameters = class" />
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
            <span data-ttu-id="6426c-101">Azure の到達可能性情レポートの地理的および時間の制約。</span><span class="sxs-lookup"><span data-stu-id="6426c-101">Geographic and time constraints for Azure reachability report.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6426c-102">AzureReachabilityReportParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6426c-102">Initializes a new instance of the AzureReachabilityReportParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportParameters (Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, DateTime startTime, DateTime endTime, System.Collections.Generic.IList&lt;string&gt; providers = null, System.Collections.Generic.IList&lt;string&gt; azureLocations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, valuetype System.DateTime startTime, valuetype System.DateTime endTime, class System.Collections.Generic.IList`1&lt;string&gt; providers, class System.Collections.Generic.IList`1&lt;string&gt; azureLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.#ctor(Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation,System.DateTime,System.DateTime,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (providerLocation As AzureReachabilityReportLocation, startTime As DateTime, endTime As DateTime, Optional providers As IList(Of String) = null, Optional azureLocations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters : Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation * DateTime * DateTime * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters (providerLocation, startTime, endTime, providers, azureLocations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="providerLocation" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="providers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="azureLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="providerLocation">To be added.</param>
        <param name="startTime"><span data-ttu-id="6426c-103">Azure の到達可能性情レポートの開始時刻です。</span><span class="sxs-lookup"><span data-stu-id="6426c-103">The start time for the Azure reachability report.</span></span></param>
        <param name="endTime"><span data-ttu-id="6426c-104">Azure の到達可能性情レポートの終了時刻。</span><span class="sxs-lookup"><span data-stu-id="6426c-104">The end time for the Azure reachability report.</span></span></param>
        <param name="providers"><span data-ttu-id="6426c-105">インターネット サービス プロバイダーの一覧です。</span><span class="sxs-lookup"><span data-stu-id="6426c-105">List of Internet service providers.</span></span></param>
        <param name="azureLocations"><span data-ttu-id="6426c-106">クエリのスコープを指定する省略可能な Azure リージョン。</span><span class="sxs-lookup"><span data-stu-id="6426c-106">Optional Azure regions to scope the query to.</span></span></param>
        <summary>
            <span data-ttu-id="6426c-107">AzureReachabilityReportParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="6426c-107">Initializes a new instance of the AzureReachabilityReportParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AzureLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AzureLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.AzureLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AzureLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.AzureLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6426c-108">取得または設定するクエリのスコープを指定する省略可能な Azure リージョン。</span><span class="sxs-lookup"><span data-stu-id="6426c-108">Gets or sets optional Azure regions to scope the query to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6426c-109">取得または Azure 到達可能性情レポートの終了時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6426c-109">Gets or sets the end time for the Azure reachability report.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProviderLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.ProviderLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property ProviderLocation As AzureReachabilityReportLocation" />
      <MemberSignature Language="F#" Value="member this.ProviderLocation : Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.ProviderLocation" />
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
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Providers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Providers" />
      <MemberSignature Language="VB.NET" Value="Public Property Providers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Providers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Providers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6426c-110">取得またはインターネット サービス プロバイダーの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="6426c-110">Gets or sets list of Internet service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6426c-111">取得または Azure 到達可能性情レポートの開始時刻を設定します。</span><span class="sxs-lookup"><span data-stu-id="6426c-111">Gets or sets the start time for the Azure reachability report.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureReachabilityReportParameters.Validate " />
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
            <span data-ttu-id="6426c-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="6426c-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6426c-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6426c-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>