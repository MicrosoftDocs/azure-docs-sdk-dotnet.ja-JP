<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ロード バランサーのステージでは、追加またはバックエンドを削除する許可を更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.DefineBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackend (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithBackend.DefineBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しいバックエンドの名前。</param>
        <summary>
            このロード バランサーの更新プログラムの一部として、新しいバックエンドの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>バックエンドの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate UpdateBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate UpdateBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.UpdateBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate" Usage="iWithBackend.UpdateBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">更新するバックエンドの名前。</param>
        <summary>
            このロード バランサーの既存のバックエンドを更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithBackend.WithoutBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithBackend.WithoutBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除するバックエンドの名前です。</param>
        <summary>
            ロード バランサーから、指定されたバックエンドを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>