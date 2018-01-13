<Type Name="CloudBlobStream" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream">
  <TypeSignature Language="C#" Value="public abstract class CloudBlobStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit CloudBlobStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class CloudBlobStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type CloudBlobStream = class&#xA;    inherit Stream" />
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
            Blob に書き込むためのストリームを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected CloudBlobStream ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.#ctor" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.BeginCommit(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginCommit (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCommit : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobStream.BeginCommit (callback, state)" />
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
        <param name="callback">コミットが完了すると呼び出されるオプションの非同期コールバック。</param>
        <param name="state">この特定の非同期コミット要求を他の要求と区別するユーザー指定のオブジェクト。</param>
        <summary>
            非同期のコミット操作を開始します。
            </summary>
        <returns><c>ICancellableAsyncResult</c>を表す非同期のコミットは、保留になっている可能性があります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFlush">
      <MemberSignature Language="C#" Value="public abstract Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFlush(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.BeginFlush(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function BeginFlush (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFlush : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlobStream.BeginFlush (callback, state)" />
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
        <param name="callback">フラッシュの完了時に呼び出されるオプションの非同期コールバック。</param>
        <param name="state">この特定の非同期フラッシュ要求を他の要求と区別するために使用するユーザー指定のオブジェクト。</param>
        <summary>
            非同期のフラッシュ操作を開始します。
            </summary>
        <returns><c>ICancellableAsyncResult</c>を表す非同期のフラッシュを保留になっている可能性があります。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public abstract void Commit ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Commit() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.Commit" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Commit ()" />
      <MemberSignature Language="F#" Value="abstract member Commit : unit -&gt; unit" Usage="cloudBlobStream.Commit " />
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
            このストリームのすべてのバッファーをクリア、基になる blob に書き込まれるバッファー内のデータし、blob をコミットします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCommit">
      <MemberSignature Language="C#" Value="public abstract void EndCommit (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCommit(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.EndCommit(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndCommit (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCommit : IAsyncResult -&gt; unit" Usage="cloudBlobStream.EndCommit asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />を終了させる保留中の非同期リクエストへの参照を含むオブジェクト。</param>
        <summary>
            保留中の非同期コミットを完了するまで待機します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFlush">
      <MemberSignature Language="C#" Value="public abstract void EndFlush (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFlush(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlobStream.EndFlush(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub EndFlush (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFlush : IAsyncResult -&gt; unit" Usage="cloudBlobStream.EndFlush asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />を終了させる保留中の非同期リクエストへの参照を含むオブジェクト。</param>
        <summary>
            完了する保留中の非同期のフラッシュを待機します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>