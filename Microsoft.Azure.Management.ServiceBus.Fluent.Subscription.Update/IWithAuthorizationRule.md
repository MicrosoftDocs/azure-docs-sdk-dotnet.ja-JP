<Type Name="IWithAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithAuthorizationRule">
  <TypeSignature Language="C#" Value="public interface IWithAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthorizationRule" />
  <TypeSignature Language="F#" Value="type IWithAuthorizationRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            サブスクリプションへのアクセスの承認規則の追加を許可するキューの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewAuthorizationRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithNewAuthorizationRule (string name, params Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithNewAuthorizationRule(string name, valuetype Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithAuthorizationRule.WithNewAuthorizationRule(System.String,Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAuthorizationRule (name As String, ParamArray rights As AccessRights()) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAuthorizationRule : string * Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[] -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewAuthorizationRule (name, rights)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="rights" Type="Microsoft.Azure.Management.ServiceBus.Fluent.Models.AccessRights[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <param name="rights">ルールに関する権利。</param>
        <summary>
            サブスクリプションの承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプションの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNewAuthorizationRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutNewAuthorizationRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate WithoutNewAuthorizationRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IWithAuthorizationRule.WithoutNewAuthorizationRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNewAuthorizationRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNewAuthorizationRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate" Usage="iWithAuthorizationRule.WithoutNewAuthorizationRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Subscription.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <summary>
            サブスクリプションの承認規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>サブスクリプションの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>