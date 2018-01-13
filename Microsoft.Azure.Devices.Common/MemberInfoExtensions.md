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
            リフレクションのサポートを拡張
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
        <param name="member">名前が必要なメンバー</param>
        <summary>
            完全修飾名 (アセンブリ、クラス、メンバー) を検索するメンバーの参照を指定すると、
            </summary>
        <returns>アセンブリ、名前空間、クラス、およびメンバーを含む、完全修飾メンバー名</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>