<Type Name="SequentialFileStagingArtifact" FullName="Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact">
  <TypeSignature Language="C#" Value="public sealed class SequentialFileStagingArtifact : Microsoft.Azure.Batch.IFileStagingArtifact" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SequentialFileStagingArtifact extends System.Object implements class Microsoft.Azure.Batch.IFileStagingArtifact" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SequentialFileStagingArtifact&#xA;Implements IFileStagingArtifact" />
  <TypeSignature Language="F#" Value="type SequentialFileStagingArtifact = class&#xA;    interface IFileStagingArtifact" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IFileStagingArtifact</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            このファイルのステージング プロバイダーの成果物のペイロードのステージング ファイル
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SequentialFileStagingArtifact ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobContainerCreated">
      <MemberSignature Language="C#" Value="public string BlobContainerCreated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobContainerCreated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact.BlobContainerCreated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobContainerCreated As String" />
      <MemberSignature Language="F#" Value="member this.BlobContainerCreated : string" Usage="Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact.BlobContainerCreated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            作成された任意の blob コンテナーの名前。  
            
            指定された、明示的なコンテナーがないアップロードするには、少なくとも 1 つのファイルがある場合は、blob コンテナーが作成されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamingFragment">
      <MemberSignature Language="C#" Value="public string NamingFragment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamingFragment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact.NamingFragment" />
      <MemberSignature Language="VB.NET" Value="Public Property NamingFragment As String" />
      <MemberSignature Language="F#" Value="member this.NamingFragment : string with get, set" Usage="Microsoft.Azure.Batch.FileStaging.SequentialFileStagingArtifact.NamingFragment" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.FileStaging</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            必要に応じて、呼び出し元によって設定されます。  必要に応じて、実装によって使用されます。 既定の名前を構築するときに使用できる名前フラグメントです。
            
            のみで一度設定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>