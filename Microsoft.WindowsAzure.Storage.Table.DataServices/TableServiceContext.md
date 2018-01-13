<Type Name="TableServiceContext" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext">
  <TypeSignature Language="C#" Value="public class TableServiceContext : System.Data.Services.Client.DataServiceContext, IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableServiceContext extends System.Data.Services.Client.DataServiceContext implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public Class TableServiceContext&#xA;Inherits DataServiceContext&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TableServiceContext = class&#xA;    inherit DataServiceContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Services.Client.DataServiceContext</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            表す、 <see cref="T:System.Data.Services.Client.DataServiceContext" /> Windows Azure テーブル サービスで使用するオブジェクト。
            </summary>
    <remarks><see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />クラスは同時実行クエリや要求をサポートしていません。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableServiceContext (Microsoft.WindowsAzure.Storage.Table.CloudTableClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Table.CloudTableClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.#ctor(Microsoft.WindowsAzure.Storage.Table.CloudTableClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (client As CloudTableClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext : Microsoft.WindowsAzure.Storage.Table.CloudTableClient -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext client" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (callback, state)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
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
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (options As SaveChangesOptions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, callback, state)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, requestOptions, operationContext, callback, state)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="requestOptions"></param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns><see cref="T:System.IAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="tableServiceContext.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
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
            TableServiceContext によって使用されているすべてのリソースを解放します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="tableServiceContext.Dispose disposing" />
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
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>true</c>マネージ コードとアンマネージ リソースを解放するには<c>false</c>アンマネージ リソースだけを解放します。</param>
        <summary>
            TableServiceContext によって使用されているアンマネージ リソースを解放し、必要に応じてマネージ リソースも解放します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.EndSaveChangesWithRetries(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndSaveChangesWithRetries (asyncResult As IAsyncResult) As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.EndSaveChangesWithRetries : IAsyncResult -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.EndSaveChangesWithRetries asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            変更を保存する非同期操作を終了します。
            </summary>
        <returns> A<see cref="T:System.Data.Services.Client.DataServiceResponse" />操作の結果を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetries () As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : unit -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries " />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存します。
            </summary>
        <returns>A<see cref="T:System.Data.Services.Client.DataServiceResponse" />操作の結果を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries (options, requestOptions, operationContext)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存します。
            </summary>
        <returns> A<see cref="T:System.Data.Services.Client.DataServiceResponse" />操作の結果を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync () As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync " />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync (options As SaveChangesOptions) As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync options" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync cancellationToken" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, cancellationToken)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext, cancellationToken)" />
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
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><see cref="T:System.Data.Services.Client.SaveChangesOptions" /> 列挙値。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            サービス コンテキストに指定された再試行ポリシーを使用して、変更を保存する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />テーブル サービスを表すオブジェクト。
            </summary>
        <value>テーブル サービスのエンドポイントを指定するクライアント オブジェクトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>