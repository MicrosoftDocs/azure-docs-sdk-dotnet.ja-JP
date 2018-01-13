<Type Name="TaskContainerSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings">
  <TypeSignature Language="C#" Value="public class TaskContainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerSettings" />
  <TypeSignature Language="F#" Value="type TaskContainerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8bc61-101">タスクのコンテナー設定します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-101">The container settings for a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8bc61-102">TaskContainerSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-102">Initializes a new instance of the TaskContainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings (string imageName, string containerRunOptions = null, Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry registry = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string imageName, string containerRunOptions, class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (imageName As String, Optional containerRunOptions As String = null, Optional registry As ContainerRegistry = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings : string * string * Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings (imageName, containerRunOptions, registry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="containerRunOptions" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry" />
      </Parameters>
      <Docs>
        <param name="imageName"><span data-ttu-id="8bc61-103">タスクを実行するコンテナーの作成に使用するイメージ。</span><span class="sxs-lookup"><span data-stu-id="8bc61-103">The image to use to create the container in which the task will run.</span></span></param>
        <param name="containerRunOptions"><span data-ttu-id="8bc61-104">コンテナーに追加のオプションは、コマンドを作成します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-104">Additional options to the container create command.</span></span></param>
        <param name="registry"><span data-ttu-id="8bc61-105">コンテナー イメージを含むプライベート レジストリです。</span><span class="sxs-lookup"><span data-stu-id="8bc61-105">The private registry which contains the container image.</span></span></param>
        <summary>
            <span data-ttu-id="8bc61-106">TaskContainerSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-106">Initializes a new instance of the TaskContainerSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRunOptions">
      <MemberSignature Language="C#" Value="public string ContainerRunOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRunOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ContainerRunOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRunOptions As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRunOptions : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ContainerRunOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerRunOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bc61-107">コマンドを取得または設定がコンテナーに追加のオプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-107">Gets or sets additional options to the container create command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8bc61-108">追加のオプションは、バッチ サービスによって制御されるだけでなく、「docker の作成」コマンドに引数として提供されます。</span><span class="sxs-lookup"><span data-stu-id="8bc61-108">These additional options are supplied as arguments to the "docker create" command, in addition to those controlled by the Batch Service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageName">
      <MemberSignature Language="C#" Value="public string ImageName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ImageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ImageName" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageName As String" />
      <MemberSignature Language="F#" Value="member this.ImageName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ImageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bc61-109">取得またはタスクを実行するコンテナーの作成に使用するイメージを設定します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-109">Gets or sets the image to use to create the container in which the task will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8bc61-110">これが"docker pull"に指定された完全なイメージの参照です。</span><span class="sxs-lookup"><span data-stu-id="8bc61-110">This is the full image reference, as would be specified to "docker pull".</span></span> <span data-ttu-id="8bc61-111">かどうかはタグが指定されていないイメージ名、タグの一部として": 最新"は、既定値として使用します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-111">If no tag is provided as part of the image name, the tag ":latest" is used as a default.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Registry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry Registry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry Registry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Registry" />
      <MemberSignature Language="VB.NET" Value="Public Property Registry As ContainerRegistry" />
      <MemberSignature Language="F#" Value="member this.Registry : Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Registry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bc61-112">取得またはコンテナーのイメージを含むプライベート レジストリを設定します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-112">Gets or sets the private registry which contains the container image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8bc61-113">プールの作成に既に指定した場合、この設定は省略できます。</span><span class="sxs-lookup"><span data-stu-id="8bc61-113">This setting can be omitted if was already provided at pool creation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskContainerSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8bc61-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="8bc61-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8bc61-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8bc61-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>