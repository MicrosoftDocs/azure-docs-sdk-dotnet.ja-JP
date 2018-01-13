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
            <span data-ttu-id="16ba4-101">このファイルのステージング プロバイダーの成果物のペイロードのステージング ファイル</span><span class="sxs-lookup"><span data-stu-id="16ba4-101">The file staging artifact payload for this file staging provider</span></span>
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
            <span data-ttu-id="16ba4-102">作成された任意の blob コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="16ba4-102">The name of any blob container created.</span></span>  
            
            <span data-ttu-id="16ba4-103">指定された、明示的なコンテナーがないアップロードするには、少なくとも 1 つのファイルがある場合は、blob コンテナーが作成されます。</span><span class="sxs-lookup"><span data-stu-id="16ba4-103">A blob container is created if there is at least one file to be uploaded that does not have an explicit container specified.</span></span>
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
            <span data-ttu-id="16ba4-104">必要に応じて、呼び出し元によって設定されます。</span><span class="sxs-lookup"><span data-stu-id="16ba4-104">Optionally set by caller.</span></span>  <span data-ttu-id="16ba4-105">必要に応じて、実装によって使用されます。</span><span class="sxs-lookup"><span data-stu-id="16ba4-105">Optionally used by implementation.</span></span> <span data-ttu-id="16ba4-106">既定の名前を構築するときに使用できる名前フラグメントです。</span><span class="sxs-lookup"><span data-stu-id="16ba4-106">A name fragment that can be used when constructing default names.</span></span>
            
            <span data-ttu-id="16ba4-107">のみで一度設定できます。</span><span class="sxs-lookup"><span data-stu-id="16ba4-107">Can only be set once.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>