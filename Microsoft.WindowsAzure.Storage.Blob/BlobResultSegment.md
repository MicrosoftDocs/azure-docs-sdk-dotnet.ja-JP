<Type Name="BlobResultSegment" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment">
  <TypeSignature Language="C#" Value="public class BlobResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobResultSegment" />
  <TypeSignature Language="F#" Value="type BlobResultSegment = class" />
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
            セグメントを表します<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />結果、改ページ調整シナリオの情報を継続します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As BlobContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.ContinuationToken" />
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
            次のセグメントを取得するために使用する継続トークンを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />結果。 返します<c>null</c>以上結果がある場合。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of IListBlobItem)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.IListBlobItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />結果。
            </summary>
        <value>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>