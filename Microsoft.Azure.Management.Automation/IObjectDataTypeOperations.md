<Type Name="IObjectDataTypeOperations" FullName="Microsoft.Azure.Management.Automation.IObjectDataTypeOperations">
  <TypeSignature Language="C#" Value="public interface IObjectDataTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IObjectDataTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IObjectDataTypeOperations" />
  <TypeSignature Language="F#" Value="type IObjectDataTypeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ebb2d-101">オートメーション オブジェクトのデータ型のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-101">Service operation for automation object data types.</span></span>  <span data-ttu-id="ebb2d-102">(詳細については http://aka.ms/azureautomationsdk/objectdatatypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ebb2d-102">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListFieldsByModuleAndTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByModuleAndTypeAsync (string resourceGroupName, string automationAccount, string moduleName, string typeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByModuleAndTypeAsync(string resourceGroupName, string automationAccount, string moduleName, string typeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.ListFieldsByModuleAndTypeAsync(System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFieldsByModuleAndTypeAsync : string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="iObjectDataTypeOperations.ListFieldsByModuleAndTypeAsync (resourceGroupName, automationAccount, moduleName, typeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ebb2d-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ebb2d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ebb2d-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-104">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="ebb2d-105">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-105">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="ebb2d-106">型の名前。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-106">The name of type.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ebb2d-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ebb2d-108">モジュール名で識別される指定された型のフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-108">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="ebb2d-109">(詳細については http://aka.ms/azureautomationsdk/objectdatatypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ebb2d-109">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ebb2d-110">リストのフィールドの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-110">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFieldsByTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByTypeAsync (string resourceGroupName, string automationAccount, string typeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListFieldsByTypeAsync(string resourceGroupName, string automationAccount, string typeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IObjectDataTypeOperations.ListFieldsByTypeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFieldsByTypeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="iObjectDataTypeOperations.ListFieldsByTypeAsync (resourceGroupName, automationAccount, typeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ebb2d-111">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ebb2d-111">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ebb2d-112">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-112">The automation account name.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="ebb2d-113">型の名前。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-113">The name of type.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ebb2d-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ebb2d-115">アクセス可能なすべてのモジュール間で指定された型のフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-115">Retrieve a list of fields of a given type across all accessible modules.</span></span>  <span data-ttu-id="ebb2d-116">(詳細については http://aka.ms/azureautomationsdk/objectdatatypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ebb2d-116">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ebb2d-117">リストのフィールドの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ebb2d-117">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>