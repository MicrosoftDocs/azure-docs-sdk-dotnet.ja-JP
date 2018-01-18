<Type Name="MultiShardSchemaMismatchException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException">
  <TypeSignature Language="C#" Value="public class MultiShardSchemaMismatchException : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardSchemaMismatchException extends Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardSchemaMismatchException&#xA;Inherits MultiShardException" />
  <TypeSignature Language="F#" Value="type MultiShardSchemaMismatchException = class&#xA;    inherit MultiShardException" />
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
            <span data-ttu-id="c0fb2-101">カスタム例外は、全体的なクエリに参加しているシャードの少なくとも 1 つのスキーマが、複数のシャード クエリ全体の予期されるスキーマに準拠していない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-101">Custom exception thrown when the schema on at least one of the shards participating in the overall query does not conform to the expected schema for the multi-shard query as a whole.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c0fb2-102">MultiShardSchemaMismatchException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-102">Initializes a new instance of the MultiShardSchemaMismatchException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="c0fb2-103">例外の原因を説明するメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-103">specifices the message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="c0fb2-104">指定されたエラー メッセージで MultiShardSchemaMismatchException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-104">Initializes a new instance of the MultiShardSchemaMismatchException class with the specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardSchemaMismatchException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (info, context)" />
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
            <span data-ttu-id="c0fb2-105"><see cref="T:System.Runtime.Serialization.SerializationInfo" />スローされた例外に関するシリアル化されたオブジェクト データを保持するを参照してください。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> see that holds the serialized object data about the exception being thrown.</span></span>
            </param>
        <param name="context">
            <span data-ttu-id="c0fb2-106">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0fb2-107">シリアル化されたデータを持つ MultiShardSchemaMismatchException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-107">Initializes a new instance of the MultiShardSchemaMismatchException class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (message, innerException)" />
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
        <param name="message"> <span data-ttu-id="c0fb2-108">例外の原因を説明するメッセージを指定します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-108">specifices the message that explains the reason for the exception.</span></span></param>
        <param name="innerException"> <span data-ttu-id="c0fb2-109">シャードで発生した例外を指定します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-109">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="c0fb2-110">指定されたエラー メッセージとは、この例外の原因となった内部例外への参照を使用して、MultiShardSchemaMismatchException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c0fb2-110">Initializes a new instance of the MultiShardSchemaMismatchException class with the specified error message and the reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>