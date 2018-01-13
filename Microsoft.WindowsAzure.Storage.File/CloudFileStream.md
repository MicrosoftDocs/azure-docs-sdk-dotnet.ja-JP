<Type Name="CloudFileStream" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileStream">
  <TypeSignature Language="C#" Value="public abstract class CloudFileStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CloudFileStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CloudFileStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type CloudFileStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c06d-101">ファイルに書き込むためのストリームを表します。</span><span class="sxs-lookup"><span data-stu-id="5c06d-101">Represents a stream for writing to a file.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CloudFileStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCommit">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCommit (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCommit(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.BeginCommit(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginCommit (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCommit : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileStream.BeginCommit (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="5c06d-102">コミットが完了すると呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="5c06d-102">An optional asynchronous callback, to be called when the commit is complete.</span></span></param>
        <param name="state"><span data-ttu-id="5c06d-103">この特定の非同期コミット要求を他の要求と区別するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5c06d-103">A user-provided object that distinguishes this particular asynchronous commit request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="5c06d-104">非同期のコミット操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="5c06d-104">Begins an asynchronous commit operation.</span></span>
            </summary>
        <returns><span data-ttu-id="5c06d-105"><c>ICancellableAsyncResult</c>を表す非同期のコミットは、保留になっている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5c06d-105">An <c>ICancellableAsyncResult</c> that represents the asynchronous commit, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFlush">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.BeginFlush(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginFlush (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFlush : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileStream.BeginFlush (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="5c06d-106">フラッシュの完了時に呼び出されるオプションの非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="5c06d-106">An optional asynchronous callback, to be called when the flush is complete.</span></span></param>
        <param name="state"><span data-ttu-id="5c06d-107">この特定の非同期フラッシュ要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5c06d-107">A user-provided object that distinguishes this particular asynchronous flush request from other requests.</span></span></param>
        <summary>
            <span data-ttu-id="5c06d-108">非同期のフラッシュ操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="5c06d-108">Begins an asynchronous flush operation.</span></span>
            </summary>
        <returns><span data-ttu-id="5c06d-109"><c>ICancellableAsyncResult</c>を表す非同期のフラッシュを保留になっている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5c06d-109">An <c>ICancellableAsyncResult</c> that represents the asynchronous flush, which could still be pending.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public abstract void Commit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Commit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.Commit" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Commit ()" />
      <MemberSignature Language="F#" Value="abstract member Commit : unit -&gt; unit" Usage="cloudFileStream.Commit " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c06d-110">このストリームのすべてのバッファーをクリア、基になるファイルに書き込まれるバッファー内のデータおよびファイルをコミットします。</span><span class="sxs-lookup"><span data-stu-id="5c06d-110">Clears all buffers for this stream, causes any buffered data to be written to the underlying file, and commits the file.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCommit">
      <MemberSignature Language="C#" Value="public abstract void EndCommit (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCommit(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.EndCommit(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndCommit (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCommit : IAsyncResult -&gt; unit" Usage="cloudFileStream.EndCommit asyncResult" />
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
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5c06d-111">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="5c06d-111">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="5c06d-112">保留中の非同期コミットを完了するまで待機します。</span><span class="sxs-lookup"><span data-stu-id="5c06d-112">Waits for the pending asynchronous commit to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFlush">
      <MemberSignature Language="C#" Value="public abstract void EndFlush (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFlush(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileStream.EndFlush(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndFlush (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFlush : IAsyncResult -&gt; unit" Usage="cloudFileStream.EndFlush asyncResult" />
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
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="5c06d-113">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="5c06d-113">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="5c06d-114">完了する保留中の非同期のフラッシュを待機します。</span><span class="sxs-lookup"><span data-stu-id="5c06d-114">Waits for the pending asynchronous flush to complete.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>