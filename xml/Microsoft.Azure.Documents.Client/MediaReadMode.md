<Type Name="MediaReadMode" FullName="Microsoft.Azure.Documents.Client.MediaReadMode">
  <TypeSignature Language="C#" Value="public enum MediaReadMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MediaReadMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.MediaReadMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum MediaReadMode" />
  <TypeSignature Language="F#" Value="type MediaReadMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            添付ファイルのコンテンツをダウンロードする (ルール サブタイプ) で使用するためのモードを表します <span data-ttu-id="20e47-102">メディア) Azure Cosmos DB サービス。</span><span class="sxs-lookup"><span data-stu-id="20e47-102">media) in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Buffered">
      <MemberSignature Language="C#" Value="Buffered" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.MediaReadMode Buffered = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.MediaReadMode.Buffered" />
      <MemberSignature Language="VB.NET" Value="Buffered" />
      <MemberSignature Language="F#" Value="Buffered = 0" Usage="Microsoft.Azure.Documents.Client.MediaReadMode.Buffered" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.MediaReadMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="20e47-103">コンテンツがクライアントにバッファーし、コンテンツ ストアから直接ストリーミングします。</span><span class="sxs-lookup"><span data-stu-id="20e47-103">Content is buffered at the client and not directly streamed from the content store.</span></span> <span data-ttu-id="20e47-104">バッファーに格納されたを使用すると、メディア ファイルの読み書きにかかった時間を短縮できます。</span><span class="sxs-lookup"><span data-stu-id="20e47-104">Use Buffered to reduce the time taken to read and write media files.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Streamed">
      <MemberSignature Language="C#" Value="Streamed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.MediaReadMode Streamed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.MediaReadMode.Streamed" />
      <MemberSignature Language="VB.NET" Value="Streamed" />
      <MemberSignature Language="F#" Value="Streamed = 1" Usage="Microsoft.Azure.Documents.Client.MediaReadMode.Streamed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Client.MediaReadMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="20e47-105">コンテンツは、すべてのクライアントでバッファーなしのコンテンツ ストアから直接ストリーミングされます。</span><span class="sxs-lookup"><span data-stu-id="20e47-105">Content is directly streamed from the content store without any buffering at the client.</span></span> <span data-ttu-id="20e47-106">Streamed を使用して、メディア ファイルの読み書きのクライアントのメモリ オーバーヘッドが低減します。</span><span class="sxs-lookup"><span data-stu-id="20e47-106">Use Streamed to reduce the client memory overhead of reading and writing media files.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>