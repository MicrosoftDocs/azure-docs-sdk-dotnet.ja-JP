<Type Name="IDomainContact" FullName="Microsoft.Azure.Management.AppService.Fluent.IDomainContact">
  <TypeSignature Language="C#" Value="public interface IDomainContact : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Contact&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDomainContact implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.Contact&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IDomainContact" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDomainContact&#xA;Implements IBeta, IChildResource(Of IAppServiceDomain), IHasInner(Of Contact), IHasParent(Of IAppServiceDomain)" />
  <TypeSignature Language="F#" Value="type IDomainContact = interface&#xA;    interface IBeta&#xA;    interface IHasInner&lt;Contact&gt;&#xA;    interface IChildResource&lt;IAppServiceDomain&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IAppServiceDomain&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.Contact&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="68b36-101">ドメイン メンバー定義。</span><span class="sxs-lookup"><span data-stu-id="68b36-101">A domain contact definition.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="68b36-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="68b36-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AddressMailing">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Address AddressMailing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Address AddressMailing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.AddressMailing" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AddressMailing As Address" />
      <MemberSignature Language="F#" Value="member this.AddressMailing : Microsoft.Azure.Management.AppService.Fluent.Models.Address" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.AddressMailing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Address</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-103">郵送先住所を連絡先の取得します。</span><span class="sxs-lookup"><span data-stu-id="68b36-103">Gets contact's mailing address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Email">
      <MemberSignature Language="C#" Value="public string Email { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Email" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Email" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Email As String" />
      <MemberSignature Language="F#" Value="member this.Email : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Email" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-104">取得連絡先の電子メール アドレス。</span><span class="sxs-lookup"><span data-stu-id="68b36-104">Gets contact's email address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fax">
      <MemberSignature Language="C#" Value="public string Fax { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fax" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Fax" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fax As String" />
      <MemberSignature Language="F#" Value="member this.Fax : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Fax" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-105">取得連絡先の fax 番号。</span><span class="sxs-lookup"><span data-stu-id="68b36-105">Gets contact's fax number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirstName">
      <MemberSignature Language="C#" Value="public string FirstName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FirstName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.FirstName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirstName As String" />
      <MemberSignature Language="F#" Value="member this.FirstName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.FirstName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-106">取得連絡先の名前。</span><span class="sxs-lookup"><span data-stu-id="68b36-106">Gets contact's first name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobTitle">
      <MemberSignature Language="C#" Value="public string JobTitle { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.JobTitle" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobTitle As String" />
      <MemberSignature Language="F#" Value="member this.JobTitle : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.JobTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-107">取得連絡先の役職名。</span><span class="sxs-lookup"><span data-stu-id="68b36-107">Gets contact's job title.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastName">
      <MemberSignature Language="C#" Value="public string LastName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.LastName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastName As String" />
      <MemberSignature Language="F#" Value="member this.LastName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.LastName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-108">取得連絡先の姓。</span><span class="sxs-lookup"><span data-stu-id="68b36-108">Gets contact's last name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MiddleName">
      <MemberSignature Language="C#" Value="public string MiddleName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MiddleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.MiddleName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MiddleName As String" />
      <MemberSignature Language="F#" Value="member this.MiddleName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.MiddleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-109">取得連絡先のミドル ネームです。</span><span class="sxs-lookup"><span data-stu-id="68b36-109">Gets contact's middle name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Organization">
      <MemberSignature Language="C#" Value="public string Organization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Organization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Organization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Organization As String" />
      <MemberSignature Language="F#" Value="member this.Organization : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Organization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-110">組織の連絡先の取得。</span><span class="sxs-lookup"><span data-stu-id="68b36-110">Gets contact's organization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Phone">
      <MemberSignature Language="C#" Value="public string Phone { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Phone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Phone" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Phone As String" />
      <MemberSignature Language="F#" Value="member this.Phone : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IDomainContact.Phone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="68b36-111">取得連絡先の電話番号。</span><span class="sxs-lookup"><span data-stu-id="68b36-111">Gets contact's phone number.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>