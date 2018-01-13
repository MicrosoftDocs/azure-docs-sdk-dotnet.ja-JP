<Type Name="TableStorageModel" FullName="Microsoft.WindowsAzure.Storage.Table.TableStorageModel">
  <TypeSignature Language="C#" Value="public class TableStorageModel : Microsoft.Data.Edm.Library.EdmModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableStorageModel extends Microsoft.Data.Edm.Library.EdmModel implements class Microsoft.Data.Edm.IEdmElement, class Microsoft.Data.Edm.IEdmModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableStorageModel" />
  <TypeSignature Language="VB.NET" Value="Public Class TableStorageModel&#xA;Inherits EdmModel" />
  <TypeSignature Language="F#" Value="type TableStorageModel = class&#xA;    inherit EdmModel&#xA;    interface IEdmModel&#xA;    interface IEdmElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Data.Edm.Library.EdmModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f370c-101">テーブルのトランザクションの OData で使用されるデータ モデルを表します。</span><span class="sxs-lookup"><span data-stu-id="f370c-101">Represents a data model that will be used by OData for table transactions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableStorageModel (string accountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableStorageModel.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableStorageModel : string -&gt; Microsoft.WindowsAzure.Storage.Table.TableStorageModel" Usage="new Microsoft.WindowsAzure.Storage.Table.TableStorageModel accountName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">To be added.</param>
        <summary>
            <span data-ttu-id="f370c-102"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableStorageModel" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f370c-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableStorageModel" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Data.Edm.IEdmModel.FindDeclaredType">
      <MemberSignature Language="C#" Value="Microsoft.Data.Edm.IEdmSchemaType IEdmModel.FindDeclaredType (string qualifiedName);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.Data.Edm.IEdmSchemaType Microsoft.Data.Edm.IEdmModel.FindDeclaredType(string qualifiedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableStorageModel.Microsoft#Data#Edm#IEdmModel#FindDeclaredType(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function FindDeclaredType (qualifiedName As String) As IEdmSchemaType Implements IEdmModel.FindDeclaredType" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Data.Edm.IEdmModel.FindDeclaredType(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Data.Edm.IEdmSchemaType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="qualifiedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="qualifiedName"><span data-ttu-id="f370c-103">検索する型の修飾名。</span><span class="sxs-lookup"><span data-stu-id="f370c-103">The qualified name of the type being found.</span></span></param>
        <summary>
            <span data-ttu-id="f370c-104">このモデルで指定された名前を持つ型を検索し、このような型が存在しない場合は、新しい型を作成します。</span><span class="sxs-lookup"><span data-stu-id="f370c-104">Searches for a type with the given name in this model and creates a new type if no such type exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f370c-105">要求された型またはそのような型が存在しない場合に作成した新しい型。</span><span class="sxs-lookup"><span data-stu-id="f370c-105">The requested type, or the new type created if no such type exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>