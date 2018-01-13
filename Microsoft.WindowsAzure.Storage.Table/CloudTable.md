<Type Name="CloudTable" FullName="Microsoft.WindowsAzure.Storage.Table.CloudTable">
  <TypeSignature Language="C#" Value="public class CloudTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTable" />
  <TypeSignature Language="F#" Value="type CloudTable = class" />
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
            Microsoft Azure テーブルを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTable : Uri -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTable tableAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tableAddress">A<see cref="T:System.Uri" />テーブルへの絶対 URI を指定します。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Microsoft.WindowsAzure.Storage.StorageUri tableAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri tableAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTable : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTable (tableAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAddress">A<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.StorageUri" />プライマリとセカンダリの両方の場所にあるテーブルに対して絶対 URI を格納します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTable : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTable (tableAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAbsoluteUri">A<see cref="T:System.Uri" />テーブルへの絶対 URI を指定します。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (callback, state)" />
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
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginCreate(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (callback, state)" />
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
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (callback, state)" />
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
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginDelete(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (callback, state)" />
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
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecute(Microsoft.WindowsAzure.Storage.Table.TableOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecute (operation As TableOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.WindowsAzure.Storage.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.WindowsAzure.Storage.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            非同期のテーブル操作の実行を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecute(Microsoft.WindowsAzure.Storage.Table.TableOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            非同期のテーブル操作の実行を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteBatch(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteBatch (batch As TableBatchOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteBatch(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQueryForKeyRotationSegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化されたクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化されたクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルをクエリして、指定された適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            セグメント化モードでクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (callback, state)" />
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
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginExists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (callback, state)" />
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
            テーブルのアクセス許可の設定を取得する非同期の要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginGetPermissions(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルのアクセス許可の設定を取得する非同期の要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Table.TablePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As TablePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Table.TablePermissions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期要求を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.Create(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudTable.Create (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync " />
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
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync cancellationToken" />
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
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateIfNotExists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudTable.CreateIfNotExists (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在しない場合は、テーブルを作成します。
            </summary>
        <returns>
          <c>true</c>テーブルが作成された、それ以外の場合は<c>false</c>です。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync " />
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
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync cancellationToken" />
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
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            既に存在しない場合は、テーブルを作成する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>この API は、存在の確認を実行し、したがってリスト権限が必要です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; CreateQuery&lt;TElement&gt; () where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; CreateQuery&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.CreateQuery``1" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateQuery(Of TElement As {ITableEntityNew}) () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.CreateQuery : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <summary>
            LINQ を使用して、クエリを作成するファクトリ メソッドを変更できます。 クエリ、後で実行できますの使用可能な実行方法のいずれかを使用して<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />など<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuery(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />、 <see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />、または<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />です。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />オブジェクト、型に特化した<c>TElement</c>を後で実行できます。</returns>
        <remarks>
            <see cref="N:Microsoft.WindowsAzure.Storage.Table.Queryable" />名前空間には拡張メソッドが含まれています、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />オブジェクトを含む<see cref="M:WithOptions" />、 <see cref="M:WithContext" />、および<see cref="M:AsTableQuery" />です。 これらのメソッドを使用するのには、<c>を使用して</c>を参照するステートメント、<see cref="N:Microsoft.WindowsAzure.Storage.Table.Queryable" />名前空間。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.Delete(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudTable.Delete (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync " />
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
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync cancellationToken" />
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
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteIfExists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudTable.DeleteIfExists (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            存在する場合は、テーブルを削除します。
            </summary>
        <returns>
          <c>true</c>テーブルが削除された、それ以外の場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync " />
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
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync cancellationToken" />
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
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            存在する場合は、テーブルを削除する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudTable.EndCreate asyncResult" />
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
            テーブルを作成する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndCreateIfNotExists asyncResult" />
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
            既に存在しない場合は、テーブルを作成する非同期操作を終了します。
            </summary>
        <returns>
          <c>true</c>テーブルが作成された、それ以外の場合は<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudTable.EndDelete asyncResult" />
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
            テーブルを削除する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndDeleteIfExists asyncResult" />
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
            存在する場合は、テーブルを削除する非同期操作を終了します。
            </summary>
        <returns>
          <c>true</c>テーブルが削除された、それ以外の場合<c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResult EndExecute (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResult EndExecute(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecute(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecute (asyncResult As IAsyncResult) As TableResult" />
      <MemberSignature Language="F#" Value="abstract member EndExecute : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResult&#xA;override this.EndExecute : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResult" Usage="cloudTable.EndExecute asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            非同期のテーブル操作の実行を終了します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />テーブルに対する操作の実行結果を含むです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; EndExecuteBatch (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; EndExecuteBatch(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecuteBatch(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteBatch (asyncResult As IAsyncResult) As IList(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.EndExecuteBatch asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を終了します。
            </summary>
        <returns>型の列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />内の各操作の順序で、結果を含む、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルにします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecuteQueryForKeyRotationSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQueryForKeyRotationSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of KeyRotationEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&#xA;override this.EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;" Usage="cloudTable.EndExecuteQueryForKeyRotationSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを終了します。 
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />クエリの実行結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecuteQuerySegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of DynamicTableEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テーブルで、非同期のセグメント化されたクエリを終了します。 
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />クエリの実行結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt; (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecuteQuerySegmented``1(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TResult) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">返される結果の型。 Begin で指定されたエンティティ型または競合回避モジュールの結果の型を指定できます。</typeparam>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を終了します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />クエリの実行結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TElement,TResult&gt; (IAsyncResult asyncResult) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExecuteQuerySegmented``2(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            セグメント化モードでクエリを実行する非同期操作を終了します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />を含む型に射影<c>TResult</c>クエリの実行の結果。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndExists asyncResult" />
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
            テーブルが存在するかどうかを判断する非同期操作を終了します。
            </summary>
        <returns>
          <c>true</c>テーブルが存在する場合は、それ以外の場合、 <c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TablePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TablePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As TablePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TablePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TablePermissions" Usage="cloudTable.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テーブルのアクセス許可の設定を取得する要求の非同期の結果を返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudTable.EndSetPermissions asyncResult" />
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
            テーブルのアクセス許可の設定を取得する要求の非同期の結果を返します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResult Execute (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResult Execute(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.Execute(Microsoft.WindowsAzure.Storage.Table.TableOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResult&#xA;override this.Execute : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResult" Usage="cloudTable.Execute (operation, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対する操作を実行します。  
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync (Microsoft.WindowsAzure.Storage.Table.TableOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteAsync(Microsoft.WindowsAzure.Storage.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteAsync (operation As TableOperation) As Task(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync operation" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <summary>
            非同期のテーブル操作を実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteAsync(Microsoft.WindowsAzure.Storage.Table.TableOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            非同期のテーブル操作を実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteAsync(Microsoft.WindowsAzure.Storage.Table.TableOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            非同期のテーブル操作を実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync (Microsoft.WindowsAzure.Storage.Table.TableOperation operation, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteAsync(class Microsoft.WindowsAzure.Storage.Table.TableOperation operation, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteAsync(Microsoft.WindowsAzure.Storage.Table.TableOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.WindowsAzure.Storage.Table.TableOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.WindowsAzure.Storage.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableOperation" />を実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            非同期のテーブル操作を実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteBatch (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt; ExecuteBatch(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteBatch(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&#xA;override this.ExecuteBatch : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;" Usage="cloudTable.ExecuteBatch (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            分割不可能な操作として、テーブルに対するバッチ操作を実行します。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />オブジェクト内の各操作の順序で、結果を含む、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルにします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteBatchAsync(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteBatchAsync (batch As TableBatchOperation) As Task(Of IList(Of TableResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync batch" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteBatchAsync(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteBatchAsync(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.WindowsAzure.Storage.Table.TableBatchOperation batch, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteBatchAsync(Microsoft.WindowsAzure.Storage.Table.TableBatchOperation,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.WindowsAzure.Storage.Table.TableBatchOperation * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Storage.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルに対する操作のバッチを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResult" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; ExecuteQuery (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; ExecuteQuery(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuery(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対するクエリを実行しの列挙可能なコレクションを返します<see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />オブジェクト。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />をクエリによって返されるテーブル エンティティを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; ExecuteQuery&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TElement&gt; ExecuteQuery&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuery``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">型のテーブルをクエリし、使用するクエリ パラメーターを指定して TableQuery インスタンスに特殊化<c>TElement</c>です。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対するクエリを実行します。
            </summary>
        <returns>型の列挙可能なコレクションに特殊化<c>TElement</c>クエリの実行の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuery``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Result&gt;&#xA;override this.ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Result&gt;" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対するクエリを実行し、指定された適用<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>型に射影を含む列挙可能なコレクション<c>TResult</c>クエリの実行の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuery``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            クエリを実行し、指定された適用<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>型に射影を含む列挙可能なコレクション<c>TResult</c>クエリの実行の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotation">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotation(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotation : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotation : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotation (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルに対するクエリを実行しの列挙可能なコレクションを返します<see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />オブジェクト。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />をクエリによって返されるテーブル エンティティを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotationSegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのセグメント化されたクエリを実行し、返します、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />を含む<see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />オブジェクト。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity" />クエリの実行結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQueryForKeyRotationSegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of KeyRotationEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.Storage.Table.CloudTable/&lt;ExecuteQueryForKeyRotationSegmentedAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; ExecuteQuerySegmented (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt; ExecuteQuerySegmented(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmented(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのセグメント化されたクエリを実行し、返します、<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />を含む<see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />オブジェクト。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />クエリの実行結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt; ExecuteQuerySegmented&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TElement&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルに対するクエリを実行します。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />型に対して特殊化されて、 <c>TElement</c>クエリの実行の結果を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルでセグメント化されたクエリを実行し、指定された適用<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />クエリの実行結果を含むオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmented``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セグメント化モードでクエリを実行し、指定された適用<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />を含む型に射影<c>TResult</c>クエリの実行の結果。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of DynamicTableEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;class Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />を表すクエリを実行します。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルにセグメント化されたクエリを実行する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化モードでテーブルをクエリする非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <summary>
            セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.WindowsAzure.Storage.Table.TableQuery,Microsoft.WindowsAzure.Storage.Table.EntityResolver{``0},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <summary>
            セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.WindowsAzure.Storage.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.WindowsAzure.Storage.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken token, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.WindowsAzure.Storage.Table.TableQuery{``0},Microsoft.WindowsAzure.Storage.Table.EntityResolver{``1},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;'Result&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.WindowsAzure.Storage.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.WindowsAzure.Storage.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">クエリのエンティティ型。</typeparam>
        <typeparam name="TResult">先の種類、<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />クエリ結果の射影されます。</typeparam>
        <param name="query">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</param>
        <param name="resolver"><see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</param>
        <param name="token">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityResolver`1" />結果にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.Exists(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudTable.Exists (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルが存在するかどうかを確認します。
            </summary>
        <returns>
          <c>true</c>テーブルが存在する場合は、それ以外の場合、 <c>false</c>です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync " />
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
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync cancellationToken" />
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
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ExistsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルが存在するかどうかを判断する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TablePermissions GetPermissions (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TablePermissions GetPermissions(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetPermissions(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TablePermissions&#xA;override this.GetPermissions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TablePermissions" Usage="cloudTable.GetPermissions (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのアクセス許可の設定を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of TablePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブルのアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルのアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルのアクセス許可の設定を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy -&gt; string" Usage="cloudTable.GetSharedAccessSignature policy" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <summary>
            テーブルの共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
        <exception cref="T:System.InvalidOperationException">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <param name="accessPolicyIdentifier">保存されているアクセス ポリシーを識別する文字列。</param>
        <summary>
            テーブルの共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
        <exception cref="T:System.InvalidOperationException">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String, startPartitionKey As String, startRowKey As String, endPartitionKey As String, endRowKey As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy * string * string * string * string * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey)" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <param name="accessPolicyIdentifier">保存されているアクセス ポリシーを識別する文字列。</param>
        <param name="startPartitionKey">開始パーティション キーを指定する文字列または<c>null</c>です。</param>
        <param name="startRowKey">開始行キーを指定する文字列または<c>null</c>です。</param>
        <param name="endPartitionKey">終了パーティション キーを指定する文字列または<c>null</c>です。</param>
        <param name="endRowKey">終了行キーを指定する文字列または<c>null</c>です。</param>
        <summary>
            テーブルの共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
        <exception cref="T:System.InvalidOperationException">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy * string * string * string * string * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey, protocols, ipAddressOrRange)" />
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
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</param>
        <param name="accessPolicyIdentifier">保存されているアクセス ポリシーを識別する文字列。</param>
        <param name="startPartitionKey">開始パーティション キーを指定する文字列または<c>null</c>です。</param>
        <param name="startRowKey">開始行キーを指定する文字列または<c>null</c>です。</param>
        <param name="endPartitionKey">終了パーティション キーを指定する文字列または<c>null</c>です。</param>
        <param name="endRowKey">終了行キーを指定する文字列または<c>null</c>です。</param>
        <param name="protocols">許可されているプロトコル (https のみ、または http と https)。 プロトコルを制限したくない場合は null です。</param>
        <param name="ipAddressOrRange">許可されている IP アドレスまたは IP アドレスの範囲を実行します。 Null を制限したくない場合は、IP アドレスに基づいています。</param>
        <summary>
            テーブルの共有アクセス署名を返します。
            </summary>
        <returns>URI クエリ文字列としての共有アクセス署名します。</returns>
        <remarks>返されるクエリ文字列には、先頭に疑問符が含まれています。</remarks>
        <exception cref="T:System.InvalidOperationException">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTable.Name" />
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
            テーブルの名前を取得します。
            </summary>
        <value>テーブルの名前を含む文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTable.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />テーブル サービスを表すオブジェクト。
            </summary>
        <value>A<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.SetPermissions(Microsoft.WindowsAzure.Storage.Table.TablePermissions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudTable.SetPermissions (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのアクセス許可の設定を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As TablePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TablePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TablePermissions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Table.TablePermissions permissions, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Table.TablePermissions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Table.TablePermissions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルのアクセス許可を設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTable.StorageUri" />
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
            プライマリとセカンダリの両方の場所のテーブルの Uri を取得します。
            </summary>
        <value>型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.StorageUri" />テーブルの Uri は、プライマリとセカンダリの両方の場所を格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cloudTable.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブルの名前を返します。
            </summary>
        <returns>テーブルの名前を含む文字列。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTable.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTable.Uri" />
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
            プライマリの場所のテーブルの URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />プライマリの場所にあるテーブルに対して絶対 URI を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>