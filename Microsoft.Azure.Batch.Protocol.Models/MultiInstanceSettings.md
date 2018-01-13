<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a4a3-101">マルチ インスタンスのタスクを実行する方法を指定する設定です。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-101">Settings which specify how to run a multi-instance task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="0a4a3-102">マルチ インスタンスのタスクは通常、MPI タスクをサポートするために使用されます。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-102">Multi-instance tasks are commonly used to support MPI tasks.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a4a3-103">MultiInstanceSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-103">Initializes a new instance of the MultiInstanceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null, Optional commonResourceFiles As IList(Of ResourceFile) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings : string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings (coordinationCommandLine, numberOfInstances, commonResourceFiles)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="commonResourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine"><span data-ttu-id="0a4a3-104">プライマリを調整するときに有効にするすべてのコンピューティング ノード上で実行するコマンド ラインでは、メイン タスクのコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-104">The command line to run on all the compute nodes to enable them to coordinate when the primary runs the main task command.</span></span></param>
        <param name="numberOfInstances"><span data-ttu-id="0a4a3-105">タスクに必要なコンピューター ノードの数。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-105">The number of compute nodes required by the task.</span></span></param>
        <param name="commonResourceFiles"><span data-ttu-id="0a4a3-106">Batch service は調整のコマンドラインを実行する前にダウンロードされるファイルの一覧。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-106">A list of files that the Batch service will download before running the coordination command line.</span></span></param>
        <summary>
            <span data-ttu-id="0a4a3-107">MultiInstanceSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-107">Initializes a new instance of the MultiInstanceSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonResourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a4a3-108">取得または調整のコマンドラインを実行する前に、バッチ サービスをダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-108">Gets or sets a list of files that the Batch service will download before running the coordination command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a4a3-109">一般的なリソース ファイルとリソース ファイルのタスクの違いは、プライマリののみタスク リソース ファイルがダウンロードされ、プライマリを含むすべてのサブタスクの一般的なリソース ファイルにダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-109">The difference between common resource files and task resource files is that common resource files are downloaded for all subtasks including the primary, whereas task resource files are downloaded only for the primary.</span></span> <span data-ttu-id="0a4a3-110">なお、これらのリソース ファイルは、タスクの作業ディレクトリにダウンロードされませんが、代わりに、タスクのルート ディレクトリ (作業ディレクトリの上の 1 つのディレクトリ) にダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-110">Also note that these resource files are not downloaded to the task working directory, but instead are downloaded to the task root directory (one directory above the working directory).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="coordinationCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a4a3-111">取得または有効にして、プライマリが主なタスクのコマンドを実行するときに調整するためのすべてのコンピューティング ノード上で実行するコマンドラインを設定します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-111">Gets or sets the command line to run on all the compute nodes to enable them to coordinate when the primary runs the main task command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a4a3-112">一般的な調整のコマンドラインは、バック グラウンド サービスを起動し、サービスがノード間のメッセージを処理する準備ができていることを確認します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-112">A typical coordination command line launches a background service and verifies that the service is ready to process inter-node messages.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0a4a3-113">取得またはタスクに必要なコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-113">Gets or sets the number of compute nodes required by the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="0a4a3-114">省略した場合、既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-114">If omitted, the default is 1.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="multiInstanceSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0a4a3-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0a4a3-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0a4a3-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>