<Type Name="AclActionExtension" FullName="Microsoft.Azure.DataLake.Store.Acl.AclActionExtension">
  <TypeSignature Language="C#" Value="public static class AclActionExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AclActionExtension extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.Acl.AclActionExtension" />
  <TypeSignature Language="VB.NET" Value="Public Module AclActionExtension" />
  <TypeSignature Language="F#" Value="type AclActionExtension = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="48802-101">拡張機能クラス</span><span class="sxs-lookup"><span data-stu-id="48802-101">Extension class</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAclAction">
      <MemberSignature Language="C#" Value="public static Nullable&lt;Microsoft.Azure.DataLake.Store.Acl.AclAction&gt; GetAclAction (string rwx);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction&gt; GetAclAction(string rwx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclActionExtension.GetAclAction(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAclAction (rwx As String) As Nullable(Of AclAction)" />
      <MemberSignature Language="F#" Value="static member GetAclAction : string -&gt; Nullable&lt;Microsoft.Azure.DataLake.Store.Acl.AclAction&gt;" Usage="Microsoft.Azure.DataLake.Store.Acl.AclActionExtension.GetAclAction rwx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.DataLake.Store.Acl.AclAction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rwx" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rwx"><span data-ttu-id="48802-102">8 進数のアクセス許可</span><span class="sxs-lookup"><span data-stu-id="48802-102">Octal permission</span></span></param>
        <summary>
            <span data-ttu-id="48802-103">8 進数のアクセス許可に対応する AclAction を返します。</span><span class="sxs-lookup"><span data-stu-id="48802-103">Returns the AclAction corresponding to the octal permission.</span></span> <span data-ttu-id="48802-104">"Rwx"AclAction.All を返します</span><span class="sxs-lookup"><span data-stu-id="48802-104">For "rwx" returns AclAction.All</span></span>
            </summary>
        <returns><span data-ttu-id="48802-105">Acl のアクション</span><span class="sxs-lookup"><span data-stu-id="48802-105">Acl Action</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRwx">
      <MemberSignature Language="C#" Value="public static string GetRwx (this Microsoft.Azure.DataLake.Store.Acl.AclAction act);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetRwx(valuetype Microsoft.Azure.DataLake.Store.Acl.AclAction act) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.Acl.AclActionExtension.GetRwx(Microsoft.Azure.DataLake.Store.Acl.AclAction)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRwx (act As AclAction) As String" />
      <MemberSignature Language="F#" Value="static member GetRwx : Microsoft.Azure.DataLake.Store.Acl.AclAction -&gt; string" Usage="Microsoft.Azure.DataLake.Store.Acl.AclActionExtension.GetRwx act" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="act" Type="Microsoft.Azure.DataLake.Store.Acl.AclAction" RefType="this" />
      </Parameters>
      <Docs>
        <param name="act"><span data-ttu-id="48802-106">Acl のアクション</span><span class="sxs-lookup"><span data-stu-id="48802-106">Acl aCtion</span></span></param>
        <summary>
            <span data-ttu-id="48802-107">AclACtion を 8 進数に対応する権限を返す拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="48802-107">Extension method that returns the octal permission corresponding to the AclACtion.</span></span> <span data-ttu-id="48802-108">Ex: AclAction.ReadExecute =&gt; "r x"</span><span class="sxs-lookup"><span data-stu-id="48802-108">For ex: AclAction.ReadExecute =&gt; "r-x"</span></span>
            </summary>
        <returns><span data-ttu-id="48802-109">8 進数のアクセス許可文字列</span><span class="sxs-lookup"><span data-stu-id="48802-109">Octal permission string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>