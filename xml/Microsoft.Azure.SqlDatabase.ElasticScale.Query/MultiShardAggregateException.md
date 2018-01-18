<Type Name="MultiShardAggregateException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException">
  <TypeSignature Language="C#" Value="public class MultiShardAggregateException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardAggregateException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardAggregateException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type MultiShardAggregateException = class&#xA;    inherit Exception" />
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
            <span data-ttu-id="edeec-101">1 つまたは複数を表す<see cref="T:System.Exception" />シャード セット間でクエリを実行するときに発生したエラー。</span><span class="sxs-lookup"><span data-stu-id="edeec-101">Represents one or more <see cref="T:System.Exception" /> errors that occured when executing a query across a shard set.</span></span> <span data-ttu-id="edeec-102">InnerExceptions フィールドがこれらの例外を収集し、さらに検査または処理のため InnerExceptions を反復処理できる 1 つ。</span><span class="sxs-lookup"><span data-stu-id="edeec-102">The InnerExceptions field collects these exceptions and one can iterate through the InnerExceptions for further inspection or processing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="edeec-103"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException (System.Collections.Generic.IEnumerable&lt;Exception&gt; innerExceptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Exception&gt; innerExceptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.Collections.Generic.IEnumerable{System.Exception})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerExceptions As IEnumerable(Of Exception))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : seq&lt;Exception&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException innerExceptions" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerExceptions" Type="System.Collections.Generic.IEnumerable&lt;System.Exception&gt;" />
      </Parameters>
      <Docs>
        <param name="innerExceptions"><span data-ttu-id="edeec-104">一連の<see cref="T:System.Exception" />現在の例外の原因となった</span><span class="sxs-lookup"><span data-stu-id="edeec-104">A list of <see cref="T:System.Exception" /> that caused the current exception</span></span></param>
        <summary>
            <span data-ttu-id="edeec-105"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException (Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException innerException" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="innerException"><span data-ttu-id="edeec-106"><see cref="T:System.Exception" />現在の例外の原因となった</span><span class="sxs-lookup"><span data-stu-id="edeec-106">The <see cref="T:System.Exception" /> that caused the current exception</span></span></param>
        <summary>
            <span data-ttu-id="edeec-107"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="edeec-108">例外の原因を説明するエラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="edeec-108">The error message that explains the reason for the exception</span></span></param>
        <summary>
            <span data-ttu-id="edeec-109"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> class</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardAggregateException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException (info, context)" />
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
        <param name="info"><span data-ttu-id="edeec-110">シリアル化されたオブジェクト データを保持するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="edeec-110">The object that holds the serialized object data.</span></span></param>
        <param name="context"><span data-ttu-id="edeec-111">転送元または転送先に関するコンテキスト情報。</span><span class="sxs-lookup"><span data-stu-id="edeec-111">The contextual information about the source or destination.</span></span></param>
        <summary>
            <span data-ttu-id="edeec-112">シリアル化されたデータを持つ MultiShardAggregateException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-112">Initializes a new instance of the MultiShardAggregateException class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException (string message, System.Collections.Generic.IEnumerable&lt;Exception&gt; innerExceptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Collections.Generic.IEnumerable`1&lt;class System.Exception&gt; innerExceptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.String,System.Collections.Generic.IEnumerable{System.Exception})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerExceptions As IEnumerable(Of Exception))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : string * seq&lt;Exception&gt; -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException (message, innerExceptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerExceptions" Type="System.Collections.Generic.IEnumerable&lt;System.Exception&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="edeec-113">例外の原因を説明するエラー メッセージ</span><span class="sxs-lookup"><span data-stu-id="edeec-113">The error message that explains the reason for the exception</span></span></param>
        <param name="innerExceptions"><span data-ttu-id="edeec-114">一連の<see cref="T:System.Exception" />現在の例外の原因となった</span><span class="sxs-lookup"><span data-stu-id="edeec-114">A list of <see cref="T:System.Exception" /> that caused the current exception</span></span></param>
        <summary>
            <span data-ttu-id="edeec-115"><see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" /> class</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="edeec-116"><paramref name="innerExceptions" />が null です</span><span class="sxs-lookup"><span data-stu-id="edeec-116">The <paramref name="innerExceptions" /> is null</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardAggregateException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException (message, innerException)" />
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
        <param name="message"></param>
        <param name="innerException"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="multiShardAggregateException.GetObjectData (info, context)" />
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
        <param name="info"><span data-ttu-id="edeec-117">データを設定する SerializationInfo です。</span><span class="sxs-lookup"><span data-stu-id="edeec-117">The SerializationInfo to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="edeec-118">宛先 (StreamingContext を参照してください) このシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="edeec-118">The destination (see StreamingContext) for this serialization.</span></span></param>
        <summary>
            <span data-ttu-id="edeec-119">ターゲット オブジェクトをシリアル化に必要なデータに、SerializationInfo を設定します。</span><span class="sxs-lookup"><span data-stu-id="edeec-119">Populates a SerializationInfo with the data needed to serialize the target object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InnerExceptions">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Exception&gt; InnerExceptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Exception&gt; InnerExceptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.InnerExceptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InnerExceptions As ReadOnlyCollection(Of Exception)" />
      <MemberSignature Language="F#" Value="member this.InnerExceptions : System.Collections.ObjectModel.ReadOnlyCollection&lt;Exception&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.InnerExceptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Exception&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="edeec-120">読み取り専用コレクションを取得、<see cref="T:System.Exception" />現在の例外の原因となったのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="edeec-120">Gets a read-only collection of the <see cref="T:System.Exception" /> instances that caused the current exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardAggregateException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="multiShardAggregateException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="edeec-121">その内部の例外を含むこの例外の文字列表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="edeec-121">Provides a string representation of this exception including its inner exceptions.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>