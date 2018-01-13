<Type Name="QueueResultSegment" FullName="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment">
  <TypeSignature Language="C#" Value="public sealed class QueueResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueResultSegment" />
  <TypeSignature Language="F#" Value="type QueueResultSegment = class" />
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
            <span data-ttu-id="72698-101">セグメントを表します<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />結果、改ページ調整シナリオの情報を継続します。</span><span class="sxs-lookup"><span data-stu-id="72698-101">Represents a segment of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> results, with continuation information for pagination scenarios.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As QueueContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72698-102">次のセグメントを取得するために使用する継続トークンを取得<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />結果。</span><span class="sxs-lookup"><span data-stu-id="72698-102">Gets the continuation token used to retrieve the next segment of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> results.</span></span> <span data-ttu-id="72698-103">以上結果がある場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="72698-103">Returns null if there are no more results.</span></span>
            </summary>
        <value><span data-ttu-id="72698-104"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="72698-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of CloudQueue)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72698-105">列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />結果。</span><span class="sxs-lookup"><span data-stu-id="72698-105">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> results.</span></span>
            </summary>
        <value><span data-ttu-id="72698-106">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="72698-106">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>