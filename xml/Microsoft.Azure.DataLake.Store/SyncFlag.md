<Type Name="SyncFlag" FullName="Microsoft.Azure.DataLake.Store.SyncFlag">
  <TypeSignature Language="C#" Value="public enum SyncFlag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SyncFlag extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.SyncFlag" />
  <TypeSignature Language="VB.NET" Value="Public Enum SyncFlag" />
  <TypeSignature Language="F#" Value="type SyncFlag = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="2aabe-101">操作は、書き込みし、追加の Http 要求の一部としてパラメーターとして渡されるフラグ</span><span class="sxs-lookup"><span data-stu-id="2aabe-101">Flags that are passed as parameters as a part of Http request for operations Write and Append</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CLOSE">
      <MemberSignature Language="C#" Value="CLOSE" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.SyncFlag CLOSE = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.SyncFlag.CLOSE" />
      <MemberSignature Language="VB.NET" Value="CLOSE" />
      <MemberSignature Language="F#" Value="CLOSE = 2" Usage="Microsoft.Azure.DataLake.Store.SyncFlag.CLOSE" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.SyncFlag</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aabe-102">メタデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="2aabe-102">update metadata.</span></span>
            <span data-ttu-id="2aabe-103">ファイルのハンドラーを閉じるか、ストリームのリースを解放します。</span><span class="sxs-lookup"><span data-stu-id="2aabe-103">Close the file handler or stream Releases the lease.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="DATA">
      <MemberSignature Language="C#" Value="DATA" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.SyncFlag DATA = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.SyncFlag.DATA" />
      <MemberSignature Language="VB.NET" Value="DATA" />
      <MemberSignature Language="F#" Value="DATA = 0" Usage="Microsoft.Azure.DataLake.Store.SyncFlag.DATA" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.SyncFlag</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aabe-104">リースを保持します。</span><span class="sxs-lookup"><span data-stu-id="2aabe-104">Holds the lease.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="METADATA">
      <MemberSignature Language="C#" Value="METADATA" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.DataLake.Store.SyncFlag METADATA = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.DataLake.Store.SyncFlag.METADATA" />
      <MemberSignature Language="VB.NET" Value="METADATA" />
      <MemberSignature Language="F#" Value="METADATA = 1" Usage="Microsoft.Azure.DataLake.Store.SyncFlag.METADATA" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.DataLake.Store.SyncFlag</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aabe-105">メタデータは、データを追加すると、更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2aabe-105">Metadata needs to be updated after data is appended</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>