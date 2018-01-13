<Type Name="IWithMonitoringConfiguration" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithMonitoringConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMonitoringConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMonitoringConfiguration" />
  <TypeSignature Language="F#" Value="type IWithMonitoringConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            エンドポイント監視の構成を指定できるように、トラフィック マネージャー プロファイル定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration.WithHttpMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            HTTP はポート 80 を使用して、定期的に '/'、パスから HTTP 200 の応答を確認するエンドポイントの監視を使用するように指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration.WithHttpMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring (port As Integer, path As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port">監視のポートです。</param>
        <param name="path">監視のパス。</param>
        <summary>
            一定の間隔で指定されたパスからの HTTP 200 の応答を確認するエンドポイントの監視を指定したポートを使用して、HTTP を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpsMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpsMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration.WithHttpsMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            HTTPS はポート 443 を使用して、定期的に '/'、パスから HTTPS 200 の応答を確認するエンドポイントの監視を使用するように指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpsMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate WithHttpsMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithMonitoringConfiguration.WithHttpsMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring (port As Integer, path As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port">監視のポートです。</param>
        <param name="path">監視のパス。</param>
        <summary>
            一定の間隔で指定されたパスからの HTTPS 200 の応答を確認するエンドポイントの監視を指定したポートを使用して、HTTPS を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>