<Type Name="IWithPostalCode&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPostalCode&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPostalCode`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPostalCode(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPostalCode&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="cf305-101">アタッチした後に戻るに親の定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="cf305-101">The stage of the parent definition to return to after attaching.</span></span></typeparam>
    <summary>
            <span data-ttu-id="cf305-102">設定する郵便番号/zip コードを許可するメンバーの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="cf305-102">The stage of contact definition allowing postal/zip code to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPostalCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;ParentT&gt; WithPostalCode (string postalCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode`1&lt;!ParentT&gt; WithPostalCode(string postalCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode`1.WithPostalCode(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPostalCode (postalCode As String) As IWithPhoneCountryCode(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPostalCode : string -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;'ParentT&gt;" Usage="iWithPostalCode.WithPostalCode postalCode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="postalCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="postalCode"><span data-ttu-id="cf305-103">住所の郵便番号。</span><span class="sxs-lookup"><span data-stu-id="cf305-103">The postal code of the address.</span></span></param>
        <summary>
            <span data-ttu-id="cf305-104">郵便番号、住所の郵便番号コードを指定します。</span><span class="sxs-lookup"><span data-stu-id="cf305-104">Specifies the postal code or zip code of the address.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cf305-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="cf305-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>