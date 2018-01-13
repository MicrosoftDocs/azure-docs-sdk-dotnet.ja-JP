<Type Name="Caffe2Settings" FullName="Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings">
  <TypeSignature Language="C#" Value="public class Caffe2Settings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Caffe2Settings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings" />
  <TypeSignature Language="VB.NET" Value="Public Class Caffe2Settings" />
  <TypeSignature Language="F#" Value="type Caffe2Settings = class" />
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
            <span data-ttu-id="a1811-101">Caffe2 ジョブの設定を指定します。</span><span class="sxs-lookup"><span data-stu-id="a1811-101">Specifies the settings for Caffe2 job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Caffe2Settings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a1811-102">Caffe2Settings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a1811-102">Initializes a new instance of the Caffe2Settings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Caffe2Settings (string pythonScriptFilePath, string pythonInterpreterPath = null, string commandLineArgs = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string pythonScriptFilePath, string pythonInterpreterPath, string commandLineArgs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (pythonScriptFilePath As String, Optional pythonInterpreterPath As String = null, Optional commandLineArgs As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings : string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings" Usage="new Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings (pythonScriptFilePath, pythonInterpreterPath, commandLineArgs)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pythonScriptFilePath" Type="System.String" />
        <Parameter Name="pythonInterpreterPath" Type="System.String" />
        <Parameter Name="commandLineArgs" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pythonScriptFilePath"><span data-ttu-id="a1811-103">ジョブを実行する python スクリプトのパスとファイル名。</span><span class="sxs-lookup"><span data-stu-id="a1811-103">The path and file name of the python script to execute the job.</span></span></param>
        <param name="pythonInterpreterPath"><span data-ttu-id="a1811-104">Python インタープリターへのパス。</span><span class="sxs-lookup"><span data-stu-id="a1811-104">The path to python interpreter.</span></span></param>
        <param name="commandLineArgs"><span data-ttu-id="a1811-105">Python スクリプトに渡される必要があるコマンドライン引数</span><span class="sxs-lookup"><span data-stu-id="a1811-105">Command line arguments that needs to be passed to the python script</span></span></param>
        <summary>
            <span data-ttu-id="a1811-106">Caffe2Settings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="a1811-106">Initializes a new instance of the Caffe2Settings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLineArgs">
      <MemberSignature Language="C#" Value="public string CommandLineArgs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLineArgs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.CommandLineArgs" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLineArgs As String" />
      <MemberSignature Language="F#" Value="member this.CommandLineArgs : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.CommandLineArgs" />
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
            <span data-ttu-id="a1811-107">取得または設定すると、python スクリプトに渡される必要があるコマンドライン引数</span><span class="sxs-lookup"><span data-stu-id="a1811-107">Gets or sets command line arguments that needs to be passed to the python script</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonInterpreterPath">
      <MemberSignature Language="C#" Value="public string PythonInterpreterPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonInterpreterPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.PythonInterpreterPath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonInterpreterPath As String" />
      <MemberSignature Language="F#" Value="member this.PythonInterpreterPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.PythonInterpreterPath" />
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
            <span data-ttu-id="a1811-108">取得または python インタープリターにパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="a1811-108">Gets or sets the path to python interpreter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonScriptFilePath">
      <MemberSignature Language="C#" Value="public string PythonScriptFilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PythonScriptFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.PythonScriptFilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property PythonScriptFilePath As String" />
      <MemberSignature Language="F#" Value="member this.PythonScriptFilePath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.PythonScriptFilePath" />
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
            <span data-ttu-id="a1811-109">取得またはジョブを実行するスクリプトを python のパスとファイル名を設定します。</span><span class="sxs-lookup"><span data-stu-id="a1811-109">Gets or sets the path and file name of the python script to execute the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="caffe2Settings.Validate " />
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
            <span data-ttu-id="a1811-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="a1811-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a1811-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a1811-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>