<Type Name="MobileServiceTableOperationError" FullName="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError">
  <TypeSignature Language="C#" Value="public class MobileServiceTableOperationError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceTableOperationError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceTableOperationError" />
  <TypeSignature Language="F#" Value="type MobileServiceTableOperationError = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            失敗したテーブル操作の詳細を示します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceTableOperationError (string id, long operationVersion, Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind operationKind, Nullable&lt;System.Net.HttpStatusCode&gt; status, string tableName, Newtonsoft.Json.Linq.JObject item, string rawResult, Newtonsoft.Json.Linq.JObject result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, int64 operationVersion, valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind operationKind, valuetype System.Nullable`1&lt;valuetype System.Net.HttpStatusCode&gt; status, string tableName, class Newtonsoft.Json.Linq.JObject item, string rawResult, class Newtonsoft.Json.Linq.JObject result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.#ctor(System.String,System.Int64,Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind,System.Nullable{System.Net.HttpStatusCode},System.String,Newtonsoft.Json.Linq.JObject,System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, operationVersion As Long, operationKind As MobileServiceTableOperationKind, status As Nullable(Of HttpStatusCode), tableName As String, item As JObject, rawResult As String, result As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError : string * int64 * Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind * Nullable&lt;System.Net.HttpStatusCode&gt; * string * Newtonsoft.Json.Linq.JObject * string * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError" Usage="new Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError (id, operationVersion, operationKind, status, tableName, item, rawResult, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="operationVersion" Type="System.Int64" />
        <Parameter Name="operationKind" Type="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind" />
        <Parameter Name="status" Type="System.Nullable&lt;System.Net.HttpStatusCode&gt;" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="item" Type="Newtonsoft.Json.Linq.JObject" />
        <Parameter Name="rawResult" Type="System.String" />
        <Parameter Name="result" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="id">操作 id と同じであるエラーの id。</param>
        <param name="operationVersion">操作のバージョン。</param>
        <param name="operationKind">テーブル操作の種類。</param>
        <param name="status">サーバーによって返される HTTP ステータス コード。</param>
        <param name="tableName">リモート テーブルの名前です。</param>
        <param name="item">操作に関連付けられている項目。</param>
        <param name="rawResult">テーブル操作の未加工の応答。</param>
        <param name="result">テーブル操作の応答です。</param>
        <summary>
            インスタンスを初期化します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAndDiscardItemAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelAndDiscardItemAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelAndDiscardItemAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.CancelAndDiscardItemAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelAndDiscardItemAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CancelAndDiscardItemAsync : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceTableOperationError.CancelAndDiscardItemAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError/&lt;CancelAndDiscardItemAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            テーブル操作をキャンセルし、項目のローカル インスタンスを破棄します。
            </summary>
        <returns>操作が取り消されたときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAndUpdateItemAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelAndUpdateItemAsync (Newtonsoft.Json.Linq.JObject item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelAndUpdateItemAsync(class Newtonsoft.Json.Linq.JObject item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.CancelAndUpdateItemAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelAndUpdateItemAsync (item As JObject) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelAndUpdateItemAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="mobileServiceTableOperationError.CancelAndUpdateItemAsync item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError/&lt;CancelAndUpdateItemAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="item">ローカル ストアで更新する項目。</param>
        <summary>
            テーブル操作をキャンセルし、指定したアイテムとアイテムのローカル インスタンスを更新します。
            </summary>
        <returns>操作が取り消されたときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Handled">
      <MemberSignature Language="C#" Value="public bool Handled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Handled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Handled" />
      <MemberSignature Language="VB.NET" Value="Public Property Handled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Handled : bool with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Handled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーが処理されるかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.Linq.JObject Item { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.Linq.JObject Item" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Item" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Item As JObject" />
      <MemberSignature Language="F#" Value="member this.Item : Newtonsoft.Json.Linq.JObject" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Linq.JObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作に関連付けられている項目。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationKind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind OperationKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind OperationKind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.OperationKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationKind As MobileServiceTableOperationKind" />
      <MemberSignature Language="F#" Value="member this.OperationKind : Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.OperationKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テーブル操作の種類。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RawResult">
      <MemberSignature Language="C#" Value="public string RawResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RawResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.RawResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RawResult As String" />
      <MemberSignature Language="F#" Value="member this.RawResult : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.RawResult" />
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
            テーブル操作の未加工の応答。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.Linq.JObject Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.Linq.JObject Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As JObject" />
      <MemberSignature Language="F#" Value="member this.Result : Newtonsoft.Json.Linq.JObject" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Linq.JObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            テーブル操作の応答です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Net.HttpStatusCode&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Net.HttpStatusCode&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of HttpStatusCode)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;System.Net.HttpStatusCode&gt;" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Net.HttpStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サーバーによって返される HTTP ステータス コード。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.TableName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string" Usage="Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.TableName" />
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
            リモート テーブルの名前です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateOperationAsync (Newtonsoft.Json.Linq.JObject item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateOperationAsync(class Newtonsoft.Json.Linq.JObject item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError.UpdateOperationAsync(Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateOperationAsync (item As JObject) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateOperationAsync : Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task" Usage="mobileServiceTableOperationError.UpdateOperationAsync item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationError/&lt;UpdateOperationAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="item">ローカル ストアで更新する項目。</param>
        <summary>
            テーブル操作を更新し、指定したアイテムでアイテムのローカル インスタンスを更新します。 エラーをクリアし、操作状態を保留中に設定します。
            </summary>
        <returns>操作が更新されるときに完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>