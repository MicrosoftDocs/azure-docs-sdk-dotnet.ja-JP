<Type Name="Dataset" FullName="Microsoft.Azure.Management.DataFactories.Core.Models.Dataset">
  <TypeSignature Language="C#" Value="public class Dataset" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Dataset extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.Models.Dataset" />
  <TypeSignature Language="VB.NET" Value="Public Class Dataset" />
  <TypeSignature Language="F#" Value="type Dataset = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fb7f1-101">データセットでは、その記憶域と同様に、データのスキーマを定義します。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-101">A dataset defines the schema of the data as well as its storage.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fb7f1-102">Dataset クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-102">Initializes a new instance of the Dataset class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Dataset (string name, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.#ctor(System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, properties As DatasetProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Core.Models.Dataset : string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.Dataset" Usage="new Microsoft.Azure.Management.DataFactories.Core.Models.Dataset (name, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="properties">To be added.</param>
        <summary>
            <span data-ttu-id="fb7f1-103">必須の引数で、データセット クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-103">Initializes a new instance of the Dataset class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.Name" />
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
            <span data-ttu-id="fb7f1-104">必須。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-104">Required.</span></span> <span data-ttu-id="fb7f1-105">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-105">Name of the dataset.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DatasetProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties with get, set" Usage="Microsoft.Azure.Management.DataFactories.Core.Models.Dataset.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fb7f1-106">必須。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-106">Required.</span></span> <span data-ttu-id="fb7f1-107">データセットのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="fb7f1-107">dataset properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>