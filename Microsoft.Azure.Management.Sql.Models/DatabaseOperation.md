<Type Name="DatabaseOperation" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseOperation">
  <TypeSignature Language="C#" Value="public class DatabaseOperation : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseOperation extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseOperation&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DatabaseOperation = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            データベースの操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Databaseoperation ですクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseOperation (string id = null, string name = null, string type = null, string databaseName = null, string operation = null, string operationFriendlyName = null, Nullable&lt;int&gt; percentComplete = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null, Nullable&lt;int&gt; errorCode = null, string errorDescription = null, Nullable&lt;int&gt; errorSeverity = null, Nullable&lt;bool&gt; isUserError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string databaseName, string operation, string operationFriendlyName, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorDescription, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, valuetype System.Nullable`1&lt;bool&gt; isUserError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional databaseName As String = null, Optional operation As String = null, Optional operationFriendlyName As String = null, Optional percentComplete As Nullable(Of Integer) = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorDescription As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional isUserError As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseOperation : string * string * string * string * string * string * Nullable&lt;int&gt; * string * Nullable&lt;DateTime&gt; * string * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseOperation" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseOperation (id, name, type, databaseName, operation, operationFriendlyName, percentComplete, serverName, startTime, state, errorCode, errorDescription, errorSeverity, isUserError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationFriendlyName" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorDescription" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isUserError" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソース名。</param>
        <param name="type">リソースの種類。</param>
        <param name="databaseName">データベースの名前で、操作が実行されます。</param>
        <param name="operation">操作の名前。</param>
        <param name="operationFriendlyName">操作のフレンドリ名。</param>
        <param name="percentComplete">操作完了の割合。</param>
        <param name="serverName">サーバーの名前。</param>
        <param name="startTime">操作の開始時刻です。</param>
        <param name="state">操作の状態。 使用可能な値が含まれます: '保留中'、'処理中'、'成功'、'失敗'、'CancelInProgress'、'キャンセル'</param>
        <param name="errorCode">操作のエラー コード。</param>
        <param name="errorDescription">操作エラーの説明。</param>
        <param name="errorSeverity">操作エラーの重大度。</param>
        <param name="isUserError">かどうか、エラーは、ユーザー エラーです。</param>
        <summary>
            Databaseoperation ですクラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作が実行されているデータベースの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作のエラー コードを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDescription">
      <MemberSignature Language="C#" Value="public string ErrorDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorDescription As String" />
      <MemberSignature Language="F#" Value="member this.ErrorDescription : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作エラーの説明を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorSeverity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorSeverity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作エラーの重大度を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUserError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUserError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUserError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.IsUserError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsUserError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUserError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.IsUserError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isUserError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラーがユーザー エラーかどうかを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationFriendlyName">
      <MemberSignature Language="C#" Value="public string OperationFriendlyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationFriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.OperationFriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationFriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.OperationFriendlyName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.OperationFriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationFriendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作のフレンドリ名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作完了の割合を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サーバーの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の開始時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            操作の状態を取得します。 使用可能な値が含まれます: '保留中'、'処理中'、'成功'、'失敗'、'CancelInProgress'、'キャンセル'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>