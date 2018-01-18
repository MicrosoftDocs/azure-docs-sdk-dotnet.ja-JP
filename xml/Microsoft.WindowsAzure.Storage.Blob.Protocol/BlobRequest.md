<Type Name="BlobRequest" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest">
  <TypeSignature Language="C#" Value="public static class BlobRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BlobRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobRequest" />
  <TypeSignature Language="F#" Value="type BlobRequest = class" />
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
            <span data-ttu-id="37da0-101">一連の Blob サービスに対する要求を構築するためのヘルパー メソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="37da0-101">Provides a set of helper methods for constructing a request against the Blob service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WriteBlockListBody">
      <MemberSignature Language="C#" Value="public static void WriteBlockListBody (System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem&gt; blocks, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteBlockListBody(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem&gt; blocks, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest.WriteBlockListBody(System.Collections.Generic.IEnumerable{Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem},System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteBlockListBody (blocks As IEnumerable(Of PutBlockListItem), outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteBlockListBody : seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem&gt; * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest.WriteBlockListBody (blocks, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="blocks" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem&gt;" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="blocks"><span data-ttu-id="37da0-102">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="37da0-102">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" /> objects.</span></span></param>
        <param name="outputStream"><span data-ttu-id="37da0-103">ブロック一覧の書き込み先となるストリーム。</span><span class="sxs-lookup"><span data-stu-id="37da0-103">The stream to which the block list is written.</span></span></param>
        <summary>
            <span data-ttu-id="37da0-104">ブロック一覧の本文を XML 形式で指定したストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="37da0-104">Writes the body of the block list to the specified stream in XML format.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteSharedAccessIdentifiers">
      <MemberSignature Language="C#" Value="public static void WriteSharedAccessIdentifiers (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies sharedAccessPolicies, System.IO.Stream outputStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void WriteSharedAccessIdentifiers(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies sharedAccessPolicies, class System.IO.Stream outputStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest.WriteSharedAccessIdentifiers(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies,System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub WriteSharedAccessIdentifiers (sharedAccessPolicies As SharedAccessBlobPolicies, outputStream As Stream)" />
      <MemberSignature Language="F#" Value="static member WriteSharedAccessIdentifiers : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies * System.IO.Stream -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobRequest.WriteSharedAccessIdentifiers (sharedAccessPolicies, outputStream)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessPolicies" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicies" />
        <Parameter Name="outputStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="sharedAccessPolicies"><span data-ttu-id="37da0-105">共有アクセス ポリシーのコレクション。</span><span class="sxs-lookup"><span data-stu-id="37da0-105">A collection of shared access policies.</span></span></param>
        <param name="outputStream"><span data-ttu-id="37da0-106">出力ストリーム。</span><span class="sxs-lookup"><span data-stu-id="37da0-106">An output stream.</span></span></param>
        <summary>
            <span data-ttu-id="37da0-107">共有アクセス ポリシーのコレクションを XML 形式で指定したストリームに書き込みます。</span><span class="sxs-lookup"><span data-stu-id="37da0-107">Writes a collection of shared access policies to the specified stream in XML format.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>