<Type Name="ApplicationPrincipalsDescription" FullName="System.Fabric.Description.ApplicationPrincipalsDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationPrincipalsDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationPrincipalsDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationPrincipalsDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationPrincipalsDescription" />
  <TypeSignature Language="F#" Value="type ApplicationPrincipalsDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="ce027-101">サービスのアプリケーションのプリンシパルについて説明します。</span><span class="sxs-lookup"><span data-stu-id="ce027-101">Describes the application principals of the service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPrincipalsDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationPrincipalsDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="ce027-102">作成して初期化、<see cref="T:System.Fabric.Description.ApplicationPrincipalsDescription" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="ce027-102">Creates and initializes an <see cref="T:System.Fabric.Description.ApplicationPrincipalsDescription" /> object.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Groups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt; Groups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.SecurityGroupDescription&gt; Groups" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationPrincipalsDescription.Groups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Groups As IList(Of SecurityGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.Groups : System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt;" Usage="System.Fabric.Description.ApplicationPrincipalsDescription.Groups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ce027-103">アプリケーション マニフェストでアプリケーション環境のセットアップの一部として作成する必要がありますグループを取得します。</span><span class="sxs-lookup"><span data-stu-id="ce027-103">Gets the groups that must be created as a part of the application environment setup in the application manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ce027-104">このグループは、アプリケーション マニフェストでアプリケーション環境のセットアップの一部として作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ce027-104">The groups that must be created as a part of the application environment setup in the application manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.SecurityUserDescription&gt; Users" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationPrincipalsDescription.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IList(Of SecurityUserDescription)" />
      <MemberSignature Language="F#" Value="member this.Users : System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt;" Usage="System.Fabric.Description.ApplicationPrincipalsDescription.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="ce027-105">アプリケーション マニフェストでアプリケーション環境のセットアップの一部として作成する必要がありますユーザーを取得します。</span><span class="sxs-lookup"><span data-stu-id="ce027-105">Gets the users that must be created as a part of the application environment setup in the application manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="ce027-106">このユーザーは、アプリケーション マニフェストでアプリケーション環境のセットアップの一部として作成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ce027-106">The users that must be created as a part of the application environment setup in the application manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>