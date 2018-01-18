<Type Name="ContainerResultSegment" FullName="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment">
  <TypeSignature Language="C#" Value="public class ContainerResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerResultSegment" />
  <TypeSignature Language="F#" Value="type ContainerResultSegment = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b8d3-101">セグメントを表します<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />結果し、継続と改ページの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2b8d3-101">Represents a segment of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> results and contains continuation and pagination information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As BlobContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8d3-102">次のセグメントを取得するために使用する継続トークンを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />結果。</span><span class="sxs-lookup"><span data-stu-id="2b8d3-102">Gets the continuation token used to retrieve the next segment of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="2b8d3-103"><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2b8d3-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of CloudBlobContainer)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b8d3-104">列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />結果。</span><span class="sxs-lookup"><span data-stu-id="2b8d3-104">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="2b8d3-105">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="2b8d3-105">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>