<Type Name="SearchSort" FullName="Microsoft.Azure.Management.OperationalInsights.Models.SearchSort">
  <TypeSignature Language="C#" Value="public class SearchSort" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchSort extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.Models.SearchSort" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchSort" />
  <TypeSignature Language="F#" Value="type SearchSort = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ca734-101">検索の並べ替えパラメーター。</span><span class="sxs-lookup"><span data-stu-id="ca734-101">The sort parameters for search.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchSort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ca734-102">SearchSort クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca734-102">Initializes a new instance of the SearchSort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchSort (string name = null, string order = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string order) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional order As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.OperationalInsights.Models.SearchSort : string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchSort" Usage="new Microsoft.Azure.Management.OperationalInsights.Models.SearchSort (name, order)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="order" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="ca734-103">フィールドの名前で検索クエリが並べ替えられます。</span><span class="sxs-lookup"><span data-stu-id="ca734-103">The name of the field the search query is sorted on.</span></span></param>
        <param name="order"><span data-ttu-id="ca734-104">検索の並べ替え順序。</span><span class="sxs-lookup"><span data-stu-id="ca734-104">The sort order of the search.</span></span> <span data-ttu-id="ca734-105">使用可能な値が含まれます: 'asc'、'desc'</span><span class="sxs-lookup"><span data-stu-id="ca734-105">Possible values include: 'asc', 'desc'</span></span></param>
        <summary>
            <span data-ttu-id="ca734-106">SearchSort クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ca734-106">Initializes a new instance of the SearchSort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca734-107">取得または設定に並べ替え順序は、検索クエリ フィールドの名前。</span><span class="sxs-lookup"><span data-stu-id="ca734-107">Gets or sets the name of the field the search query is sorted on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Order">
      <MemberSignature Language="C#" Value="public string Order { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Order" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.Order" />
      <MemberSignature Language="VB.NET" Value="Public Property Order As String" />
      <MemberSignature Language="F#" Value="member this.Order : string with get, set" Usage="Microsoft.Azure.Management.OperationalInsights.Models.SearchSort.Order" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="order")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ca734-108">取得または検索の並べ替え順序を設定します。</span><span class="sxs-lookup"><span data-stu-id="ca734-108">Gets or sets the sort order of the search.</span></span> <span data-ttu-id="ca734-109">使用可能な値が含まれます: 'asc'、'desc'</span><span class="sxs-lookup"><span data-stu-id="ca734-109">Possible values include: 'asc', 'desc'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>