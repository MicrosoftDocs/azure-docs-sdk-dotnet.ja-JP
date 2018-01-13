<Type Name="IWithSku" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithSku">
  <TypeSignature Language="C#" Value="public interface IWithSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSku" />
  <TypeSignature Language="F#" Value="type IWithSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            パラメーターを変更できるように、ストレージ アカウントの更新段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithSku (Microsoft.Azure.Management.Storage.Fluent.Models.SkuName skuName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithSku(valuetype Microsoft.Azure.Management.Storage.Fluent.Models.SkuName skuName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithSku.WithSku(Microsoft.Azure.Management.Storage.Fluent.Models.SkuName)" />
      <MemberSignature Language="F#" Value="abstract member WithSku : Microsoft.Azure.Management.Storage.Fluent.Models.SkuName -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithSku.WithSku skuName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="skuName" Type="Microsoft.Azure.Management.Storage.Fluent.Models.SkuName" />
      </Parameters>
      <Docs>
        <param name="skuName">Sku。</param>
        <summary>
            ストレージ アカウントの sku を指定します。 これは、呼び出す勘定科目の種類に使用します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>ストレージ アカウントの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>