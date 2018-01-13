<Type Name="ContentHash" FullName="Microsoft.Azure.Management.Automation.Models.ContentHash">
  <TypeSignature Language="C#" Value="public class ContentHash" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContentHash extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.ContentHash" />
  <TypeSignature Language="VB.NET" Value="Public Class ContentHash" />
  <TypeSignature Language="F#" Value="type ContentHash = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2434f-101">Runbook のプロパティの型の定義。</span><span class="sxs-lookup"><span data-stu-id="2434f-101">Definition of the runbook property type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContentHash ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ContentHash.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2434f-102">ContentHash クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2434f-102">Initializes a new instance of the ContentHash class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContentHash (string algorithm, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string algorithm, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.ContentHash.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (algorithm As String, value As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.Models.ContentHash : string * string -&gt; Microsoft.Azure.Management.Automation.Models.ContentHash" Usage="new Microsoft.Azure.Management.Automation.Models.ContentHash (algorithm, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="algorithm">To be added.</param>
        <param name="value">To be added.</param>
        <summary>
            <span data-ttu-id="2434f-103">必須の引数で ContentHash クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2434f-103">Initializes a new instance of the ContentHash class with required arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ContentHash.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ContentHash.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2434f-104">必須。</span><span class="sxs-lookup"><span data-stu-id="2434f-104">Required.</span></span> <span data-ttu-id="2434f-105">取得またはコンテンツのハッシュに使用されるコンテンツのハッシュ アルゴリズムを設定します。</span><span class="sxs-lookup"><span data-stu-id="2434f-105">Gets or sets the content hash algorithm used to hash the content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.ContentHash.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.ContentHash.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2434f-106">必須。</span><span class="sxs-lookup"><span data-stu-id="2434f-106">Required.</span></span> <span data-ttu-id="2434f-107">取得またはコンテンツの必要なハッシュ値を設定します。</span><span class="sxs-lookup"><span data-stu-id="2434f-107">Gets or sets expected hash value of the content.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>