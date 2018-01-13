<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class&#xA;    interface ITransportObjectProvider&lt;MultiInstanceSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="d132b-101">マルチ インスタンスのタスクを実行する方法を指定する設定です。</span><span class="sxs-lookup"><span data-stu-id="d132b-101">Settings which specify how to run a multi-instance task.</span></span> <span data-ttu-id="d132b-102">マルチ インスタンスのタスクは通常、MPI タスクをサポートするために使用されます。</span><span class="sxs-lookup"><span data-stu-id="d132b-102">Multi-instance tasks are commonly used to support MPI tasks.</span></span> <span data-ttu-id="d132b-103">詳細については、https://azure.microsoft.com/documentation/articles/batch-mpi/ を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d132b-103">For more information see https://azure.microsoft.com/documentation/articles/batch-mpi/.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.MultiInstanceSettings : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.MultiInstanceSettings (coordinationCommandLine, numberOfInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine"><span data-ttu-id="d132b-104">サブタスクを調整するためのコンピューティング ノードのインスタンスで実行するコマンドです。</span><span class="sxs-lookup"><span data-stu-id="d132b-104">The command to run on the compute node instances for coordinating among the subtasks.</span></span></param>
        <param name="numberOfInstances"><span data-ttu-id="d132b-105">マルチ インスタンスのタスクで必要なコンピューティング ノードの数。</span><span class="sxs-lookup"><span data-stu-id="d132b-105">The number of compute nodes required by the multi-instance task.</span></span></param>
        <summary>
            <span data-ttu-id="d132b-106"><see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d132b-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d132b-107">取得または調整のコマンドラインを実行する前に、バッチ サービスをダウンロードするファイルの一覧を設定します。</span><span class="sxs-lookup"><span data-stu-id="d132b-107">Gets or sets a list of files that the Batch service will download before running the coordination command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="d132b-108">一般的なリソース ファイルとリソース ファイルのタスクの違いは、プライマリののみタスク リソース ファイルがダウンロードされ、プライマリを含むすべてのサブタスクの一般的なリソース ファイルにダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="d132b-108">The difference between common resource files and task resource files is that common resource files are downloaded for all subtasks including the primary, whereas task resource files are downloaded only for the primary.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d132b-109">取得またはサブタスクを調整するためのコンピューティング ノードのインスタンスで実行するコマンドを設定します。</span><span class="sxs-lookup"><span data-stu-id="d132b-109">Gets or sets the command to run on the compute node instances for coordinating among the subtasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d132b-110">取得または複数のインスタンスのタスクで必要なコンピューティング ノードの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d132b-110">Gets or sets the number of compute nodes required by the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>