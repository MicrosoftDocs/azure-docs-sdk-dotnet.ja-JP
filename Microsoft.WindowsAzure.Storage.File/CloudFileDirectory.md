<Type Name="CloudFileDirectory" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory">
  <TypeSignature Language="C#" Value="public class CloudFileDirectory : Microsoft.WindowsAzure.Storage.File.IListFileItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudFileDirectory extends System.Object implements class Microsoft.WindowsAzure.Storage.File.IListFileItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudFileDirectory&#xA;Implements IListFileItem" />
  <TypeSignature Language="F#" Value="type CloudFileDirectory = class&#xA;    interface IListFileItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.File.IListFileItem</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            区切り文字で指定されたファイルのディレクトリを表します。
            </summary>
    <remarks>としてカプセル化される共有<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />オブジェクト、ディレクトリ、およびディレクトリのファイルを保持します。 ディレクトリは、サブディレクトリを含めることもできます。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileDirectory (Uri directoryAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri directoryAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directoryAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory : Uri -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory directoryAbsoluteUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directoryAbsoluteUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="directoryAbsoluteUri">A<see cref="T:System.Uri" />ディレクトリの絶対 URI を含むオブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />クラス ディレクトリへの絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileDirectory (Microsoft.WindowsAzure.Storage.StorageUri directoryAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri directoryAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directoryAbsoluteUri As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory (directoryAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directoryAbsoluteUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="directoryAbsoluteUri">A<see cref="T:System.Uri" />ディレクトリの絶対 URI を含むオブジェクト。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />クラス ディレクトリへの絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileDirectory (Uri directoryAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri directoryAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (directoryAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileDirectory (directoryAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="directoryAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="directoryAbsoluteUri">A<see cref="T:System.Uri" />ディレクトリの絶対 URI を含むオブジェクト。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />クラス ディレクトリへの絶対 URI を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginCreate (callback, state)" />
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
            ディレクトリを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginCreate(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginCreate (options, operationContext, callback, state)" />
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
            ディレクトリを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginCreateIfNotExists (callback, state)" />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginCreateIfNotExists (options, operationContext, callback, state)" />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginDelete (callback, state)" />
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
            ディレクトリを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginDelete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginDelete (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ディレクトリを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginDeleteIfExists (callback, state)" />
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
            既に存在する場合、ディレクトリを削除する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginDeleteIfExists (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在する場合、ディレクトリを削除する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginExists (callback, state)" />
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
            ディレクトリが存在するかどうかを確認する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginExists (options, operationContext, callback, state)" />
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
            ディレクトリが存在するかどうかを確認する非同期要求を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginFetchAttributes (callback, state)" />
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
            ディレクトリのプロパティを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginFetchAttributes (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ファイルのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginListFilesAndDirectoriesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListFilesAndDirectoriesSegmented (currentToken As FileContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListFilesAndDirectoriesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListFilesAndDirectoriesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginListFilesAndDirectoriesSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented (Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented(valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginListFilesAndDirectoriesSegmented(System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListFilesAndDirectoriesSegmented : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListFilesAndDirectoriesSegmented : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginListFilesAndDirectoriesSegmented (maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListFilesAndDirectoriesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginListFilesAndDirectoriesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginListFilesAndDirectoriesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginListFilesAndDirectoriesSegmented (prefix, maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">ファイルまたはディレクトリ名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginSetMetadata (callback, state)" />
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
            ディレクトリのメタデータを更新する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.BeginSetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileDirectory.BeginSetMetadata (accessCondition, options, operationContext, callback, state)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback">非同期操作の完了時に通知を受け取るコールバック デリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            ディレクトリのメタデータを更新する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Create(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileDirectory.Create (requestOptions, operationContext)" />
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
        <param name="requestOptions"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。 このオブジェクトを使用して、記憶域サービスに要求を追跡して、操作に関する追加のランタイム情報を提供します。 </param>
        <summary>
            ディレクトリを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.CreateAsync " />
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
            ディレクトリを作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.CreateAsync cancellationToken" />
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
            ディレクトリを作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.CreateAsync (options, operationContext)" />
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
            ディレクトリを作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.CreateAsync (options, operationContext, cancellationToken)" />
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
            ディレクトリを作成する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateIfNotExists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileDirectory.CreateIfNotExists (requestOptions, operationContext)" />
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
            既に存在しない場合は、ディレクトリを作成します。
            </summary>
        <returns>
          <c>true</c>ディレクトリがまだ存在せず、作成されたそれ以外の場合<c>false</c>です。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.CreateIfNotExistsAsync " />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.CreateIfNotExistsAsync cancellationToken" />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.CreateIfNotExistsAsync (options, operationContext)" />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.CreateIfNotExistsAsync (options, operationContext, cancellationToken)" />
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
            既に存在しない場合は、ディレクトリを作成する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>この API は、作成または書き込みアクセス許可が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Delete(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileDirectory.Delete (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.DeleteAsync " />
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
            ディレクトリを削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.DeleteAsync cancellationToken" />
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
            ディレクトリを削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.DeleteAsync (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリを削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.DeleteAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ディレクトリを削除する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteIfExists(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileDirectory.DeleteIfExists (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在する場合は、ディレクトリを削除します。
            </summary>
        <returns>
          <c>true</c>ディレクトリが既に存在し、削除された場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.DeleteIfExistsAsync " />
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
            既に存在する場合、ディレクトリを削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.DeleteIfExistsAsync cancellationToken" />
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
            既に存在する場合、ディレクトリを削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.DeleteIfExistsAsync (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在する場合、ディレクトリを削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.DeleteIfExistsAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在する場合、ディレクトリを削除する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudFileDirectory.EndCreate asyncResult" />
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
            ディレクトリを作成する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudFileDirectory.EndCreateIfNotExists asyncResult" />
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
            既に存在しない場合は、ディレクトリを作成する非同期の要求の結果を返します。
            </summary>
        <returns>
          <c>true</c>場合、ディレクトリがまだ存在せず作成された、それ以外の<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudFileDirectory.EndDelete asyncResult" />
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
            ディレクトリを削除する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudFileDirectory.EndDeleteIfExists asyncResult" />
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
            既に存在する場合、ディレクトリを削除する非同期の要求の結果を返します。
            </summary>
        <returns>
          <c>true</c>いて、ディレクトリが既に存在して削除された、 <c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudFileDirectory.EndExists asyncResult" />
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
            ディレクトリが存在するかどうかを確認する要求の非同期の結果を返します。
            </summary>
        <returns>
          <c>true</c>ディレクトリが存在する場合<c>false</c>、それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudFileDirectory.EndFetchAttributes asyncResult" />
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
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.FileResultSegment EndListFilesAndDirectoriesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.FileResultSegment EndListFilesAndDirectoriesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndListFilesAndDirectoriesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListFilesAndDirectoriesSegmented (asyncResult As IAsyncResult) As FileResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListFilesAndDirectoriesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment&#xA;override this.EndListFilesAndDirectoriesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment" Usage="cloudFileDirectory.EndListFilesAndDirectoriesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を終了します。
            </summary>
        <returns>実装するオブジェクトを含む結果セグメント<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudFileDirectory.EndSetMetadata asyncResult" />
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
            ディレクトリのメタデータを更新する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Exists(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudFileDirectory.Exists (requestOptions, operationContext)" />
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
            ディレクトリが存在するかどうかを確認します。
            </summary>
        <returns>
          <c>true</c>ディレクトリが存在する場合<c>false</c>、それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.ExistsAsync " />
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
            ディレクトリが存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.ExistsAsync cancellationToken" />
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
            ディレクトリが存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.ExistsAsync (options, operationContext)" />
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
            ディレクトリが存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ExistsAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudFileDirectory.ExistsAsync (options, operationContext, cancellationToken)" />
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
            ディレクトリが存在するかどうかを確認する非同期要求を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileDirectory.FetchAttributes (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリのプロパティを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.FetchAttributesAsync " />
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
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.FetchAttributesAsync cancellationToken" />
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
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.FetchAttributesAsync (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ファイルのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.FetchAttributesAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ファイルのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ディレクトリのプロパティおよびメタデータを設定する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectoryReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.CloudFileDirectory GetDirectoryReference (string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory GetDirectoryReference(string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.GetDirectoryReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetDirectoryReference (itemName As String) As CloudFileDirectory" />
      <MemberSignature Language="F#" Value="abstract member GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory&#xA;override this.GetDirectoryReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="cloudFileDirectory.GetDirectoryReference itemName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileDirectory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="itemName">A<see cref="T:System.String" />サブディレクトリの名前を含むです。</param>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />をこのディレクトリ内のサブディレクトリを表すオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.CloudFile GetFileReference (string fileName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.CloudFile GetFileReference(string fileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.GetFileReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetFileReference (fileName As String) As CloudFile" />
      <MemberSignature Language="F#" Value="abstract member GetFileReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFile&#xA;override this.GetFileReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFile" Usage="cloudFileDirectory.GetFileReference fileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fileName">A<see cref="T:System.String" />ファイルの名前を含むです。</param>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" />をこのディレクトリ内のファイルを表すオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFile" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectories">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; ListFilesAndDirectories (Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; ListFilesAndDirectories(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectories(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectories : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;&#xA;override this.ListFilesAndDirectories : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;" Usage="cloudFileDirectory.ListFilesAndDirectories (options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            遅延取得されると、共有内のファイルの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; ListFilesAndDirectories (string prefix, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; ListFilesAndDirectories(string prefix, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectories(System.String,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListFilesAndDirectories : string * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;" Usage="cloudFileDirectory.ListFilesAndDirectories (prefix, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">ファイルまたはディレクトリ名のプレフィックスを含む文字列。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            遅延取得されると、共有内のファイルの列挙可能なコレクションを返します。
            </summary>
        <returns>実装するオブジェクトの列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />遅れてが取得されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListFilesAndDirectoriesSegmented (currentToken As FileContinuationToken) As FileResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment&#xA;override this.ListFilesAndDirectoriesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返します。
            </summary>
        <returns>実装するオブジェクトを含む結果セグメント<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented (Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented(valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmented(System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmented : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment&#xA;override this.ListFilesAndDirectoriesSegmented : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmented (maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返します。
            </summary>
        <returns>実装するオブジェクトを含む結果セグメント<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.FileResultSegment ListFilesAndDirectoriesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ListFilesAndDirectoriesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.FileResultSegment" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmented (prefix, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">ファイルまたはディレクトリ名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返します。
            </summary>
        <returns>実装するオブジェクトを含む結果セグメント<see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListFilesAndDirectoriesSegmentedAsync (currentToken As FileContinuationToken) As Task(Of FileResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync (prefix, currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">ファイルまたはディレクトリ名のプレフィックスを含む文字列。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync (maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync (maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFilesAndDirectoriesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt; ListFilesAndDirectoriesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFilesAndDirectoriesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;&#xA;override this.ListFilesAndDirectoriesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;" Usage="cloudFileDirectory.ListFilesAndDirectoriesSegmentedAsync (prefix, maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.FileResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">ファイルまたはディレクトリ名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">前の一覧作成操作によって返される継続トークンです。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            共有のファイル項目のコレクションを含む結果セグメントを返す非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Metadata" />
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
            ディレクトリのユーザー定義メタデータを取得します。
            </summary>
        <value>名前と値のペアのコレクションとしてのディレクトリのメタデータ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Name" />
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
            ディレクトリの名前を取得します。
            </summary>
        <value>A<see cref="T:System.String" />ディレクトリの名前を含むです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileDirectory Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileDirectory Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As CloudFileDirectory" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Parent" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Parent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" />ディレクトリの親ディレクトリを表すオブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As FileDirectoryProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties" />ディレクトリのシステム プロパティを表すオブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.File.FileDirectoryProperties" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudFileClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.ServiceClient" />
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
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" />ファイル サービスのエンドポイントを指定するオブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileDirectory.SetMetadata (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options"><see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリのメタデータを更新します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.SetMetadataAsync " />
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
            ディレクトリのメタデータを更新する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.SetMetadataAsync cancellationToken" />
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
            ディレクトリのメタデータを更新する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.SetMetadataAsync (accessCondition, options, operationContext)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            ディレクトリのメタデータを更新する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileDirectory.SetMetadataAsync (accessCondition, options, operationContext, cancellationToken)" />
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
        <param name="accessCondition"><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />ディレクトリのアクセス条件を表すオブジェクト。 場合<c>null</c>条件は使用されません。</param>
        <param name="options">A<see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            ディレクトリのメタデータを更新する非同期操作を実行するタスクを返します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />を現在の操作を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Share">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare Share { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare Share" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Share" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Share As CloudFileShare" />
      <MemberSignature Language="F#" Value="member this.Share : Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Share" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Share</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" />ディレクトリの共有を表すオブジェクト。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SnapshotQualifiedStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SnapshotQualifiedStorageUri" />
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
            両方のプライマリとセカンダリの場所のディレクトリの共有がスナップショットの場合は、クエリ文字列情報を含むディレクトリの URI を取得します。
            </summary>
        <value>型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.StorageUri" />ディレクトリの共有がスナップショットの場合、スナップショットのクエリ情報をディレクトリの Uri の両方、プライマリとセカンダリの場所などを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedUri">
      <MemberSignature Language="C#" Value="public Uri SnapshotQualifiedUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SnapshotQualifiedUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SnapshotQualifiedUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedUri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.SnapshotQualifiedUri" />
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
            ディレクトリの共有がスナップショットの場合は、クエリ文字列情報を含むディレクトリへの絶対 URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />ディレクトリの共有がスナップショットの場合は、スナップショットのクエリ情報を含むディレクトリへの絶対 URI を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.StorageUri" />
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
            すべての場所のファイル ディレクトリの Uri を取得します。
            </summary>
        <value>A<see cref="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.StorageUri" />すべての場所のファイル ディレクトリの Uri を含むオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileDirectory.Uri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.File.IListFileItem.Uri</InterfaceMember>
      </Implements>
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
            プライマリの場所のディレクトリの URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />プライマリの場所に存在するディレクトリの絶対 URI を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>