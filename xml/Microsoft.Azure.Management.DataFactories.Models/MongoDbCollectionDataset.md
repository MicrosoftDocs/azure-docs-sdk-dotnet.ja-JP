<Type Name="MongoDbCollectionDataset" FullName="Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset">
  <TypeSignature Language="C#" Value="public class MongoDbCollectionDataset : Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MongoDbCollectionDataset extends Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class MongoDbCollectionDataset&#xA;Inherits DatasetTypeProperties" />
  <TypeSignature Language="F#" Value="type MongoDbCollectionDataset = class&#xA;    inherit DatasetTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("MongoDbCollection")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fcbb5-101">MongoDB データベース内のコレクションです。</span><span class="sxs-lookup"><span data-stu-id="fcbb5-101">A collection in a MongoDB database.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MongoDbCollectionDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcbb5-102"><see cref="T:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcbb5-102">Initialize a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MongoDbCollectionDataset (string collectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string collectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (collectionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset : string -&gt; Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" Usage="new Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset collectionName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="collectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="collectionName">To be added.</param>
        <summary>
            <span data-ttu-id="fcbb5-103">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" />必須の引数を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="fcbb5-103">Initialize a new instance of the <see cref="T:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset" /> class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionName">
      <MemberSignature Language="C#" Value="public string CollectionName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CollectionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset.CollectionName" />
      <MemberSignature Language="VB.NET" Value="Public Property CollectionName As String" />
      <MemberSignature Language="F#" Value="member this.CollectionName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.MongoDbCollectionDataset.CollectionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcbb5-104">必須。</span><span class="sxs-lookup"><span data-stu-id="fcbb5-104">Required.</span></span> <span data-ttu-id="fcbb5-105">MongoDB データベース内のコレクションの名前です。</span><span class="sxs-lookup"><span data-stu-id="fcbb5-105">Name of the collection in the MongoDB database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>