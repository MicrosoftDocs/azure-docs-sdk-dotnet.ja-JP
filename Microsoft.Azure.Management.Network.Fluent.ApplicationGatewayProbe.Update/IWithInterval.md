<Type Name="IWithInterval" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval">
  <TypeSignature Language="C#" Value="public interface IWithInterval" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInterval" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInterval" />
  <TypeSignature Language="F#" Value="type IWithInterval = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイ プローブ更新できるようにする連続するプローブの間隔を指定の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeBetweenProbesInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeBetweenProbesInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeBetweenProbesInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithInterval.WithTimeBetweenProbesInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeBetweenProbesInSeconds (seconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTimeBetweenProbesInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithInterval.WithTimeBetweenProbesInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds">1 ~ 86400 秒の数。</param>
        <summary>
            連続するプローブ間隔 (秒) の時間間隔を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>