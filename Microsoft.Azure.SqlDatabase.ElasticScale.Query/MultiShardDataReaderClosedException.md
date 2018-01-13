<Type Name="MultiShardDataReaderClosedException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException">
  <TypeSignature Language="C#" Value="public class MultiShardDataReaderClosedException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardDataReaderClosedException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardDataReaderClosedException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MultiShardDataReaderClosedException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            独自の例外をスローするときに、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />が閉じられる、ユーザーが閉じたリーダーに対して操作を実行しようとします。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardDataReaderClosedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MultiShardDataReaderClosedException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardDataReaderClosedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラーを説明するメッセージ。</param>
        <summary>
            指定したエラー メッセージで MultiShardDataReaderClosedException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardDataReaderClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
            スローされた例外に関するシリアル化されたオブジェクト データを保持する SerializationInfo です。
            </param>
        <param name="context">
            ソースまたは転送先に関するコンテキスト情報を含む StreamingContext です。
            </param>
        <summary>
            シリアル化されたデータを持つ MultiShardDataReaderClosedException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardDataReaderClosedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReaderClosedException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">例外の原因を説明するエラー メッセージ。</param>
        <param name="innerException">
            内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。
            </param>
        <summary>
            指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つ MultiShardReaderClosedException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>