<Type Name="PartitionKey" FullName="Microsoft.Azure.Documents.PartitionKey">
  <TypeSignature Language="C#" Value="public sealed class PartitionKey" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionKey extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.PartitionKey" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionKey" />
  <TypeSignature Language="F#" Value="type PartitionKey = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="10de2-101">Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-101">Represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionKey (object keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyValue As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.PartitionKey : obj -&gt; Microsoft.Azure.Documents.PartitionKey" Usage="new Microsoft.Azure.Documents.PartitionKey keyValue" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="keyValue">
            <span data-ttu-id="10de2-102">コレクションが作成されるときに、パーティション キーとして指定されているドキュメント プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="10de2-102">The value of the document property that is specified as the partition key when a collection is created.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10de2-103">新しいインスタンスをインスタンス化、<see cref="T:Microsoft.Azure.Documents.PartitionKey" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="10de2-103">Instantiate a new instance of the <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> object.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="10de2-104">このクラスは、Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-104">This class represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="partitionKey.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="10de2-105">比較するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="10de2-105">The object to compare with.</span></span></param>
        <summary>
            <span data-ttu-id="10de2-106">2 つのインスタンス間でオブジェクト比較を行うのための以下演算子をオーバーライド<see cref="T:Microsoft.Azure.Documents.PartitionKey" />です。</span><span class="sxs-lookup"><span data-stu-id="10de2-106">Overrides the Equal operator for object comparisons between two instances of <see cref="T:Microsoft.Azure.Documents.PartitionKey" />.</span></span>
            </summary>
        <returns><span data-ttu-id="10de2-107">2 つのオブジェクト インスタンスが等しいと見なされる場合は true。</span><span class="sxs-lookup"><span data-stu-id="10de2-107">True if two object instance are considered equal.</span></span></returns>
        <remarks>
            <span data-ttu-id="10de2-108">このクラスは、Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-108">This class represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FromJsonString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Documents.PartitionKey FromJsonString (string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Documents.PartitionKey FromJsonString(string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.FromJsonString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FromJsonString (keyValue As String) As PartitionKey" />
      <MemberSignature Language="F#" Value="static member FromJsonString : string -&gt; Microsoft.Azure.Documents.PartitionKey" Usage="Microsoft.Azure.Documents.PartitionKey.FromJsonString keyValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyValue">
            <span data-ttu-id="10de2-109">シリアル化された JSON 形式で、コレクションの作成時にパーティション分割キーとして指定されているドキュメント プロパティの値。</span><span class="sxs-lookup"><span data-stu-id="10de2-109">The value of the document property that is specified as the partition key when a collection is created, in serialized JSON form.</span></span>
            </param>
        <summary>
            <span data-ttu-id="10de2-110">新しいインスタンスをインスタンス化、<see cref="T:Microsoft.Azure.Documents.PartitionKey" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="10de2-110">Instantiate a new instance of the <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="10de2-111">このクラスは、Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-111">This class represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="partitionKey.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10de2-112">ハッシュ関数を使用して、オブジェクトのハッシュ コードを返します。</span><span class="sxs-lookup"><span data-stu-id="10de2-112">Hash function to return the hash code for the object.</span></span>
            </summary>
        <returns><span data-ttu-id="10de2-113">ハッシュ コードをこの<see cref="T:Microsoft.Azure.Documents.PartitionKey" />インスタンス</span><span class="sxs-lookup"><span data-stu-id="10de2-113">The hash code for this <see cref="T:Microsoft.Azure.Documents.PartitionKey" /> instance</span></span></returns>
        <remarks>
            <span data-ttu-id="10de2-114">このクラスは、Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-114">This class represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.PartitionKey.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionKey.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="10de2-115">スペースで区切って、重要な各コンポーネントの値を出力する基本の ToString メソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="10de2-115">Override the base ToString method to output the value of each key component, separated by a space.</span></span>
            </summary>
        <returns><span data-ttu-id="10de2-116">すべての主要なコンポーネントの値の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="10de2-116">The string representation of all the key component values.</span></span></returns>
        <remarks>
            <span data-ttu-id="10de2-117">このクラスは、Azure Cosmos DB サービスのコレクションの対象のパーティションを識別するパーティション キー値を表します。</span><span class="sxs-lookup"><span data-stu-id="10de2-117">This class represents a partition key value that identifies the target partition of a collection in the Azure Cosmos DB service.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>