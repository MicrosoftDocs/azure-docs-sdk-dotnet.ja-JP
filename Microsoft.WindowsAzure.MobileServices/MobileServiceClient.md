<Type Name="MobileServiceClient" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceClient">
  <TypeSignature Language="C#" Value="public class MobileServiceClient : IDisposable, Microsoft.WindowsAzure.MobileServices.IMobileServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceClient extends System.Object implements class Microsoft.WindowsAzure.MobileServices.IMobileServiceClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceClient&#xA;Implements IDisposable, IMobileServiceClient" />
  <TypeSignature Language="F#" Value="type MobileServiceClient = class&#xA;    interface IMobileServiceClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IMobileServiceClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Microsoft Azure モバイル サービスへの基本的なアクセスを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileServiceClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
             これは、単体テスト専用
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceClient (string mobileAppUri, params System.Net.Http.HttpMessageHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mobileAppUri, class System.Net.Http.HttpMessageHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor(System.String,System.Net.Http.HttpMessageHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mobileAppUri As String, ParamArray handlers As HttpMessageHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient : string * System.Net.Http.HttpMessageHandler[] -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient (mobileAppUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mobileAppUri" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.HttpMessageHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="mobileAppUri">
            Microsoft Azure のモバイル アプリの絶対 URI です。
            </param>
        <param name="handlers">
            チェーン<see cref="T:System.Net.Http.HttpMessageHandler" />インスタンス。
            最後に表示されるすべて<see cref="T:System.Net.Http.DelegatingHandler" />s。
            </param>
        <summary>
            MobileServiceClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceClient (Uri mobileAppUri, params System.Net.Http.HttpMessageHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri mobileAppUri, class System.Net.Http.HttpMessageHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor(System.Uri,System.Net.Http.HttpMessageHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mobileAppUri As Uri, ParamArray handlers As HttpMessageHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient : Uri * System.Net.Http.HttpMessageHandler[] -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient (mobileAppUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mobileAppUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.HttpMessageHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="mobileAppUri">
            Microsoft Azure のモバイル アプリの絶対 URI です。
            </param>
        <param name="handlers">
            チェーン<see cref="T:System.Net.Http.HttpMessageHandler" />インスタンス。
            最後に表示されるすべて<see cref="T:System.Net.Http.DelegatingHandler" />s。
            </param>
        <summary>
            MobileServiceClient クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlternateLoginHost">
      <MemberSignature Language="C#" Value="public Uri AlternateLoginHost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri AlternateLoginHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.AlternateLoginHost" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateLoginHost As Uri" />
      <MemberSignature Language="F#" Value="member this.AlternateLoginHost : Uri with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.AlternateLoginHost" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.AlternateLoginHost</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ログインの代替 URI
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUser">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.CurrentUser" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentUser As MobileServiceUser" />
      <MemberSignature Language="F#" Value="member this.CurrentUser : Microsoft.WindowsAzure.MobileServices.MobileServiceUser with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.CurrentUser" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.CurrentUser</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceUser</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在では、MobileServiceClient.Login() 呼び出しは成功後に指定されたユーザーを認証します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDatabasePath">
      <MemberSignature Language="C#" Value="public static string DefaultDatabasePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultDatabasePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.DefaultDatabasePath" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultDatabasePath As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDatabasePath : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.DefaultDatabasePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            すべてのファイルの場所のオフライン同期を作成する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="mobileServiceClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            実装<see cref="T:System.IDisposable" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="mobileServiceClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
            示す Dispose() メソッドまたはファイナライザーから呼び出されている場合。
            </param>
        <summary>
            実装<see cref="T:System.IDisposable" />派生クラスで使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnsureFileExists">
      <MemberSignature Language="C#" Value="public static void EnsureFileExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnsureFileExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EnsureFileExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub EnsureFileExists (path As String)" />
      <MemberSignature Language="F#" Value="static member EnsureFileExists : string -&gt; unit" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EnsureFileExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">完全修飾パス名を確認するには</param>
        <summary>
            により、ファイルが存在するために必要な場合は作成
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EventManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventManager As IMobileServiceEventManager" />
      <MemberSignature Language="F#" Value="member this.EventManager : Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EventManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            イベント マネージャーを公開し、発行およびイベントを使用するモバイル サービスの種類で使用されるイベント ストリームを管理します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetSyncTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable (tableName As String) As IMobileServiceSyncTable" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&#xA;override this.GetSyncTable : string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" Usage="mobileServiceClient.GetSyncTable tableName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">テーブルの名前。</param>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />インスタンス、そのテーブルの型指定されていないデータの操作を提供します。
            </summary>
        <returns>テーブルです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; GetSyncTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; GetSyncTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetSyncTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable(Of T) () As IMobileServiceSyncTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt;&#xA;override this.GetSyncTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt;" Usage="mobileServiceClient.GetSyncTable " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable``1</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            テーブル内のインスタンスの型。
            </typeparam>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1" />インスタンスで、ローカル テーブルの操作を厳密に型指定されたデータを提供します。
            </summary>
        <returns>
            テーブルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable (tableName As String) As IMobileServiceTable" />
      <MemberSignature Language="F#" Value="abstract member GetTable : string -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&#xA;override this.GetTable : string -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" Usage="mobileServiceClient.GetTable tableName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">
            テーブルの名前。
            </param>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />インスタンス、そのテーブルの型指定されていないデータの操作を提供します。
            </summary>
        <returns>
            テーブルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt; GetTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!!T&gt; GetTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable(Of T) () As IMobileServiceTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;&#xA;override this.GetTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;" Usage="mobileServiceClient.GetTable " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable``1</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            テーブル内のインスタンスの型。
            </typeparam>
        <summary>
            返します、<see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" />インスタンス、そのテーブルに対して操作を厳密に型指定されたデータを提供します。
            </summary>
        <returns>
            テーブルです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallationId">
      <MemberSignature Language="C#" Value="public string InstallationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstallationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InstallationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstallationId As String" />
      <MemberSignature Language="F#" Value="member this.InstallationId : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InstallationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この製品利用統計情報データを提供するアプリケーションのインストールを識別する id。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="body">HTTP 本文として送信する値。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            HTTP コンテンツの送信をサポートする HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            追加のデータは、クエリ文字列に送信されます。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="body">HTTP 本文として送信する値。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpContent content, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; requestHeaders, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpContent content, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; requestHeaders, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeApiAsync (apiName As String, content As HttpContent, method As HttpMethod, requestHeaders As IDictionary(Of String, String), parameters As IDictionary(Of String, String)) As Task(Of HttpResponseMessage)" />
      <MemberSignature Language="F#" Value="member this.InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, content, method, requestHeaders, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="content" Type="System.Net.Http.HttpContent" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="requestHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム AP の名前。</param>
        <param name="content">HTTP コンテンツ。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="requestHeaders">
            HttpRequest に含めるユーザー定義のヘッダーのディクショナリ。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <summary>
            指定された http メソッドを使用して、Windows Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。
            </summary>
        <returns>カスタム api の呼び出しからの HTTP 応答。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpContent content, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; requestHeaders, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpContent content, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; requestHeaders, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, content, method, requestHeaders, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="content" Type="System.Net.Http.HttpContent" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="requestHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName">カスタム AP の名前。</param>
        <param name="content">HTTP コンテンツ。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="requestHeaders">
            HttpRequest に含めるユーザー定義のヘッダーのディクショナリ。
            </param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            指定された http メソッドを使用して、Windows Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。
            </summary>
        <returns>カスタム api の呼び出しからの HTTP 応答。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;&#xA;override this.InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Microsoft Azure モバイル サービスから返されるインスタンスの型。</typeparam>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``1(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</typeparam>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            クエリ文字列を使用して、追加のデータを渡すことができます。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;&#xA;override this.InvokeApiAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</typeparam>
        <typeparam name="U">Microsoft Azure モバイル サービスから返されるインスタンスの型。</typeparam>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="body">HTTP 本文として送信する値。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            HTTP コンテンツを送信するためのサポートが HTTP POST を使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;&#xA;override this.InvokeApiAsync : string * 'T * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__66`2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">Microsoft Azure モバイル サービスに送信されるインスタンスの型。</typeparam>
        <typeparam name="U">Microsoft Azure モバイル サービスから返されるインスタンスの型。</typeparam>
        <param name="apiName">カスタム API の名前です。</param>
        <param name="body">HTTP 本文として送信する値。</param>
        <param name="method">HTTP メソッド。</param>
        <param name="parameters">
            ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。
            </param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            指定された HTTP メソッドを使用して、Microsoft Azure モバイル サービスのユーザー定義のカスタム API を呼び出します。
            追加のデータは、HTTP コンテンツまたはクエリ文字列が送信できます。
            </summary>
        <returns>カスタム api の呼び出しからの応答コンテンツ。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As MobileServiceAuthenticationProvider, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.LoginAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider,Newtonsoft.Json.Linq.JObject)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            使用する認証プロバイダーです。
            </param>
        <param name="token">
            ログインに使用する既存の OAuth トークンとプロバイダー固有のオブジェクト。
            </param>
        <summary>
            プロバイダーとオプションのトークン オブジェクトで、Windows Azure モバイル サービスにユーザーを記録します。
            </summary>
        <returns>
            ユーザーが認証を終了するとタスクが完了します。
            </returns>
        <remarks>
            トークンのオブジェクトは、特定のプロバイダーに応じて書式設定する必要があります。 これらは、プロバイダーに基づく形式のいくつかの例: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (string provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(string provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginAsync(System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As String, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : string * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.LoginAsync : string * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(System.String,Newtonsoft.Json.Linq.JObject)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            使用する認証プロバイダーです。
            </param>
        <param name="token">
            ログインに使用する既存の OAuth トークンとプロバイダー固有のオブジェクト。
            </param>
        <summary>
            プロバイダーとオプションのトークン オブジェクトで、Microsoft Azure モバイル サービスにユーザーを記録します。
            </summary>
        <returns>
            ユーザーが認証を終了するとタスクが完了します。
            </returns>
        <remarks>
            トークンのオブジェクトは、特定のプロバイダーに応じて書式設定する必要があります。 これらは、プロバイダーに基づく形式のいくつかの例: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginUriPrefix">
      <MemberSignature Language="C#" Value="public string LoginUriPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginUriPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginUriPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LoginUriPrefix As String" />
      <MemberSignature Language="F#" Value="member this.LoginUriPrefix : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginUriPrefix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginUriPrefix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ログインのエンドポイントのプレフィックス。 既定値を/.auth/login に設定されていない場合
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogoutAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LogoutAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LogoutAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LogoutAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LogoutAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member LogoutAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.LogoutAsync : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceClient.LogoutAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LogoutAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ユーザーをログアウトします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileAppUri">
      <MemberSignature Language="C#" Value="public Uri MobileAppUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri MobileAppUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.MobileAppUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileAppUri As Uri" />
      <MemberSignature Language="F#" Value="member this.MobileAppUri : Uri" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.MobileAppUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Microsoft Azure のモバイル アプリの絶対 URI です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.RefreshUserAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshUserAsync () As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member RefreshUserAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.RefreshUserAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.RefreshUserAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.RefreshUserAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;RefreshUserAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ログインしたユーザーの id プロバイダーにアクセス トークンを更新します。
            </summary>
        <returns>
            ユーザーがアクセス トークンを更新し終えたときに完了するタスク
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SerializerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property SerializerSettings As MobileServiceJsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializerSettings : Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SerializerSettings" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SerializerSettings</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定をシリアル化に使用します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SyncContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncContext As IMobileServiceSyncContext" />
      <MemberSignature Language="F#" Value="member this.SyncContext : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SyncContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インスタンス<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>