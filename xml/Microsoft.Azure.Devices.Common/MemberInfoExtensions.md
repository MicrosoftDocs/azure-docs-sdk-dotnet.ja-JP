<Type Name="MemberInfoExtensions" FullName="Microsoft.Azure.Devices.Common.MemberInfoExtensions">
  <TypeSignature Language="C#" Value="public static class MemberInfoExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MemberInfoExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Common.MemberInfoExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MemberInfoExtensions" />
  <TypeSignature Language="F#" Value="type MemberInfoExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8bfbc-101">リフレクションのサポートを拡張</span><span class="sxs-lookup"><span data-stu-id="8bfbc-101">Extended reflection support</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetFullyQualifiedMemberName">
      <MemberSignature Language="C#" Value="public static string GetFullyQualifiedMemberName (this System.Reflection.MemberInfo member);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFullyQualifiedMemberName(class System.Reflection.MemberInfo member) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.MemberInfoExtensions.GetFullyQualifiedMemberName(System.Reflection.MemberInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFullyQualifiedMemberName (member As MemberInfo) As String" />
      <MemberSignature Language="F#" Value="static member GetFullyQualifiedMemberName : System.Reflection.MemberInfo -&gt; string" Usage="Microsoft.Azure.Devices.Common.MemberInfoExtensions.GetFullyQualifiedMemberName member" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" RefType="this" />
      </Parameters>
      <Docs>
        <param name="member"><span data-ttu-id="8bfbc-102">名前が必要なメンバー</span><span class="sxs-lookup"><span data-stu-id="8bfbc-102">The member whose name is desired</span></span></param>
        <summary>
            <span data-ttu-id="8bfbc-103">完全修飾名 (アセンブリ、クラス、メンバー) を検索するメンバーの参照を指定すると、</span><span class="sxs-lookup"><span data-stu-id="8bfbc-103">Given a member reference, find its fully qualified name (assembly, class, member)</span></span>
            </summary>
        <returns><span data-ttu-id="8bfbc-104">アセンブリ、名前空間、クラス、およびメンバーを含む、完全修飾メンバー名</span><span class="sxs-lookup"><span data-stu-id="8bfbc-104">The fully qualified member name, including assembly, namespace, class, and member</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>