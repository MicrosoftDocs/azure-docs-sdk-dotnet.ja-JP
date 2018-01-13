<Type Name="IWithAuthorizationRule" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule">
  <TypeSignature Language="C#" Value="public interface IWithAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAuthorizationRule" />
  <TypeSignature Language="F#" Value="type IWithAuthorizationRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            キューへのアクセスの承認規則の追加を許可するキューの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewListenRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewListenRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewListenRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule.WithNewListenRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewListenRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewListenRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewListenRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <summary>
            キューにリッスンの承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewManageRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewManageRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewManageRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule.WithNewManageRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewManageRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewManageRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewManageRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <summary>
            キューの管理の承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSendRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewSendRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithNewSendRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule.WithNewSendRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSendRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSendRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithAuthorizationRule.WithNewSendRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <summary>
            キューの送信の承認規則を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAuthorizationRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutAuthorizationRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate WithoutAuthorizationRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IWithAuthorizationRule.WithoutAuthorizationRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAuthorizationRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAuthorizationRule : string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate" Usage="iWithAuthorizationRule.WithoutAuthorizationRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.Queue.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">規則の名前。</param>
        <summary>
            キューの承認規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>キュー更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>