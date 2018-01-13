<Type Name="SynonymMapFormat" FullName="Microsoft.Azure.Search.Models.SynonymMapFormat">
  <TypeSignature Language="C#" Value="public sealed class SynonymMapFormat : Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.SynonymMapFormat&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SynonymMapFormat extends Microsoft.Azure.Search.Models.ExtensibleEnum`1&lt;class Microsoft.Azure.Search.Models.SynonymMapFormat&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymMapFormat" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SynonymMapFormat&#xA;Inherits ExtensibleEnum(Of SynonymMapFormat)" />
  <TypeSignature Language="F#" Value="type SynonymMapFormat = class&#xA;    inherit ExtensibleEnum&lt;SynonymMapFormat&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ExtensibleEnum&lt;Microsoft.Azure.Search.Models.SynonymMapFormat&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.SynonymMapFormat</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Azure.Search.Serialization.ExtensibleEnumConverter`1&lt;Microsoft.Azure.Search.Models.SynonymMapFormat&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="de484-101">Azure Search synonymmap の形式を定義します。</span><span class="sxs-lookup"><span data-stu-id="de484-101">Defines the format of a Azure Search synonymmap.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMapFormat Create (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMapFormat Create(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMapFormat.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (name As String) As SynonymMapFormat" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Search.Models.SynonymMapFormat" Usage="Microsoft.Azure.Search.Models.SynonymMapFormat.Create name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapFormat</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="de484-102">シノニム マップ形式の名前です。</span><span class="sxs-lookup"><span data-stu-id="de484-102">Name of the synonym map format.</span></span></param>
        <summary>
            <span data-ttu-id="de484-103">新しい SynonymMapFormat インスタンスを作成または指定された名前の既知の類義語形式のものと一致する場合は、既存のインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="de484-103">Creates a new SynonymMapFormat instance, or returns an existing instance if the given name matches that of a known synonym format.</span></span>
            </summary>
        <returns><span data-ttu-id="de484-104">指定した名前の SynonymMapFormat インスタンス。</span><span class="sxs-lookup"><span data-stu-id="de484-104">A SynonymMapFormat instance with the given name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="op_Implicit">
      <MemberSignature Language="C#" Value="public static implicit operator Microsoft.Azure.Search.Models.SynonymMapFormat (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig specialname class Microsoft.Azure.Search.Models.SynonymMapFormat op_Implicit(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymMapFormat.op_Implicit(System.String)~Microsoft.Azure.Search.Models.SynonymMapFormat" />
      <MemberSignature Language="VB.NET" Value="Public Shared Widening Operator CType (name As String) As SynonymMapFormat" />
      <MemberSignature Language="F#" Value="static member op_Implicit : string -&gt; Microsoft.Azure.Search.Models.SynonymMapFormat" Usage="Microsoft.Azure.Search.Models.SynonymMapFormat.op_Implicit name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapFormat</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="de484-105">変換する文字列。</span><span class="sxs-lookup"><span data-stu-id="de484-105">string to convert.</span></span></param>
        <summary>
            <span data-ttu-id="de484-106">文字列から SynonymMapFormat への暗黙的な変換を定義します。</span><span class="sxs-lookup"><span data-stu-id="de484-106">Defines implicit conversion from string to SynonymMapFormat.</span></span>
            </summary>
        <returns><span data-ttu-id="de484-107">SynonymMapFormat として文字列です。</span><span class="sxs-lookup"><span data-stu-id="de484-107">The string as a SynonymMapFormat.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Solr">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Search.Models.SynonymMapFormat Solr;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Search.Models.SynonymMapFormat Solr" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Search.Models.SynonymMapFormat.Solr" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Solr As SynonymMapFormat " />
      <MemberSignature Language="F#" Value=" staticval mutable Solr : Microsoft.Azure.Search.Models.SynonymMapFormat" Usage="Microsoft.Azure.Search.Models.SynonymMapFormat.Solr" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="de484-108">Solr 類義語形式を示します</span><span class="sxs-lookup"><span data-stu-id="de484-108">Indicates Solr synonyms format</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>