<Type Name="TaskContainerSettings" FullName="Microsoft.Azure.Batch.TaskContainerSettings">
  <TypeSignature Language="C#" Value="public class TaskContainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskContainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerSettings" />
  <TypeSignature Language="F#" Value="type TaskContainerSettings = class&#xA;    interface ITransportObjectProvider&lt;TaskContainerSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="4ec52-101">タスクのコンテナー設定します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-101">The container settings for a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings (string imageName, string containerRunOptions = null, Microsoft.Azure.Batch.ContainerRegistry registry = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string imageName, string containerRunOptions, class Microsoft.Azure.Batch.ContainerRegistry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskContainerSettings.#ctor(System.String,System.String,Microsoft.Azure.Batch.ContainerRegistry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (imageName As String, Optional containerRunOptions As String = null, Optional registry As ContainerRegistry = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskContainerSettings : string * string * Microsoft.Azure.Batch.ContainerRegistry -&gt; Microsoft.Azure.Batch.TaskContainerSettings" Usage="new Microsoft.Azure.Batch.TaskContainerSettings (imageName, containerRunOptions, registry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="containerRunOptions" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Batch.ContainerRegistry" />
      </Parameters>
      <Docs>
        <param name="imageName"><span data-ttu-id="4ec52-102">タスクを実行するコンテナーの作成に使用するイメージ。</span><span class="sxs-lookup"><span data-stu-id="4ec52-102">The image to use to create the container in which the task will run.</span></span></param>
        <param name="containerRunOptions"><span data-ttu-id="4ec52-103">コンテナーに追加のオプションは、コマンドを作成します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-103">Additional options to the container create command.</span></span></param>
        <param name="registry"><span data-ttu-id="4ec52-104">コンテナー イメージを含むプライベート レジストリです。</span><span class="sxs-lookup"><span data-stu-id="4ec52-104">The private registry which contains the container image.</span></span></param>
        <summary>
            <span data-ttu-id="4ec52-105"><see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRunOptions">
      <MemberSignature Language="C#" Value="public string ContainerRunOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRunOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.ContainerRunOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerRunOptions As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRunOptions : string" Usage="Microsoft.Azure.Batch.TaskContainerSettings.ContainerRunOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ec52-106">コンテナーに追加のオプションを取得するコマンドを作成します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-106">Gets additional options to the container create command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4ec52-107">追加のオプションは、バッチ サービスによって制御されるだけでなく、「docker の作成」コマンドに引数として提供されます。</span><span class="sxs-lookup"><span data-stu-id="4ec52-107">These additional options are supplied as arguments to the "docker create" command, in addition to those controlled by the Batch Service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageName">
      <MemberSignature Language="C#" Value="public string ImageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ImageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.ImageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImageName As String" />
      <MemberSignature Language="F#" Value="member this.ImageName : string" Usage="Microsoft.Azure.Batch.TaskContainerSettings.ImageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ec52-108">タスクを実行するコンテナーの作成に使用するイメージを取得します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-108">Gets the image to use to create the container in which the task will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4ec52-109">これが"docker pull"に指定された完全なイメージの参照です。</span><span class="sxs-lookup"><span data-stu-id="4ec52-109">This is the full image reference, as would be specified to "docker pull".</span></span> <span data-ttu-id="4ec52-110">かどうかはタグが指定されていないイメージ名、タグの一部として": 最新"は、既定値として使用します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-110">If no tag is provided as part of the image name, the tag ":latest" is used as a default.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Registry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ContainerRegistry Registry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ContainerRegistry Registry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.Registry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Registry As ContainerRegistry" />
      <MemberSignature Language="F#" Value="member this.Registry : Microsoft.Azure.Batch.ContainerRegistry" Usage="Microsoft.Azure.Batch.TaskContainerSettings.Registry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ContainerRegistry</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ec52-111">コンテナー イメージを含むプライベート レジストリを取得します。</span><span class="sxs-lookup"><span data-stu-id="4ec52-111">Gets the private registry which contains the container image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4ec52-112">プールの作成に既に指定した場合、この設定は省略できます。</span><span class="sxs-lookup"><span data-stu-id="4ec52-112">This setting can be omitted if was already provided at pool creation.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>