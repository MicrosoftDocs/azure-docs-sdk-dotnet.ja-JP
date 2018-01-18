<Type Name="SqlFuncs" FullName="Microsoft.Azure.Mobile.Server.SqlFuncs">
  <TypeSignature Language="C#" Value="public static class SqlFuncs" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SqlFuncs extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.SqlFuncs" />
  <TypeSignature Language="VB.NET" Value="Public Class SqlFuncs" />
  <TypeSignature Language="F#" Value="type SqlFuncs = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", Justification="Temporary", MessageId="Funcs")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StringConvert">
      <MemberSignature Language="C#" Value="public static string StringConvert (Nullable&lt;double&gt; number);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string StringConvert(valuetype System.Nullable`1&lt;float64&gt; number) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert(System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StringConvert (number As Nullable(Of Double)) As String" />
      <MemberSignature Language="F#" Value="static member StringConvert : Nullable&lt;double&gt; -&gt; string" Usage="Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert number" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Data.Entity.DbFunction("SqlServer", "STR")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="number" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="number"><span data-ttu-id="52191-101">数値式です。</span><span class="sxs-lookup"><span data-stu-id="52191-101">A numeric expression.</span></span></param>
        <summary><span data-ttu-id="52191-102">数値データから変換されたデータの文字を返します。</span><span class="sxs-lookup"><span data-stu-id="52191-102">Returns character data converted from numeric data.</span></span></summary>
        <returns><span data-ttu-id="52191-103">入力された式は、文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="52191-103">The input expression converted to a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StringConvert">
      <MemberSignature Language="C#" Value="public static string StringConvert (Nullable&lt;double&gt; number, Nullable&lt;int&gt; length);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string StringConvert(valuetype System.Nullable`1&lt;float64&gt; number, valuetype System.Nullable`1&lt;int32&gt; length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert(System.Nullable{System.Double},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StringConvert (number As Nullable(Of Double), length As Nullable(Of Integer)) As String" />
      <MemberSignature Language="F#" Value="static member StringConvert : Nullable&lt;double&gt; * Nullable&lt;int&gt; -&gt; string" Usage="Microsoft.Azure.Mobile.Server.SqlFuncs.StringConvert (number, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Entity</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Data.Entity.DbFunction("SqlServer", "STR")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="number" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="number"><span data-ttu-id="52191-104">数値式です。</span><span class="sxs-lookup"><span data-stu-id="52191-104">A numeric expression.</span></span></param>
        <param name="length"><span data-ttu-id="52191-105">文字列の長さの合計。</span><span class="sxs-lookup"><span data-stu-id="52191-105">The total length of the string.</span></span> <span data-ttu-id="52191-106">これには小数点、符号、数字、空白文字も含まれます。</span><span class="sxs-lookup"><span data-stu-id="52191-106">This includes decimal point, sign, digits, and spaces.</span></span> <span data-ttu-id="52191-107">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="52191-107">The default is 10.</span></span></param>
        <summary><span data-ttu-id="52191-108">数値データから変換されたデータの文字を返します。</span><span class="sxs-lookup"><span data-stu-id="52191-108">Returns character data converted from numeric data.</span></span></summary>
        <returns><span data-ttu-id="52191-109">入力された数値式は、文字列に変換します。</span><span class="sxs-lookup"><span data-stu-id="52191-109">The numeric input expression converted to a string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>