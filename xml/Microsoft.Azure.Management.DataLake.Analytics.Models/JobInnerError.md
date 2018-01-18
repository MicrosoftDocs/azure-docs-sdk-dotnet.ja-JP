<Type Name="JobInnerError" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError">
  <TypeSignature Language="C#" Value="public class JobInnerError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInnerError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInnerError" />
  <TypeSignature Language="F#" Value="type JobInnerError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6092-101">Data Lake Analytics ジョブのエラーの詳細。</span><span class="sxs-lookup"><span data-stu-id="c6092-101">The Data Lake Analytics job error details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInnerError ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6092-102">JobInnerError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6092-102">Initializes a new instance of the JobInnerError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInnerError (Nullable&lt;int&gt; diagnosticCode = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity = null, string details = null, string component = null, string errorId = null, string helpLink = null, string internalDiagnostics = null, string message = null, string resolution = null, string source = null, string description = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; diagnosticCode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; severity, string details, string component, string errorId, string helpLink, string internalDiagnostics, string message, string resolution, string source, string description, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError innerError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes},System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional diagnosticCode As Nullable(Of Integer) = null, Optional severity As Nullable(Of SeverityTypes) = null, Optional details As String = null, Optional component As String = null, Optional errorId As String = null, Optional helpLink As String = null, Optional internalDiagnostics As String = null, Optional message As String = null, Optional resolution As String = null, Optional source As String = null, Optional description As String = null, Optional innerError As JobInnerError = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; * string * string * string * string * string * string * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError (diagnosticCode, severity, details, component, errorId, helpLink, internalDiagnostics, message, resolution, source, description, innerError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="diagnosticCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="severity" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" />
        <Parameter Name="details" Type="System.String" />
        <Parameter Name="component" Type="System.String" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="helpLink" Type="System.String" />
        <Parameter Name="internalDiagnostics" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="resolution" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="innerError" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" />
      </Parameters>
      <Docs>
        <param name="diagnosticCode"><span data-ttu-id="c6092-103">診断エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c6092-103">the diagnostic error code.</span></span></param>
        <param name="severity"><span data-ttu-id="c6092-104">エラーの重大度レベル。</span><span class="sxs-lookup"><span data-stu-id="c6092-104">the severity level of the failure.</span></span> <span data-ttu-id="c6092-105">使用可能な値が含まれます: 'Warning'、'Error'、'情報'、'SevereWarning'、'非推奨'、'UserWarning'</span><span class="sxs-lookup"><span data-stu-id="c6092-105">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span></param>
        <param name="details"><span data-ttu-id="c6092-106">エラー メッセージの詳細。</span><span class="sxs-lookup"><span data-stu-id="c6092-106">the details of the error message.</span></span></param>
        <param name="component"><span data-ttu-id="c6092-107">失敗したコンポーネント。</span><span class="sxs-lookup"><span data-stu-id="c6092-107">the component that failed.</span></span></param>
        <param name="errorId"><span data-ttu-id="c6092-108">ジョブで発生したエラーの種類の特定の識別子。</span><span class="sxs-lookup"><span data-stu-id="c6092-108">the specific identifier for the type of error encountered in the job.</span></span></param>
        <param name="helpLink"><span data-ttu-id="c6092-109">MSDN または Azure へのリンクは、存在する場合、この種類のエラーのヘルプします。</span><span class="sxs-lookup"><span data-stu-id="c6092-109">the link to MSDN or Azure help for this type of error, if any.</span></span></param>
        <param name="internalDiagnostics"><span data-ttu-id="c6092-110">ジョブ エラーの詳細を要求するユーザーを取得するための十分なアクセス許可がある場合は、内部診断スタック トレース、それ以外の場合、空になります。</span><span class="sxs-lookup"><span data-stu-id="c6092-110">the internal diagnostic stack trace if the user requesting the job error details has sufficient permissions it will be retrieved, otherwise it will be empty.</span></span></param>
        <param name="message"><span data-ttu-id="c6092-111">障害のユーザー フレンドリ エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c6092-111">the user friendly error message for the failure.</span></span></param>
        <param name="resolution"><span data-ttu-id="c6092-112">存在する場合、失敗の推奨される解決方法です。</span><span class="sxs-lookup"><span data-stu-id="c6092-112">the recommended resolution for the failure, if any.</span></span></param>
        <param name="source"><span data-ttu-id="c6092-113">エラーの最終的なソース (通常、システムまたはユーザー)。</span><span class="sxs-lookup"><span data-stu-id="c6092-113">the ultimate source of the failure (usually either SYSTEM or USER).</span></span></param>
        <param name="description"><span data-ttu-id="c6092-114">エラー メッセージの説明</span><span class="sxs-lookup"><span data-stu-id="c6092-114">the error message description</span></span></param>
        <param name="innerError"><span data-ttu-id="c6092-115">この特定のジョブ エラー メッセージ、存在する場合の内部エラーです。</span><span class="sxs-lookup"><span data-stu-id="c6092-115">the inner error of this specific job error message, if any.</span></span></param>
        <summary>
            <span data-ttu-id="c6092-116">JobInnerError クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c6092-116">Initializes a new instance of the JobInnerError class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Component" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="component")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-117">失敗したコンポーネントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-117">Gets the component that failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-118">エラー メッセージの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-118">Gets the error message description</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Details">
      <MemberSignature Language="C#" Value="public string Details { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Details" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Details" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Details As String" />
      <MemberSignature Language="F#" Value="member this.Details : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Details" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="details")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-119">エラー メッセージの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-119">Gets the details of the error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DiagnosticCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DiagnosticCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.DiagnosticCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DiagnosticCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.DiagnosticCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diagnosticCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-120">診断エラー コードを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-120">Gets the diagnostic error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-121">ジョブで発生したエラーの種類の特定の識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-121">Gets the specific identifier for the type of error encountered in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HelpLink">
      <MemberSignature Language="C#" Value="public string HelpLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HelpLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.HelpLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HelpLink As String" />
      <MemberSignature Language="F#" Value="member this.HelpLink : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.HelpLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="helpLink")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-122">存在する場合は、この種のエラー、MSDN または Azure のヘルプへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-122">Gets the link to MSDN or Azure help for this type of error, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError InnerError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InnerError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerError As JobInnerError" />
      <MemberSignature Language="F#" Value="member this.InnerError : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InnerError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="innerError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-123">存在する場合は、この特定のジョブのエラー メッセージの内部エラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-123">Gets the inner error of this specific job error message, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDiagnostics">
      <MemberSignature Language="C#" Value="public string InternalDiagnostics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDiagnostics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InternalDiagnostics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalDiagnostics As String" />
      <MemberSignature Language="F#" Value="member this.InternalDiagnostics : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.InternalDiagnostics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDiagnostics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-124">ジョブ エラーの詳細を取得するための十分なアクセス許可を要求するユーザー、それ以外の場合に空にする場合は、内部診断スタック トレースを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-124">Gets the internal diagnostic stack trace if the user requesting the job error details has sufficient permissions it will be retrieved, otherwise it will be empty.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-125">エラーのユーザー フレンドリ エラー メッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-125">Gets the user friendly error message for the failure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resolution">
      <MemberSignature Language="C#" Value="public string Resolution { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Resolution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Resolution" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Resolution As String" />
      <MemberSignature Language="F#" Value="member this.Resolution : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Resolution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resolution")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-126">存在する場合、エラーが発生する、推奨される解像度を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-126">Gets the recommended resolution for the failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Severity">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt; Severity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Severity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Severity As Nullable(Of SeverityTypes)" />
      <MemberSignature Language="F#" Value="member this.Severity : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Severity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="severity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.SeverityTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-127">エラーの重大度レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="c6092-127">Gets the severity level of the failure.</span></span> <span data-ttu-id="c6092-128">使用可能な値が含まれます: 'Warning'、'Error'、'情報'、'SevereWarning'、'非推奨'、'UserWarning'</span><span class="sxs-lookup"><span data-stu-id="c6092-128">Possible values include: 'Warning', 'Error', 'Info', 'SevereWarning', 'Deprecated', 'UserWarning'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Source" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInnerError.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6092-129">エラーの最終的なソースを取得 (通常、システムまたはユーザー)。</span><span class="sxs-lookup"><span data-stu-id="c6092-129">Gets the ultimate source of the failure (usually either SYSTEM or USER).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>