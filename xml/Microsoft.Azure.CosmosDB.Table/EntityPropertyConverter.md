<Type Name="EntityPropertyConverter" FullName="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter">
  <TypeSignature Language="C#" Value="public static class EntityPropertyConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EntityPropertyConverter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class EntityPropertyConverter" />
  <TypeSignature Language="F#" Value="type EntityPropertyConverter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="870d8-101">EntityPropertyConverter クラスです。</span><span class="sxs-lookup"><span data-stu-id="870d8-101">EntityPropertyConverter class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="870d8-102">設定されるオブジェクトの種類</span><span class="sxs-lookup"><span data-stu-id="870d8-102">The type of the object to populate</span></span></typeparam>
        <param name="flattenedEntityProperties"><span data-ttu-id="870d8-103">フラット化されたエンティティ プロパティのディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="870d8-103">The flattened entity property dictionary.</span></span></param>
        <param name="operationContext"><span data-ttu-id="870d8-104"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-104">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="870d8-105">フラット化されたエンティティのプロパティのディクショナリを使用して T 型の完全なオブジェクト グラフを再構築し、再構築されたオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="870d8-105">Reconstructs the complete object graph of type T using the flattened entity property dictionary and returns reconstructed object.</span></span>
            <span data-ttu-id="870d8-106">プロパティ辞書には、基本的なプロパティのみ、入れ子になったプロパティのみまたは両方の種類の組み合わせが含まれて可能性があります。</span><span class="sxs-lookup"><span data-stu-id="870d8-106">The property dictionary may contain only basic properties, only nested properties or a mix of both types.</span></span>
            </summary>
        <returns><span data-ttu-id="870d8-107">完全なオブジェクト階層で再構築されたオブジェクトを含む結果を返します。</span><span class="sxs-lookup"><span data-stu-id="870d8-107">The result containing the reconstructed object with its full object hierarchy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T ConvertBack&lt;T&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; flattenedEntityProperties, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T ConvertBack&lt;T&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; flattenedEntityProperties, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; 'T" Usage="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.ConvertBack (flattenedEntityProperties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="flattenedEntityProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="870d8-108">設定されるオブジェクトの種類</span><span class="sxs-lookup"><span data-stu-id="870d8-108">The type of the object to populate</span></span></typeparam>
        <param name="flattenedEntityProperties"><span data-ttu-id="870d8-109">フラット化されたエンティティ プロパティのディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="870d8-109">The flattened entity property dictionary.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="870d8-110">A<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-110">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="870d8-111"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-111">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="870d8-112">フラット化されたエンティティのプロパティのディクショナリを使用して T 型の完全なオブジェクト グラフを再構築し、再構築されたオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="870d8-112">Reconstructs the complete object graph of type T using the flattened entity property dictionary and returns reconstructed object.</span></span>
            <span data-ttu-id="870d8-113">プロパティ辞書には、基本的なプロパティのみ、入れ子になったプロパティのみまたは両方の種類の組み合わせが含まれて可能性があります。</span><span class="sxs-lookup"><span data-stu-id="870d8-113">The property dictionary may contain only basic properties, only nested properties or a mix of both types.</span></span>
            </summary>
        <returns><span data-ttu-id="870d8-114">完全なオブジェクト階層で再構築されたオブジェクトを含む結果を返します。</span><span class="sxs-lookup"><span data-stu-id="870d8-114">The result containing the reconstructed object with its full object hierarchy.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultPropertyNameDelimiter">
      <MemberSignature Language="C#" Value="public const string DefaultPropertyNameDelimiter;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultPropertyNameDelimiter" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultPropertyNameDelimiter As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultPropertyNameDelimiter : string" Usage="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.DefaultPropertyNameDelimiter" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="870d8-115">プロパティの区切り記号。</span><span class="sxs-lookup"><span data-stu-id="870d8-115">The property delimiter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object root, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object root, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.Flatten (root, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root"><span data-ttu-id="870d8-116">フラット化して変換するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-116">The object to flatten and convert.</span></span></param>
        <param name="operationContext"><span data-ttu-id="870d8-117"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-117">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="870d8-118">オブジェクト グラフを通過する時間を平坦化する EntityProperties を入れ子になったすべて (およびいない入れ子になった) のプロパティに変換、プロパティ ディクショナリに格納します。</span><span class="sxs-lookup"><span data-stu-id="870d8-118">Traverses object graph, flattens and converts all nested (and not nested) properties to EntityProperties, stores them in the property dictionary.</span></span>
            <span data-ttu-id="870d8-119">キーは、'_' で区切られた各終了ノードのプロパティをルートから前の注文の深さの最初のトラバース時に閲覧のプロパティの名前を追加することによって構築されます。</span><span class="sxs-lookup"><span data-stu-id="870d8-119">The keys are constructed by appending the names of the properties visited during pre-order depth first traversal from root to each end node property delimited by '_'.</span></span>
            <span data-ttu-id="870d8-120">永続的な記憶域システムに格納されているまたは一般的な方法で web サービスの間で受け渡しする複雑なオブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="870d8-120">Allows complex objects to be stored in persistent storage systems or passed between web services in a generic way.</span></span>
            </summary>
        <returns><span data-ttu-id="870d8-121">結果を含む<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />フラット化されたルート オブジェクトのすべてのプロパティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-121">The result containing <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the flattened root object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.Dictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten (object root, Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.Dictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Flatten(object root, class Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.Flatten(System.Object,Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.Dictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverter.Flatten (root, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="root" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="root"><span data-ttu-id="870d8-122">フラット化して変換するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-122">The object to flatten and convert.</span></span></param>
        <param name="entityPropertyConverterOptions"><span data-ttu-id="870d8-123">A<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" />変換オプションは、エンティティ プロパティを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-123">A <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityPropertyConverterOptions" /> object that specifies options for the entity property conversion.</span></span></param>
        <param name="operationContext"><span data-ttu-id="870d8-124"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-124">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="870d8-125">オブジェクト グラフを通過する時間を平坦化する EntityProperties を入れ子になったすべて (およびいない入れ子になった) のプロパティに変換、プロパティ ディクショナリに格納します。</span><span class="sxs-lookup"><span data-stu-id="870d8-125">Traverses object graph, flattens and converts all nested (and not nested) properties to EntityProperties, stores them in the property dictionary.</span></span>
            <span data-ttu-id="870d8-126">キーは、'_' で区切られた各終了ノードのプロパティをルートから前の注文の深さの最初のトラバース時に閲覧のプロパティの名前を追加することによって構築されます。</span><span class="sxs-lookup"><span data-stu-id="870d8-126">The keys are constructed by appending the names of the properties visited during pre-order depth first traversal from root to each end node property delimited by '_'.</span></span>
            <span data-ttu-id="870d8-127">永続的な記憶域システムに格納されているまたは一般的な方法で web サービスの間で受け渡しする複雑なオブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="870d8-127">Allows complex objects to be stored in persistent storage systems or passed between web services in a generic way.</span></span>
            </summary>
        <returns><span data-ttu-id="870d8-128">結果を含む<see cref="T:System.Collections.Generic.IDictionary`2" />の<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />フラット化されたルート オブジェクトのすべてのプロパティ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="870d8-128">The result containing <see cref="T:System.Collections.Generic.IDictionary`2" /> of <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> objects for all properties of the flattened root object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>