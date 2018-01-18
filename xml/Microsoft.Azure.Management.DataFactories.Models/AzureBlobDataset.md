<Type Name="AzureBlobDataset" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset">
  <TypeSignature Language="C#" Value="public class AzureBlobDataset : Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBlobDataset extends Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBlobDataset&#xA;Inherits DatasetTypeProperties" />
  <TypeSignature Language="F#" Value="type AzureBlobDataset = class&#xA;    inherit DatasetTypeProperties" />
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
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("AzureBlob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b5778-101">Azure blob ストレージです。</span><span class="sxs-lookup"><span data-stu-id="b5778-101">The Azure blob storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBlobDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Compression">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.Compression Compression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.Compression Compression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.Compression" />
      <MemberSignature Language="VB.NET" Value="Public Property Compression As Compression" />
      <MemberSignature Language="F#" Value="member this.Compression : Microsoft.Azure.Management.DataFactories.Models.Compression with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.Compression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.Compression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-102">データの圧縮方法は、blob ストレージに使用します。</span><span class="sxs-lookup"><span data-stu-id="b5778-102">The data compression method used for the blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileName">
      <MemberSignature Language="C#" Value="public string FileName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.FileName" />
      <MemberSignature Language="VB.NET" Value="Public Property FileName As String" />
      <MemberSignature Language="F#" Value="member this.FileName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.FileName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-103">Azure の blob の名前。</span><span class="sxs-lookup"><span data-stu-id="b5778-103">The name of the Azure blob.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FolderPath">
      <MemberSignature Language="C#" Value="public string FolderPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FolderPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.FolderPath" />
      <MemberSignature Language="VB.NET" Value="Public Property FolderPath As String" />
      <MemberSignature Language="F#" Value="member this.FolderPath : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.FolderPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-104">Azure blob ストレージのパス。</span><span class="sxs-lookup"><span data-stu-id="b5778-104">The path of the Azure blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Models.StorageFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As StorageFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.DataFactories.Models.StorageFormat with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.StorageFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-105">Azure blob ストレージの形式です。</span><span class="sxs-lookup"><span data-stu-id="b5778-105">The format of the Azure blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionedBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.PartitionedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionedBy As IList(Of Partition)" />
      <MemberSignature Language="F#" Value="member this.PartitionedBy : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.PartitionedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-106">パスで使用されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="b5778-106">The partitions to be used by the path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableRootLocation">
      <MemberSignature Language="C#" Value="public string TableRootLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableRootLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.TableRootLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TableRootLocation As String" />
      <MemberSignature Language="F#" Value="member this.TableRootLocation : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureBlobDataset.TableRootLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b5778-107">Blob パスのルートです。</span><span class="sxs-lookup"><span data-stu-id="b5778-107">The root of blob path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>