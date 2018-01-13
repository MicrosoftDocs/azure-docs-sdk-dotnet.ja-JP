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
            タスクのコンテナー設定します。
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
        <param name="imageName">タスクを実行するコンテナーの作成に使用するイメージ。</param>
        <param name="containerRunOptions">コンテナーに追加のオプションは、コマンドを作成します。</param>
        <param name="registry">コンテナー イメージを含むプライベート レジストリです。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" /> クラスの新しいインスタンスを初期化します。
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
            コンテナーに追加のオプションを取得するコマンドを作成します。
            </summary>
        <value>To be added.</value>
        <remarks>
            追加のオプションは、バッチ サービスによって制御されるだけでなく、「docker の作成」コマンドに引数として提供されます。
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
            タスクを実行するコンテナーの作成に使用するイメージを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これが"docker pull"に指定された完全なイメージの参照です。 かどうかはタグが指定されていないイメージ名、タグの一部として": 最新"は、既定値として使用します。
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
            コンテナー イメージを含むプライベート レジストリを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            プールの作成に既に指定した場合、この設定は省略できます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>