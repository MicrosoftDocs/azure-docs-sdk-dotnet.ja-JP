<Type Name="CloudFileShare" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileShare">
  <TypeSignature Language="C#" Value="public class CloudFileShare" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudFileShare extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudFileShare" />
  <TypeSignature Language="F#" Value="type CloudFileShare = class" />
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
            Microsoft Azure ファイル サービス内の共有を表します。
            </summary>
    <remarks>共有としてカプセル化されるディレクトリを保持する<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />オブジェクト、およびディレクトリのファイルを保持します。 ディレクトリは、サブディレクトリを含めることもできます。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileShare (Uri shareAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri shareAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileShare : Uri -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileShare shareAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="shareAddress">共有の絶対 URI です。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileShare (Microsoft.WindowsAzure.Storage.StorageUri shareAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri shareAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileShare : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileShare (shareAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="shareAddress">共有の絶対 URI です。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileShare (Uri shareAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri shareAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareAddress As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileShare : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileShare (shareAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareAddress" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="shareAddress">共有の絶対 URI です。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileShare (Microsoft.WindowsAzure.Storage.StorageUri shareAddress, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri shareAddress, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareAddress As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileShare : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileShare (shareAddress, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="shareAddress">共有の絶対 URI です。</param>
        <param name="snapshotTime">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileShare (Uri shareAddress, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri shareAddress, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (shareAddress As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileShare : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileShare (shareAddress, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="shareAddress" Type="System.Uri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="shareAddress">共有の絶対 URI です。</param>
        <param name="snapshotTime">A<see cref="T:System.DateTimeOffset" />共有がスナップショットの場合、スナップショットのタイムスタンプを指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginCreate (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有を作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginCreate(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginCreate (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有を作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginCreateIfNotExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginCreateIfNotExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDelete (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有を削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDelete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDelete (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有を削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDelete(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDelete (deleteSnapshotsOption, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有を削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDeleteIfExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDeleteIfExists (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginDeleteIfExists (deleteSnapshotsOption, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有が存在するかどうかを確認する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有が存在するかどうかを確認する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginFetchAttributes (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有の属性を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginFetchAttributes (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有の属性を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginGetPermissions (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のアクセス許可の設定を取得する非同期の要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginGetPermissions(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginGetPermissions (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のアクセス許可の設定を取得する非同期の要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginGetStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginGetStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetStats (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetStats(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginGetStats(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetStats : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetStats : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginGetStats (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetMetadata (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetMetadata (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetPermissions(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As FileSharePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetPermissions (permissions, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のアクセス許可を設定する非同期要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetPermissions(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetPermissions (permissions, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のアクセス許可を設定する非同期要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSetProperties(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSetProperties (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSnapshot (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.BeginSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileShare.BeginSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Create(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.Create (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。 このオブジェクトを使用して、記憶域サービスに要求を追跡して、操作に関する追加のランタイム情報を提供します。 </param>
        <summary>
            共有を作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.CreateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有を作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有を作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.CreateAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有を作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.CreateAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有を作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateIfNotExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileShare.CreateIfNotExists (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在しない場合は、共有を作成します。
            </summary>
        <returns>
          <c>true</c>いて、共有がまだ存在せず作成されたそれ以外の<c>false</c>です。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.CreateIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.CreateIfNotExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.CreateIfNotExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.CreateIfNotExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Delete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.Delete (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Delete(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.Delete (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有を削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.DeleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有を削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有を削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.DeleteAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有を削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.DeleteAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有を削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteAsync(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.DeleteAsync (deleteSnapshotsOption, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有を削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileShare.DeleteIfExists (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在する場合は、共有を削除します。
            </summary>
        <returns>
          <c>true</c>いて、共有がまだ存在せず作成されたそれ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExists(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileShare.DeleteIfExists (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在する場合は、共有を削除します。
            </summary>
        <returns>
          <c>true</c>いて、共有がまだ存在せず作成されたそれ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.DeleteIfExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.DeleteIfExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.DeleteIfExistsAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.DeleteIfExistsAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.DeleteIfExistsAsync (deleteSnapshotsOption, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">A<see cref="T:Microsoft.WindowsAzure.Storage.File.DeleteShareSnapshotsOption" />のみ、共有を削除するか、共有とすべてのスナップショットを削除するかどうかを示すオブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndCreate asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有を作成する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudFileShare.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            既に存在しない場合、共有を作成する非同期の要求の結果を返します。
            </summary>
        <returns>
          <c>true</c>場合、共有がまだ存在せず作成された、それ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndDelete asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有を削除する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudFileShare.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            既に存在する場合に、共有を削除する非同期の要求の結果を返します。
            </summary>
        <returns>
          <c>true</c>場合、共有がまだ存在せず作成された、それ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudFileShare.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有が存在するかどうかを確認する要求の非同期の結果を返します。
            </summary>
        <returns>
          <c>true</c>共有が存在する場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndFetchAttributes asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有の属性を取得する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.FileSharePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.FileSharePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As FileSharePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.FileSharePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.FileSharePermissions" Usage="cloudFileShare.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileSharePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のアクセス許可の設定を取得する要求の非同期の結果を返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats EndGetStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats EndGetStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndGetStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetStats (asyncResult As IAsyncResult) As ShareStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&#xA;override this.EndGetStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" Usage="cloudFileShare.EndGetStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有の統計を取得する非同期操作を終了します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndSetMetadata asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のユーザー定義メタデータを設定するための非同期要求操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndSetPermissions asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のアクセス許可を設定する非同期の要求の結果を返します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndSetProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetProperties : IAsyncResult -&gt; unit" Usage="cloudFileShare.EndSetProperties asyncResult" />
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
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のプロパティを更新する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare EndSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare EndSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.EndSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndSnapshot (asyncResult As IAsyncResult) As CloudFileShare" />
      <MemberSignature Language="F#" Value="member this.EndSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileShare.EndSnapshot asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を終了します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />共有スナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Exists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileShare.Exists (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有が存在するかどうかを確認します。
            </summary>
        <returns>
          <c>true</c>共有が存在する場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.ExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有が存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.ExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有が存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.ExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.ExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有が存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.ExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileShare.ExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有が存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.FetchAttributes (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の属性を取得します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.FetchAttributesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有の属性を取得する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.FetchAttributesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有の属性を取得する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.FetchAttributesAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の属性を取得する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.FetchAttributesAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有の属性を取得する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.FileSharePermissions GetPermissions (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.FileSharePermissions GetPermissions(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetPermissions(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.FileSharePermissions&#xA;override this.GetPermissions : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.FileSharePermissions" Usage="cloudFileShare.GetPermissions (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileSharePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のアクセス許可の設定を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of FileSharePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;" Usage="cloudFileShare.GetPermissionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有のアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;" Usage="cloudFileShare.GetPermissionsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;" Usage="cloudFileShare.GetPermissionsAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;" Usage="cloudFileShare.GetPermissionsAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileSharePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRootDirectoryReference">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileDirectory GetRootDirectoryReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory GetRootDirectoryReference() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetRootDirectoryReference" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRootDirectoryReference () As CloudFileDirectory" />
      <MemberSignature Language="F#" Value="member this.GetRootDirectoryReference : unit -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="cloudFileShare.GetRootDirectoryReference " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileDirectory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            この共有のルート ディレクトリへの参照を返します。
            </summary>
        <returns>ルート ディレクトリへの参照。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessFilePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy -&gt; string" Usage="cloudFileShare.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <summary>
            共有の共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy, string groupPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy, string groupPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessFilePolicy, groupPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy * string -&gt; string" Usage="cloudFileShare.GetSharedAccessSignature (policy, groupPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <param name="groupPolicyIdentifier">共有レベルのアクセス ポリシー。</param>
        <summary>
            共有の共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy, string groupPolicyIdentifier, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy policy, string groupPolicyIdentifier, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudFileShare.GetSharedAccessSignature (policy, groupPolicyIdentifier, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFilePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <param name="groupPolicyIdentifier">共有レベルのアクセス ポリシー。</param>
        <param name="protocols">許可されているプロトコル (https のみ、または http と https)。 プロトコルを制限したくない場合は null です。</param>
        <param name="ipAddressOrRange">許可されている IP アドレスまたは IP アドレスの範囲を実行します。 Null を制限したくない場合は、IP アドレスに基づいています。</param>
        <summary>
            共有の共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats GetStats (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats GetStats(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetStats(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetStats : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&#xA;override this.GetStats : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" Usage="cloudFileShare.GetStats (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の統計情報を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetStatsAsync () As Task(Of ShareStats)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;&#xA;override this.GetStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;" Usage="cloudFileShare.GetStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;&#xA;override this.GetStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;" Usage="cloudFileShare.GetStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetStatsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;&#xA;override this.GetStatsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;" Usage="cloudFileShare.GetStatsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt; GetStatsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.GetStatsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;&#xA;override this.GetStatsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;" Usage="cloudFileShare.GetStatsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有の統計を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ShareStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSnapshot">
      <MemberSignature Language="C#" Value="public bool IsSnapshot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSnapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.IsSnapshot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSnapshot As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSnapshot : bool" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.IsSnapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この共有は、スナップショットであるかどうかを示す値を取得します。
            </summary>
        <value>
          <c>true</c>この共有はスナップショットである場合は、それ以外の場合、 <c>false</c>です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有のメタデータを取得します。
            </summary>
        <value>共有のメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有の名前を取得します。
            </summary>
        <value>共有の名前です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileShareProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileShareProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileShareProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.File.FileShareProperties" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileShareProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有のシステム プロパティを取得します。
            </summary>
        <value>共有のプロパティです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudFileClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有のサービス クライアントを取得します。
            </summary>
        <value>ファイル サービスのエンドポイントを指定するクライアント オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.SetMetadata (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のユーザー定義メタデータを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetMetadataAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetMetadataAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetMetadataAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetMetadataAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />共有のアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のユーザー定義メタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPermissions(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.SetPermissions (permissions, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileSharePermissions" /> オブジェクト。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のアクセス許可を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.File.FileSharePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As FileSharePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPermissionsAsync permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <summary>
            共有のアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPermissionsAsync (permissions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPermissionsAsync (permissions, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.File.FileSharePermissions permissions, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.File.FileSharePermissions,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.File.FileSharePermissions * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPermissionsAsync (permissions, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.File.FileSharePermissions" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">共有に適用するアクセス許可。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public virtual void SetProperties (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetProperties(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetProperties(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileShare.SetProperties (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のプロパティを更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPropertiesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPropertiesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPropertiesAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SetPropertiesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileShare.SetPropertiesAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のプロパティを更新する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare Snapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare Snapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Snapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.Snapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileShare.Snapshot (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> 、要求の追加オプションを指定するオブジェクトまたは<c>null</c>です。 場合<c>null</c>既定のオプションは、要求に適用されます。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のスナップショットを作成します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />共有スナップショットであるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function SnapshotAsync () As Task(Of CloudFileShare)" />
      <MemberSignature Language="F#" Value="member this.SnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileShare.SnapshotAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileShare.SnapshotAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileShare.SnapshotAsync (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; SnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileShare.SnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="metadata">スナップショットのメタデータを定義する名前と値のペアのコレクション。</param>
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />要求を続行するために満たす必要がある条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のスナップショットを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotQualifiedStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotQualifiedStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            両方のプライマリとセカンダリの場所、共有がスナップショットの場合は、クエリ文字列情報を含むは、共有の URI を取得します。
            </summary>
        <value>型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.StorageUri" />共有がスナップショットの場合、スナップショットのクエリ情報を共有の Uri の両方、プライマリとセカンダリの場所などを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedUri">
      <MemberSignature Language="C#" Value="public Uri SnapshotQualifiedUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SnapshotQualifiedUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotQualifiedUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedUri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotQualifiedUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有がスナップショットの場合は、クエリ文字列情報を含む、共有への絶対 URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />共有がスナップショットの場合は、スナップショットのクエリ情報を含む、共有への絶対 URI を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この共有がスナップショットの場合は、共有のスナップショットが作成された日時を取得します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />を含む、共有のスナップショットをそれ以外の場合は、共有が、スナップショット時間<c>null</c>です。</value>
        <remarks>
            このプロパティの値は、共有がスナップショットでない場合は、 <c>null</c>です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべての場所の Uri の一覧を取得します。
            </summary>
        <value>すべての場所の Uri の一覧です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileShare.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileShare.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            共有の URI を取得します。
            </summary>
        <value>共有の絶対 URI です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>