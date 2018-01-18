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
            <span data-ttu-id="c7a6c-101">スキーマ情報のコレクションに関連する操作中にエラーが発生した場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-101">The exception that is thrown when an error occurs during operations related to schema info collection.</span></span>
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
            <span data-ttu-id="c7a6c-102">新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-102">Initializes a new instance.</span></span>
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
        <param name="message"><span data-ttu-id="c7a6c-103">エラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-103">Error message.</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-104">指定したエラー メッセージでの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-104">Initializes a new instance with a specified error message.</span></span> 
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
        <param name="message"><span data-ttu-id="c7a6c-105">エラーについて説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-105">A message that describes the error.</span></span></param>
        <param name="inner"><span data-ttu-id="c7a6c-106">現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-106">The exception that is the cause of the current exception.</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-107">指定したエラー メッセージと、この例外の原因となった内部例外への参照の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-107">Initializes a new instance with a specified error message and a reference to the inner exception that caused this exception.</span></span>
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
        <param name="format"><span data-ttu-id="c7a6c-108">エラーを説明する形式のメッセージ。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-108">The format message that describes the error.</span></span></param>
        <param name="args"><span data-ttu-id="c7a6c-109">書式指定文字列の引数。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-109">The arguments to the format string.</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-110">指定した書式設定されたエラー メッセージでの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-110">Initializes a new instance with a specified formatted error message.</span></span> 
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
        <param name="code"><span data-ttu-id="c7a6c-111">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-111">Error code.</span></span></param>
        <param name="message"><span data-ttu-id="c7a6c-112">エラーを説明するメッセージ</span><span class="sxs-lookup"><span data-stu-id="c7a6c-112">A message that describes the error</span></span></param>
        <param name="inner"><span data-ttu-id="c7a6c-113">現在の例外の原因となった例外</span><span class="sxs-lookup"><span data-stu-id="c7a6c-113">The exception that is the cause of the current exception</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-114">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つ新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-114">Initializes a new instance with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
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
        <param name="code"><span data-ttu-id="c7a6c-115">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-115">Error code.</span></span></param>
        <param name="format"><span data-ttu-id="c7a6c-116">エラーを説明するメッセージの書式設定</span><span class="sxs-lookup"><span data-stu-id="c7a6c-116">The format message that describes the error</span></span></param>
        <param name="args"><span data-ttu-id="c7a6c-117">書式指定文字列の引数</span><span class="sxs-lookup"><span data-stu-id="c7a6c-117">The arguments to the format string</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-118">指定した書式設定されたエラー メッセージでの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-118">Initializes a new instance with a specified formatted error message.</span></span> 
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
            <span data-ttu-id="c7a6c-119">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-119">Error code.</span></span>
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
        <param name="info"><span data-ttu-id="c7a6c-120">データを設定する SerializationInfo です。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-120">The SerializationInfo to populate with data.</span></span></param>
        <param name="context"><span data-ttu-id="c7a6c-121">宛先 (StreamingContext を参照してください) このシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-121">The destination (see StreamingContext) for this serialization.</span></span></param>
        <summary>
            <span data-ttu-id="c7a6c-122">ターゲット オブジェクトをシリアル化に必要なデータに、SerializationInfo を設定します。</span><span class="sxs-lookup"><span data-stu-id="c7a6c-122">Populates a SerializationInfo with the data needed to serialize the target object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>