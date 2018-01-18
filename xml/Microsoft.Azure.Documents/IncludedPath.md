<Type Name="IncludedPath" FullName="Microsoft.Azure.Documents.IncludedPath">
  <TypeSignature Language="C#" Value="public sealed class IncludedPath : Microsoft.Azure.Documents.JsonSerializable, ICloneable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IncludedPath extends Microsoft.Azure.Documents.JsonSerializable implements class System.ICloneable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.IncludedPath" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IncludedPath&#xA;Inherits JsonSerializable&#xA;Implements ICloneable" />
  <TypeSignature Language="F#" Value="type IncludedPath = class&#xA;    inherit JsonSerializable&#xA;    interface ICloneable" />
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
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ICloneable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary> 
            <span data-ttu-id="80a35-101">Cosmos DB の Azure サービスに含まれる JSON ドキュメント内のパスを指定します。</span><span class="sxs-lookup"><span data-stu-id="80a35-101">Specifies a path within a JSON document to be included in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IncludedPath ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IncludedPath.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80a35-102">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="80a35-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.IncludedPath" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.IncludedPath.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="includedPath.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ICloneable.Clone</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="80a35-103">Azure Cosmos DB サービスのインクルード パスのコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="80a35-103">Creates a copy of the included path in the Azure Cosmos DB service.</span></span> 
            </summary>
        <returns><span data-ttu-id="80a35-104">インクルード パスの複製。</span><span class="sxs-lookup"><span data-stu-id="80a35-104">A clone of the included path.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexes">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt; Indexes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.Index&gt; Indexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IncludedPath.Indexes" />
      <MemberSignature Language="VB.NET" Value="Public Property Indexes As Collection(Of Index)" />
      <MemberSignature Language="F#" Value="member this.Indexes : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt; with get, set" Usage="Microsoft.Azure.Documents.IncludedPath.Indexes" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.Index&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80a35-105">取得または設定のコレクション<see cref="T:Microsoft.Azure.Documents.Index" />Cosmos DB の Azure サービスでこのインクルード パスに適用するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="80a35-105">Gets or sets the collection of <see cref="T:Microsoft.Azure.Documents.Index" /> objects to be applied for this included path in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80a35-106">コレクション、<see cref="T:Microsoft.Azure.Documents.Index" />このインクルード パスに適用するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="80a35-106">The collection of the <see cref="T:Microsoft.Azure.Documents.Index" /> objects to be applied for this included path.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.IncludedPath.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Documents.IncludedPath.Path" />
      <MemberType>Property</MemberType>
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
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="80a35-107">取得または Azure Cosmos DB サービスでインデックスを作成するパスを設定します。</span><span class="sxs-lookup"><span data-stu-id="80a35-107">Gets or sets the path to be indexed in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="80a35-108">インデックスを作成するパス。</span><span class="sxs-lookup"><span data-stu-id="80a35-108">The path to be indexed.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="80a35-109">パスを指定する方法について http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy を参照してください。</span><span class="sxs-lookup"><span data-stu-id="80a35-109">Refer to http://azure.microsoft.com/documentation/articles/documentdb-indexing-policies/#ConfigPolicy for how to specify paths.</span></span>
            <span data-ttu-id="80a35-110">有効な例をいくつか:"prop"//?、"prop"//* *、/"prop"/"subprop"/?、"prop"///しますか?</span><span class="sxs-lookup"><span data-stu-id="80a35-110">Some valid examples: /"prop"/?, /"prop"/**, /"prop"/"subprop"/?, /"prop"/[]/?</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>