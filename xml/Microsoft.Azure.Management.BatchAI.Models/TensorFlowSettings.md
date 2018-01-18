<Type Name="TensorFlowSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings">
  <TypeSignature Language="C#" Value="public class TensorFlowSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TensorFlowSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TensorFlowSettings" />
  <TypeSignature Language="F#" Value="type TensorFlowSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ace0e-101">TensorFlow ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-101">Specifies the settings for TensorFlow job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-102">TensorFlowSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-102">Initializes a new instance of the TensorFlowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TensorFlowSettings (string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath = null, string workerCommandLineArgs = null, string parameterServerCommandLineArgs = null, Nullable&lt;int&gt; workerCount = null, Nullable&lt;int&gt; parameterServerCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string masterCommandLineArgs, string pythonInterpreterPath, string workerCommandLineArgs, string parameterServerCommandLineArgs, valuetype System.Nullable`1&lt;int32&gt; workerCount, valuetype System.Nullable`1&lt;int32&gt; parameterServerCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, masterCommandLineArgs As String, Optional pythonInterpreterPath As String = null, Optional workerCommandLineArgs As String = null, Optional parameterServerCommandLineArgs As String = null, Optional workerCount As Nullable(Of Integer) = null, Optional parameterServerCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings : string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings (pythonScriptFilePath, masterCommandLineArgs, pythonInterpreterPath, workerCommandLineArgs, parameterServerCommandLineArgs, workerCount, parameterServerCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="masterCommandLineArgs" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="workerCommandLineArgs" Type="System.String" />
        <Parameter Name="parameterServerCommandLineArgs" Type="System.String" />
        <Parameter Name="workerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="parameterServerCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath"><span data-ttu-id="ace0e-103">ジョブを実行する python スクリプトのパスとファイル名。</span><span class="sxs-lookup"><span data-stu-id="ace0e-103">The path and file name of the python script to execute the job.</span></span></param>
        <param name="masterCommandLineArgs"><span data-ttu-id="ace0e-104">マスターのタスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-104">Specifies the command line arguments for the master task.</span></span></param>
        <param name="pythonInterpreterPath"><span data-ttu-id="ace0e-105">Python インタープリターへのパス。</span><span class="sxs-lookup"><span data-stu-id="ace0e-105">The path to python interpreter.</span></span></param>
        <param name="workerCommandLineArgs"><span data-ttu-id="ace0e-106">ワーカー タスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-106">Specifies the command line arguments for the worker task.</span></span></param>
        <param name="parameterServerCommandLineArgs"><span data-ttu-id="ace0e-107">パラメーターのサーバー タスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-107">Specifies the command line arguments for the parameter server task.</span></span></param>
        <param name="workerCount"><span data-ttu-id="ace0e-108">ワーカー タスクの数。</span><span class="sxs-lookup"><span data-stu-id="ace0e-108">The number of worker tasks.</span></span></param>
        <param name="parameterServerCount"><span data-ttu-id="ace0e-109">Parmeter サーバー タスクの数。</span><span class="sxs-lookup"><span data-stu-id="ace0e-109">The number of parmeter server tasks.</span></span></param>
        <summary>
            <span data-ttu-id="ace0e-110">TensorFlowSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-110">Initializes a new instance of the TensorFlowSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MasterCommandLineArgs">
      <MemberSignature Language="C#" Value="public string MasterCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MasterCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property MasterCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.MasterCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.MasterCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="masterCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-111">取得または設定は、マスターのタスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-111">Gets or sets specifies the command line arguments for the master task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string ParameterServerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParameterServerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-112">取得または設定は、パラメーターのサーバー タスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-112">Gets or sets specifies the command line arguments for the parameter server task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ace0e-113">このプロパティは、1 台のコンピューターのトレーニングでは省略可能です。</span><span class="sxs-lookup"><span data-stu-id="ace0e-113">This property is optional for single machine training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParameterServerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParameterServerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParameterServerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParameterServerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParameterServerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.ParameterServerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameterServerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-114">取得またはサーバー タスク parmeter の数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-114">Gets or sets the number of parmeter server tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ace0e-115">指定した場合、値を nodeCount 以下にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="ace0e-115">If specified, the value must be less than or equal to nodeCount.</span></span> <span data-ttu-id="ace0e-116">指定しない場合、既定値は 1 (このプロパティは 1 台のコンピューターのトレーニングには適用されません) 分散 TensorFlow トレーニング用にします。</span><span class="sxs-lookup"><span data-stu-id="ace0e-116">If not specified, the default value is equal to 1 for distributed TensorFlow training (This property is not applicable for single machine training).</span></span> <span data-ttu-id="ace0e-117">このプロパティは、分散 TensorFlow トレーニングに対してのみ指定できます。</span><span class="sxs-lookup"><span data-stu-id="ace0e-117">This property can be specified only for distributed TensorFlow training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonInterpreterPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonInterpreterPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-118">取得または python インタープリターにパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-118">Gets or sets the path to python interpreter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.PythonScriptFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pythonScriptFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-119">取得またはジョブを実行するスクリプトを python のパスとファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-119">Gets or sets the path and file name of the python script to execute the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tensorFlowSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-120">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ace0e-121">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ace0e-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WorkerCommandLineArgs">
      <MemberSignature Language="C#" Value="public string WorkerCommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerCommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.WorkerCommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCommandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-122">取得または設定は、ワーカー タスクのコマンドライン引数を指定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-122">Gets or sets specifies the command line arguments for the worker task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ace0e-123">このプロパティは、1 台のコンピューターのトレーニングでは省略可能です。</span><span class="sxs-lookup"><span data-stu-id="ace0e-123">This property is optional for single machine training.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; WorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; WorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.WorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings.WorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="workerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ace0e-124">取得またはワーカー タスクの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ace0e-124">Gets or sets the number of worker tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ace0e-125">値が以下にする必要があります、指定した場合 (nodeCount \* numberOfGPUs VM あたり)。</span><span class="sxs-lookup"><span data-stu-id="ace0e-125">If specified, the value must be less than or equal to (nodeCount \* numberOfGPUs per VM).</span></span> <span data-ttu-id="ace0e-126">指定しない場合、既定値は nodeCount になります。</span><span class="sxs-lookup"><span data-stu-id="ace0e-126">If not specified, the default value is equal to nodeCount.</span></span> <span data-ttu-id="ace0e-127">このプロパティは、分散 TensorFlow トレーニングに対してのみ指定できます。</span><span class="sxs-lookup"><span data-stu-id="ace0e-127">This property can be specified only for distributed TensorFlow training</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>