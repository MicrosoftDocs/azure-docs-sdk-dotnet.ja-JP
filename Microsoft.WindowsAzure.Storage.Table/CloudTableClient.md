<Type Name="CloudTableClient" FullName="Microsoft.WindowsAzure.Storage.Table.CloudTableClient">
  <TypeSignature Language="C#" Value="public class CloudTableClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTableClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTableClient" />
  <TypeSignature Language="F#" Value="type CloudTableClient = class" />
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
            Microsoft Azure Table サービスのクライアント側の論理表現を提供します。 このクライアントを使用してを構成およびテーブル サービスに対する要求を実行します。
            </summary>
    <remarks>サービス クライアントは、エンドポイントまたはテーブル サービスのエンドポイントをカプセル化します。 サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</remarks>
    <remarks>CloudTableClient オブジェクトは、テーブル サービスのベース URI をカプセル化します。 サービス クライアントを認証済みアクセスに使用する場合、ストレージ アカウントにアクセスするための資格情報もカプセル化します。</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri">A<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="new Microsoft.WindowsAzure.Storage.Table.CloudTableClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri">A<see cref="T:System.Uri" />を使用してクライアントを作成するテーブル サービスのエンドポイントを含むオブジェクト。</param>
        <param name="credentials"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />クラス、指定されたテーブル サービス エンドポイントとアカウントの資格情報を使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または HTTP 要求の署名に使用する認証スキームを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>共有キーまたは共有キー Lite の資格情報が使用される場合にのみ、このプロパティを設定します。共有アクセス署名または匿名アクセス経由での認証には適用されません。</para>
          <para>WCF Data Services に基づく、従来のテーブル サービス API を使用している場合で、認証方式が使用に注意してください、<see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />オブジェクトは常に共有キー Lite、このプロパティの値に関係なく。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BaseUri" />
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
            プライマリの場所の Table サービス クライアントのベース URI を取得します。
            </summary>
        <value>A<see cref="T:System.Uri" />プライマリの場所の Table サービス クライアントを構築するために使用されるベース URI を含むオブジェクトします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (callback, state)" />
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
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
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
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (callback, state)" />
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
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
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
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (prefix As String, currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="requestOptions">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="callback"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</param>
        <param name="state">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を実装するバッファー マネージャー、<see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />インターフェイス、Table サービス クライアントに対する操作で使用されるバッファー プールを指定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> 型のオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Table サービス クライアントを作成するために使用するアカウントの資格情報を取得します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As TableRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Table サービス クライアントを介して行われる要求の要求オプションを既定値に設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">前回の呼び出しから返された結果<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />です。</param>
        <summary>
            テーブル サービスのサービス プロパティを取得する非同期操作を終了します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を終了します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment EndListTablesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment EndListTablesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndListTablesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListTablesSegmented (asyncResult As IAsyncResult) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListTablesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.EndListTablesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.EndListTablesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</param>
        <summary>
            テーブルの結果セグメントを返す非同期操作を終了します。 
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudTableClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult">前回の呼び出しから返される結果<see cref="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を終了します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.GetServiceProperties (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのサービスのプロパティを取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
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
            テーブル サービスのサービス プロパティを取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.GetServiceStats (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
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
            セカンダリ Table サービス エンドポイントのサービスの統計情報を取得する非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.CloudTable GetTableReference (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.CloudTable GetTableReference(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetTableReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetTableReference (tableName As String) As CloudTable" />
      <MemberSignature Language="F#" Value="abstract member GetTableReference : string -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable&#xA;override this.GetTableReference : string -&gt; Microsoft.WindowsAzure.Storage.Table.CloudTable" Usage="cloudTableClient.GetTableReference tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">テーブルの名前を含む文字列。</param>
        <summary>
            指定されたテーブルへの参照を取得します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableServiceContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext GetTableServiceContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext GetTableServiceContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.GetTableServiceContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTableServiceContext () As TableServiceContext" />
      <MemberSignature Language="F#" Value="member this.GetTableServiceContext : unit -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="cloudTableClient.GetTableServiceContext " />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新たに作成<see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />テーブル サービスに対する操作を実行するオブジェクト。
            </summary>
        <returns>テーブル サービスに対する操作を実行するのに使用するサービス コンテキスト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; ListTables (string prefix = null, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Table.CloudTable&gt; ListTables(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTables(System.String,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTables : string * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;&#xA;override this.ListTables : string * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;" Usage="cloudTableClient.ListTables (prefix, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル、遅延、取得した指定したプレフィックスで始まるの列挙可能なコレクションを返します。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTable" />遅れて取得されるオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <summary>
            テーブルの結果セグメントを返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (prefix As String, currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, currentToken)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <summary>
            テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableResultSegment ListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブルの遅延、取得した指定したプレフィックスで始まる結果セグメントを返します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <summary>
            テーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (prefix As String, currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="requestOptions">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">テーブル名のプレフィックスを含む文字列。</param>
        <param name="maxResults">5000 の操作あたりの上限に達するまで、一度に返される結果の最大数を示す正の整数値。 この値が場合<c>null</c>結果の最大数が返されます、最大 5000 です。</param>
        <param name="currentToken">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />前の一覧作成操作によって返されます。</param>
        <param name="requestOptions">サーバーのタイムアウト、最大実行時間、および操作の再試行ポリシーです。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            指定したプレフィックスで始まるテーブルの結果セグメントを返す非同期操作を開始します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableResultSegment" />非同期操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudTableClient.SetServiceProperties (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのサービスのプロパティを設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync properties" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties"><see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> オブジェクト。</param>
        <param name="requestOptions">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</param>
        <param name="operationContext"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</param>
        <param name="cancellationToken">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</param>
        <summary>
            テーブル サービスのサービス プロパティを設定する非同期操作を開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />
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
            プライマリとセカンダリの両方の場所の Table サービスのエンドポイントを取得します。
            </summary>
        <value>型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Table.CloudTableClient.StorageUri" />プライマリとセカンダリの両方の場所のサービスの Uri をテーブルを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>