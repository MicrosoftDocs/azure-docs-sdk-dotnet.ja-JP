<Type Name="ISupportsBatchDeletion" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion">
  <TypeSignature Language="C#" Value="public interface ISupportsBatchDeletion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsBatchDeletion implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsBatchDeletion&#xA;Implements IBeta" />
  <TypeSignature Language="F#" Value="type ISupportsBatchDeletion = interface&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="00dd8-101">Azure を識別するを id から複数のリソースを削除するには、アクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="00dd8-101">Provides access to deleting multiple resource from Azure, identifying them by their IDs.</span></span>
            <span data-ttu-id="00dd8-102">(注: このインターフェイスは、ユーザー コードで実装するものではありません。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-102">(Note this interface is not intended to be implemented by user code.).</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="00dd8-103">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-103">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteByIds">
      <MemberSignature Language="C#" Value="public void DeleteByIds (System.Collections.Generic.IList&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByIds(class System.Collections.Generic.IList`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion.DeleteByIds(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByIds (ids As IList(Of String))" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIds : System.Collections.Generic.IList&lt;string&gt; -&gt; unit" Usage="iSupportsBatchDeletion.DeleteByIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="00dd8-104">リソースを削除するには、リソースの Id。</span><span class="sxs-lookup"><span data-stu-id="00dd8-104">Resource IDs of the resources to be deleted.</span></span></param>
        <summary>
            <span data-ttu-id="00dd8-105">Azure から、指定したリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="00dd8-105">Deletes the specified resources from Azure.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="00dd8-106">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-106">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIds">
      <MemberSignature Language="C#" Value="public void DeleteByIds (params string[] ids);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByIds(string[] ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion.DeleteByIds(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByIds (ParamArray ids As String())" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIds : string[] -&gt; unit" Usage="iSupportsBatchDeletion.DeleteByIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="00dd8-107">リソースを削除するには、リソースの Id。</span><span class="sxs-lookup"><span data-stu-id="00dd8-107">Resource IDs of the resources to be deleted.</span></span></param>
        <summary>
            <span data-ttu-id="00dd8-108">Azure から、指定したリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="00dd8-108">Deletes the specified resources from Azure.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="00dd8-109">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-109">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; DeleteByIdsAsync (System.Collections.Generic.IList&lt;string&gt; ids, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; DeleteByIdsAsync(class System.Collections.Generic.IList`1&lt;string&gt; ids, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion.DeleteByIdsAsync(System.Collections.Generic.IList{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdsAsync : System.Collections.Generic.IList&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iSupportsBatchDeletion.DeleteByIdsAsync (ids, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="00dd8-110">リソースを削除するには、リソースの Id。</span><span class="sxs-lookup"><span data-stu-id="00dd8-110">Resource IDs of the resources to be deleted.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="00dd8-111">非同期的と並列では、Azure から、指定したリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="00dd8-111">Deletes the specified resources from Azure asynchronously and in parallel.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="00dd8-112">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-112">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="00dd8-113">監視対象元となるすべてのリソースが正常に削除すると確認できます。</span><span class="sxs-lookup"><span data-stu-id="00dd8-113">An observable from which all of the successfully deleted resources can be observed.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; DeleteByIdsAsync (string[] ids, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; DeleteByIdsAsync(string[] ids, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchDeletion.DeleteByIdsAsync(System.String[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdsAsync : string[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iSupportsBatchDeletion.DeleteByIdsAsync (ids, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.String[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="00dd8-114">リソースを削除するには、リソースの Id。</span><span class="sxs-lookup"><span data-stu-id="00dd8-114">Resource IDs of the resources to be deleted.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="00dd8-115">非同期的と並列では、Azure から、指定したリソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="00dd8-115">Deletes the specified resources from Azure asynchronously and in parallel.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="00dd8-116">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです。)。</span><span class="sxs-lookup"><span data-stu-id="00dd8-116">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="00dd8-117">監視対象元となるすべてのリソースが正常に削除すると確認できます。</span><span class="sxs-lookup"><span data-stu-id="00dd8-117">An observable from which all of the successfully deleted resources can be observed.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>