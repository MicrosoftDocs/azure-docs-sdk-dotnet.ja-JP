<Type Name="CaffeSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings">
  <TypeSignature Language="C#" Value="public class CaffeSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CaffeSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class CaffeSettings" />
  <TypeSignature Language="F#" Value="type CaffeSettings = class" />
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
            <span data-ttu-id="e1496-101">Caffe ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-101">Specifies the settings for Caffe job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaffeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1496-102">CaffeSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1496-102">Initializes a new instance of the CaffeSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaffeSettings (string configFilePath = null, string pythonScriptFilePath = null, string pythonInterpreterPath = null, string commandLineArgs = null, Nullable&lt;int&gt; processCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configFilePath, string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs, valuetype System.Nullable`1&lt;int32&gt; processCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional configFilePath As String = null, Optional pythonScriptFilePath As String = null, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null, Optional processCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.CaffeSettings : string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.CaffeSettings (configFilePath, pythonScriptFilePath, pythonInterpreterPath, commandLineArgs, processCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configFilePath" Type="System.String" />
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
        <Parameter Name="processCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="configFilePath"><span data-ttu-id="e1496-103">構成ファイルのパスを指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-103">Specifies the path of the config file.</span></span></param>
        <param name="pythonScriptFilePath"><span data-ttu-id="e1496-104">ジョブを実行する python スクリプトのパスとファイル名。</span><span class="sxs-lookup"><span data-stu-id="e1496-104">The path and file name of the python script to execute the job.</span></span></param>
        <param name="pythonInterpreterPath"><span data-ttu-id="e1496-105">Python インタープリターへのパス。</span><span class="sxs-lookup"><span data-stu-id="e1496-105">The path to python interpreter.</span></span></param>
        <param name="commandLineArgs"><span data-ttu-id="e1496-106">Caffe ジョブに渡される必要があるコマンドライン引数。</span><span class="sxs-lookup"><span data-stu-id="e1496-106">Command line arguments that needs to be passed to the Caffe job.</span></span></param>
        <param name="processCount"><span data-ttu-id="e1496-107">MPI ランタイムに渡されるプロセス パラメーターの数です。</span><span class="sxs-lookup"><span data-stu-id="e1496-107">Number of processes parameter that is passed to MPI runtime.</span></span></param>
        <summary>
            <span data-ttu-id="e1496-108">CaffeSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1496-108">Initializes a new instance of the CaffeSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.CommandLineArgs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLineArgs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1496-109">取得または Caffe ジョブに渡される必要があるコマンドライン引数を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-109">Gets or sets command line arguments that needs to be passed to the Caffe job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigFilePath">
      <MemberSignature Language="C#" Value="public string ConfigFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ConfigFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property ConfigFilePath As String" />
      <MemberSignature Language="F#" Value="member this.ConfigFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ConfigFilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="configFilePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1496-110">取得または設定は、構成ファイルのパスを指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-110">Gets or sets specifies the path of the config file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e1496-111">このプロパティは、pythonScriptFilePath が指定されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-111">This property cannot be specified if pythonScriptFilePath is specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ProcessCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.ProcessCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e1496-112">取得または MPI ランタイムに渡されるプロセス パラメーターの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-112">Gets or sets number of processes parameter that is passed to MPI runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e1496-113">このプロパティの既定値が、nodeCount プロパティと等しい</span><span class="sxs-lookup"><span data-stu-id="e1496-113">The default value for this property is equal to nodeCount property</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonInterpreterPath" />
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
            <span data-ttu-id="e1496-114">取得または python インタープリターにパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-114">Gets or sets the path to python interpreter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e1496-115">このプロパティにすることができます、pythonScriptFilePath が指定されているかどうかにのみ指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-115">This property can be specified only if the pythonScriptFilePath is specified.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings.PythonScriptFilePath" />
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
            <span data-ttu-id="e1496-116">取得またはジョブを実行するスクリプトを python のパスとファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-116">Gets or sets the path and file name of the python script to execute the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e1496-117">このプロパティは、configFilePath が指定されているかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="e1496-117">This property cannot be specified if configFilePath is specified.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>