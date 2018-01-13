<Type Name="IWithPlan" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan">
  <TypeSignature Language="C#" Value="public interface IWithPlan" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPlan" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPlan" />
  <TypeSignature Language="F#" Value="type IWithPlan = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リソース プランを変更できるように、汎用リソース更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithoutPlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithoutPlan() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan.WithoutPlan" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPlan () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPlan : unit -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate" Usage="iWithPlan.WithoutPlan " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リソースのプランを指定します。
            </summary>
        <returns>汎用リソース更新の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithPlan (string name, string publisher, string product, string promotionCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate WithPlan(string name, string publisher, string product, string promotionCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithPlan.WithPlan(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlan (name As String, publisher As String, product As String, promotionCode As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPlan : string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate" Usage="iWithPlan.WithPlan (name, publisher, product, promotionCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
        <Parameter Name="product" Type="System.String" />
        <Parameter Name="promotionCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">プランを名前します。</param>
        <param name="publisher">計画の発行元のパブリッシャー</param>
        <param name="product">製品の製品名</param>
        <param name="promotionCode">promotionCode 存在する場合、プロモーション コード</param>
        <summary>
            リソースのプランを指定します。
            </summary>
        <returns>汎用リソース更新の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>