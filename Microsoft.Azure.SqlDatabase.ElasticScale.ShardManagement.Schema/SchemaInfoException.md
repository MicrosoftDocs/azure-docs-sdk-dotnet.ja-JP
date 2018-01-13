<Type Name="SchemaInfoException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException">
  <TypeSignature Language="C#" Value="public sealed class SchemaInfoException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit SchemaInfoException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SchemaInfoException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type SchemaInfoException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            スキーマ情報のコレクションに関連する操作中にエラーが発生した場合にスローされる例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラー メッセージ。</param>
        <summary>
            指定したエラー メッセージでの新しいインスタンスを初期化します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">エラーについて説明するメッセージ。</param>
        <param name="inner">現在の例外の原因となった例外。</param>
        <summary>
            指定したエラー メッセージと、この例外の原因となった内部例外への参照の新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException (string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (format As String, ParamArray args As Object())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException : string * obj[] -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException (format, args)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="format">エラーを説明する形式のメッセージ。</param>
        <param name="args">書式指定文字列の引数。</param>
        <summary>
            指定した書式設定されたエラー メッセージでの新しいインスタンスを初期化します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode code, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode code, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode,System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As SchemaInfoErrorCode, message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode * string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException (code, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="code">エラー コード。</param>
        <param name="message">エラーを説明するメッセージ</param>
        <param name="inner">現在の例外の原因となった例外</param>
        <summary>
            指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つ新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfoException (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode code, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode code, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.#ctor(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (code As SchemaInfoErrorCode, format As String, ParamArray args As Object())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode * string * obj[] -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException (code, format, args)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="code">エラー コード。</param>
        <param name="format">エラーを説明するメッセージの書式設定</param>
        <param name="args">書式指定文字列の引数</param>
        <summary>
            指定した書式設定されたエラー メッセージでの新しいインスタンスを初期化します。 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As SchemaInfoErrorCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エラー コード。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="schemaInfoException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">データを設定する SerializationInfo です。</param>
        <param name="context">宛先 (StreamingContext を参照してください) このシリアル化します。</param>
        <summary>
            ターゲット オブジェクトをシリアル化に必要なデータに、SerializationInfo を設定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>