<Type Name="UniqueKeyPolicy" FullName="Microsoft.Azure.Documents.UniqueKeyPolicy">
  <TypeSignature Language="C#" Value="public sealed class UniqueKeyPolicy : Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UniqueKeyPolicy extends Microsoft.Azure.Documents.JsonSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.UniqueKeyPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UniqueKeyPolicy&#xA;Inherits JsonSerializable" />
  <TypeSignature Language="F#" Value="type UniqueKeyPolicy = class&#xA;    inherit JsonSerializable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.JsonSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f5d3f-101">Azure Cosmos DB サービスのコレクション内のドキュメントの一意性制約を指定するポリシーの所有者。</span><span class="sxs-lookup"><span data-stu-id="f5d3f-101">A holder for policy specifying uniqueness constraints on documents in the collection in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UniqueKeyPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.UniqueKeyPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f5d3f-102">新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.UniqueKeyPolicy" /> Azure Cosmos DB サービスのクラスです。</span><span class="sxs-lookup"><span data-stu-id="f5d3f-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Documents.UniqueKeyPolicy" /> class for the Azure Cosmos DB service.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueKeys">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt; UniqueKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Documents.UniqueKey&gt; UniqueKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.UniqueKeyPolicy.UniqueKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property UniqueKeys As Collection(Of UniqueKey)" />
      <MemberSignature Language="F#" Value="member this.UniqueKeys : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt; with get, set" Usage="Microsoft.Azure.Documents.UniqueKeyPolicy.UniqueKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uniqueKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Documents.UniqueKey&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f5d3f-103">取得または設定のコレクション<see cref="T:Microsoft.Azure.Documents.UniqueKey" />Azure Cosmos DB サービスのコレクション内のドキュメントの一意性を保証します。</span><span class="sxs-lookup"><span data-stu-id="f5d3f-103">Gets or sets collection of <see cref="T:Microsoft.Azure.Documents.UniqueKey" /> that guarantee uniqueness of documents in collection in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>