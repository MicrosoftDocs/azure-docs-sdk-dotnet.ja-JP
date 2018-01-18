<Type Name="TroubleshootingDetails" FullName="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails">
  <TypeSignature Language="C#" Value="public class TroubleshootingDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TroubleshootingDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class TroubleshootingDetails" />
  <TypeSignature Language="F#" Value="type TroubleshootingDetails = class" />
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
            <span data-ttu-id="69512-101">指定されたリソースのトラブルシューティングの情報を得てきました。</span><span class="sxs-lookup"><span data-stu-id="69512-101">Information gained from troubleshooting of specified resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.#ctor" />
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
            <span data-ttu-id="69512-102">TroubleshootingDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="69512-102">Initializes a new instance of the TroubleshootingDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TroubleshootingDetails (string id = null, string reasonType = null, string summary = null, string detail = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; recommendedActions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string reasonType, string summary, string detail, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; recommendedActions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional reasonType As String = null, Optional summary As String = null, Optional detail As String = null, Optional recommendedActions As IList(Of TroubleshootingRecommendedActions) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.TroubleshootingDetails : string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; -&gt; Microsoft.Azure.Management.Network.Models.TroubleshootingDetails" Usage="new Microsoft.Azure.Management.Network.Models.TroubleshootingDetails (id, reasonType, summary, detail, recommendedActions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="reasonType" Type="System.String" />
        <Parameter Name="summary" Type="System.String" />
        <Parameter Name="detail" Type="System.String" />
        <Parameter Name="recommendedActions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="69512-103">操作のトラブルシューティング、get の id。</span><span class="sxs-lookup"><span data-stu-id="69512-103">The id of the get troubleshoot operation.</span></span></param>
        <param name="reasonType"><span data-ttu-id="69512-104">エラーの理由の種類。</span><span class="sxs-lookup"><span data-stu-id="69512-104">Reason type of failure.</span></span></param>
        <param name="summary"><span data-ttu-id="69512-105">トラブルシューティングの概要です。</span><span class="sxs-lookup"><span data-stu-id="69512-105">A summary of troubleshooting.</span></span></param>
        <param name="detail"><span data-ttu-id="69512-106">結果のトラブルシューティングについて説明します。</span><span class="sxs-lookup"><span data-stu-id="69512-106">Details on troubleshooting results.</span></span></param>
        <param name="recommendedActions"><span data-ttu-id="69512-107">推奨される操作の一覧です。</span><span class="sxs-lookup"><span data-stu-id="69512-107">List of recommended actions.</span></span></param>
        <summary>
            <span data-ttu-id="69512-108">TroubleshootingDetails クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="69512-108">Initializes a new instance of the TroubleshootingDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public string Detail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Detail" />
      <MemberSignature Language="VB.NET" Value="Public Property Detail As String" />
      <MemberSignature Language="F#" Value="member this.Detail : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="detail")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69512-109">取得または結果のトラブルシューティングに関する詳細情報を設定します。</span><span class="sxs-lookup"><span data-stu-id="69512-109">Gets or sets details on troubleshooting results.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69512-110">Id、get の取得または設定操作のトラブルシューティングします。</span><span class="sxs-lookup"><span data-stu-id="69512-110">Gets or sets the id of the get troubleshoot operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReasonType">
      <MemberSignature Language="C#" Value="public string ReasonType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReasonType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.ReasonType" />
      <MemberSignature Language="VB.NET" Value="Public Property ReasonType As String" />
      <MemberSignature Language="F#" Value="member this.ReasonType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.ReasonType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reasonType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69512-111">取得またはエラーの理由の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="69512-111">Gets or sets reason type of failure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedActions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; RecommendedActions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; RecommendedActions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.RecommendedActions" />
      <MemberSignature Language="VB.NET" Value="Public Property RecommendedActions As IList(Of TroubleshootingRecommendedActions)" />
      <MemberSignature Language="F#" Value="member this.RecommendedActions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.RecommendedActions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recommendedActions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.TroubleshootingRecommendedActions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69512-112">取得または推奨される操作の一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="69512-112">Gets or sets list of recommended actions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Summary">
      <MemberSignature Language="C#" Value="public string Summary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Summary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Summary" />
      <MemberSignature Language="VB.NET" Value="Public Property Summary As String" />
      <MemberSignature Language="F#" Value="member this.Summary : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.TroubleshootingDetails.Summary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="summary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="69512-113">取得またはトラブルシューティングの概要を設定します。</span><span class="sxs-lookup"><span data-stu-id="69512-113">Gets or sets a summary of troubleshooting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>