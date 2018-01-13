<Type Name="MultiShardPartialReadException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException">
  <TypeSignature Language="C#" Value="public class MultiShardPartialReadException : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardPartialReadException extends Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardPartialReadException&#xA;Inherits MultiShardException" />
  <TypeSignature Language="F#" Value="type MultiShardPartialReadException = class&#xA;    inherit MultiShardException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardDataReader" />基になるシャードのいずれかからデータを読み取る例外にヒットしたときに、この例外をスローします。 これは、すべての行が対象のシャードから正常に取得されたことを示します。 ユーザー、手順を実行、クエリを再実行するかどうか、または既に取得されている行を含む作業を続行するかどうかを判断するために必要です。
            </summary>
    <remarks>
            結果の一部のポリシーでは、この例外がスローされますのみです。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            MultiShardPartialReadException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> 例外の原因を説明するメッセージを指定します。</param>
        <summary>
            指定されたエラー メッセージで MultiShardPartialReadException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardPartialReadException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException (info, context)" />
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
            <see cref="T:System.Runtime.Serialization.SerializationInfo" />スローされた例外に関するシリアル化されたオブジェクト データを保持するを参照してください。
            </param>
        <param name="context">
            転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。
            </param>
        <summary>
            シリアル化されたデータを持つ MultiShardPartialReadException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardPartialReadException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardPartialReadException (message, innerException)" />
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
        <param name="message"> 例外の原因を説明するメッセージを指定します。</param>
        <param name="innerException"> シャードで発生した例外を指定します。</param>
        <summary>
            指定したエラー メッセージと、MultiShardPartialReadException の原因は、内部例外への参照を使用して、MultiShardPartialReadException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>