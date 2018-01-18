<Type Name="DataLakeAnalyticsUSQLActivity" FullName="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsUSQLActivity : Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsUSQLActivity extends Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsUSQLActivity&#xA;Inherits ActivityTypeProperties" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsUSQLActivity = class&#xA;    inherit ActivityTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.ActivityTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("DataLakeAnalyticsU-SQL")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="3288b-101">データ Lake Analytics U-SQL アクティビティ。</span><span class="sxs-lookup"><span data-stu-id="3288b-101">Data Lake Analytics U-SQL activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3288b-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3288b-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string script);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string script) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (script As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity : string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity script" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="script" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="script">To be added.</param>
        <summary>
            <span data-ttu-id="3288b-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />プレーン テキストのスクリプトを使用します。</span><span class="sxs-lookup"><span data-stu-id="3288b-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" /> with a plaintext script.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsUSQLActivity (string scriptPath, string scriptLinkedService);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string scriptPath, string scriptLinkedService) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (scriptPath As String, scriptLinkedService As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity : string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" Usage="new Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity (scriptPath, scriptLinkedService)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scriptPath" Type="System.String" />
        <Parameter Name="scriptLinkedService" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scriptPath">To be added.</param>
        <param name="scriptLinkedService">To be added.</param>
        <summary>
            <span data-ttu-id="3288b-104">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" />リンクされたサービスでのスクリプトを使用します。</span><span class="sxs-lookup"><span data-stu-id="3288b-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity" /> with script in linked service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationMode">
      <MemberSignature Language="C#" Value="public string CompilationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CompilationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CompilationMode As String" />
      <MemberSignature Language="F#" Value="member this.CompilationMode : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.CompilationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-105">Optional.</span></span> <span data-ttu-id="3288b-106">U-SQL のコンパイル モード。</span><span class="sxs-lookup"><span data-stu-id="3288b-106">Compilation mode of U-SQL.</span></span> <span data-ttu-id="3288b-107">いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.USqlCompilationMode" />です。</span><span class="sxs-lookup"><span data-stu-id="3288b-107">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.USqlCompilationMode" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-108">Optional.</span></span> <span data-ttu-id="3288b-109">BAUs (Big Analytics ユニット数)、またはジョブの実行に同時に使用されるノードの最大数とも呼ばれます。</span><span class="sxs-lookup"><span data-stu-id="3288b-109">Also known as BAUs (Big Analytics Units), or the maximum number of nodes that will be used simultaneously to run the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-110">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-110">Optional.</span></span> <span data-ttu-id="3288b-111">ユーザーを U-SQL アクティビティのパラメーターを指定できます。</span><span class="sxs-lookup"><span data-stu-id="3288b-111">Allows user to specify parameters for the U-SQL activity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-112">Optional.</span></span> <span data-ttu-id="3288b-113">キューされているすべてのジョブのうち、先に実行するジョブを決定します。</span><span class="sxs-lookup"><span data-stu-id="3288b-113">Determines which jobs out of all that are queued should be selected to run first.</span></span> <span data-ttu-id="3288b-114">低い優先順位が高いほど、数値 (最小値は 0) です。</span><span class="sxs-lookup"><span data-stu-id="3288b-114">The lower the number, the higher the priority (minimum is 0).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeVersion">
      <MemberSignature Language="C#" Value="public string RuntimeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuntimeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property RuntimeVersion As String" />
      <MemberSignature Language="F#" Value="member this.RuntimeVersion : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.RuntimeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-115">Optional.</span></span> <span data-ttu-id="3288b-116">使用する U SQL エンジンのランタイムのバージョン。</span><span class="sxs-lookup"><span data-stu-id="3288b-116">Runtime version of U-SQL engine to use.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Script">
      <MemberSignature Language="C#" Value="public string Script { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Script" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Script" />
      <MemberSignature Language="VB.NET" Value="Public Property Script As String" />
      <MemberSignature Language="F#" Value="member this.Script : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.Script" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-117">Optional.</span></span> <span data-ttu-id="3288b-118">プレーン テキストの U-SQL スクリプト。</span><span class="sxs-lookup"><span data-stu-id="3288b-118">The plaintext U-SQL script.</span></span> <span data-ttu-id="3288b-119">これと同時に使用できません<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />と<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />です。</span><span class="sxs-lookup"><span data-stu-id="3288b-119">This cannot be used at the same time as <see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" /> and <see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptLinkedService">
      <MemberSignature Language="C#" Value="public string ScriptLinkedService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptLinkedService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptLinkedService As String" />
      <MemberSignature Language="F#" Value="member this.ScriptLinkedService : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-120">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-120">Optional.</span></span> <span data-ttu-id="3288b-121">U-SQL スクリプトをホストしているリンクされたサービス。</span><span class="sxs-lookup"><span data-stu-id="3288b-121">The linked service hosting the U-SQL script.</span></span> <span data-ttu-id="3288b-122">これと同時に使用する必要がある<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />です。</span><span class="sxs-lookup"><span data-stu-id="3288b-122">This needs to be used at the same time as <see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptPath">
      <MemberSignature Language="C#" Value="public string ScriptPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptPath As String" />
      <MemberSignature Language="F#" Value="member this.ScriptPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3288b-123">省略可能。</span><span class="sxs-lookup"><span data-stu-id="3288b-123">Optional.</span></span> <span data-ttu-id="3288b-124">ScriptLinkedService の U-SQL スクリプトへのパス。</span><span class="sxs-lookup"><span data-stu-id="3288b-124">The path to the U-SQL script in the ScriptLinkedService.</span></span> <span data-ttu-id="3288b-125">これと同時に使用する必要がある<see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />です。</span><span class="sxs-lookup"><span data-stu-id="3288b-125">This needs to be used at the same time as <see cref="P:Microsoft.Azure.Management.DataFactories.Models.DataLakeAnalyticsUSQLActivity.ScriptLinkedService" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>