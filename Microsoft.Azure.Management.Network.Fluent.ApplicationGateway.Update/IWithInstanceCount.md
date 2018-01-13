<Type Name="IWithInstanceCount" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount">
  <TypeSignature Language="C#" Value="public interface IWithInstanceCount" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInstanceCount" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInstanceCount" />
  <TypeSignature Language="F#" Value="type IWithInstanceCount = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイの更新を許可するアプリケーション ゲートウェイの容量 (インスタンスの数) を指定の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithInstanceCount">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithInstanceCount (int instanceCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithInstanceCount(int32 instanceCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithInstanceCount.WithInstanceCount(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithInstanceCount (instanceCount As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithInstanceCount : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithInstanceCount.WithInstanceCount instanceCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="instanceCount">1 と 10 個が選択されている applicatiob ゲートウェイのサイズの制限に基づくまでの数値として容量。</param>
        <summary>
            アプリケーション ゲートウェイの容量 (インスタンスの数) を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>