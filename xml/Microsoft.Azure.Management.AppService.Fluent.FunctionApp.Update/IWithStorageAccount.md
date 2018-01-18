<Type Name="IWithStorageAccount" FullName="Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithStorageAccount">
  <TypeSignature Language="C#" Value="public interface IWithStorageAccount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStorageAccount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStorageAccount" />
  <TypeSignature Language="F#" Value="type IWithStorageAccount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f92d1-101">関数アプリの定義を指定するストレージ アカウントを許可します。</span><span class="sxs-lookup"><span data-stu-id="f92d1-101">A function app definition allowing storage account to be specified.</span></span>
            <span data-ttu-id="f92d1-102">ストレージ アカウントは、実行ランタイムの関数、トリガー、およびログを格納する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f92d1-102">A storage account is required for storing function execution runtime, triggers, and logs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithExistingStorageAccount (Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithExistingStorageAccount(class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithStorageAccount.WithExistingStorageAccount(Microsoft.Azure.Management.Storage.Fluent.IStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingStorageAccount (storageAccount As IStorageAccount) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingStorageAccount : Microsoft.Azure.Management.Storage.Fluent.IStorageAccount -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithStorageAccount.WithExistingStorageAccount storageAccount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
      </Parameters>
      <Docs>
        <param name="storageAccount"><span data-ttu-id="f92d1-103">使用するストレージ アカウント。</span><span class="sxs-lookup"><span data-stu-id="f92d1-103">The storage account to use.</span></span></param>
        <summary>
            <span data-ttu-id="f92d1-104">関数アプリに使用するストレージ アカウントを指定します。</span><span class="sxs-lookup"><span data-stu-id="f92d1-104">Specifies the storage account to use for the function app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f92d1-105">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f92d1-105">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStorageAccount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewStorageAccount (string name, Microsoft.Azure.Management.Storage.Fluent.Models.SkuName sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate WithNewStorageAccount(string name, valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuName sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IWithStorageAccount.WithNewStorageAccount(System.String,Microsoft.Azure.Management.Storage.Fluent.Models.SkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStorageAccount (name As String, sku As SkuName) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewStorageAccount : string * Microsoft.Azure.Management.Storage.Fluent.Models.SkuName -&gt; Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate" Usage="iWithStorageAccount.WithNewStorageAccount (name, sku)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.FunctionApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.SkuName" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f92d1-106">ストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f92d1-106">The name of the storage account.</span></span></param>
        <param name="sku"><span data-ttu-id="f92d1-107">ストレージ アカウントの sku。</span><span class="sxs-lookup"><span data-stu-id="f92d1-107">The sku of the storage account.</span></span></param>
        <summary>
            <span data-ttu-id="f92d1-108">関数アプリに使用する新しいストレージ アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="f92d1-108">Creates a new storage account to use for the function app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f92d1-109">関数アプリの更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="f92d1-109">The next stage of the function app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>