<Type Name="TypeCheckFunctionsExtensions" FullName="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions">
  <TypeSignature Language="C#" Value="public static class TypeCheckFunctionsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TypeCheckFunctionsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TypeCheckFunctionsExtensions" />
  <TypeSignature Language="F#" Value="type TypeCheckFunctionsExtensions = class" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5ad4d-101">型をチェックするためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-101">Provide methods for type checking.</span></span>
            <span data-ttu-id="5ad4d-102">これらのメソッドは、LINQ 式のみで使用されをサーバーで評価します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-102">These methods are to be used in LINQ expressions only and will be evaluated on server.</span></span>
            <span data-ttu-id="5ad4d-103">クライアント ライブラリで提供される実装はありません。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-103">There's no implementation provided in the client library.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="IsDefined">
      <MemberSignature Language="C#" Value="public static bool IsDefined (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDefined(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsDefined(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsDefined (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDefined : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsDefined obj" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="5ad4d-104">特定のプロパティが定義されているかを判断します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-104">Determines if a certain property is defined or not.</span></span>
            </summary>
        <returns><span data-ttu-id="5ad4d-105">True 場合、このプロパティが定義されている場合は false を返しますを返します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-105">Returns true if this property is defined otherwise returns false.</span></span></returns>
        <remarks />
        <example>
          <code><![CDATA[
            var isDefinedQuery = documents.Where(document => document.Name.IsDefined());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsNull">
      <MemberSignature Language="C#" Value="public static bool IsNull (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsNull(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsNull(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsNull (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsNull : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsNull obj" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="5ad4d-106">特定のプロパティが null かどうかを決定します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-106">Determines if a certain property is null or not.</span></span>
            </summary>
        <returns><span data-ttu-id="5ad4d-107">返しますそれ以外の場合このプロパティが null の場合は true が false を返します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-107">Returns true if this property is null otherwise returns false.</span></span></returns>
        <remarks />
        <example>
          <code><![CDATA[
            var isNullQuery = documents.Where(document => document.Name.IsNull());
            ]]></code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="IsPrimitive">
      <MemberSignature Language="C#" Value="public static bool IsPrimitive (this object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsPrimitive(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsPrimitive(System.Object)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsPrimitive (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsPrimitive : obj -&gt; bool" Usage="Microsoft.Azure.Documents.SystemFunctions.TypeCheckFunctionsExtensions.IsPrimitive obj" />
      <MemberType>Method</MemberType>
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" RefType="this" />
      </Parameters>
      <Docs>
        <param name="obj"></param>
        <summary>
            <span data-ttu-id="5ad4d-108">特定のプロパティが premitive JSON 型のかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-108">Determines if a certain property is of premitive JSON type.</span></span>
            </summary>
        <returns><span data-ttu-id="5ad4d-109">返しますそれ以外の場合このプロパティが null の場合は true が false を返します。</span><span class="sxs-lookup"><span data-stu-id="5ad4d-109">Returns true if this property is null otherwise returns false.</span></span></returns>
        <remarks>
            <span data-ttu-id="5ad4d-110">Premitive JSON 型 (Double、文字列、ブール値および Null)</span><span class="sxs-lookup"><span data-stu-id="5ad4d-110">Premitive JSON types (Double, String, Boolean and Null)</span></span>
            </remarks>
        <example>
          <code><![CDATA[
            var isPrimitiveQuery = documents.Where(document => document.Name.IsPrimitive());
            ]]></code>
        </example>
      </Docs>
    </Member>
  </Members>
</Type>