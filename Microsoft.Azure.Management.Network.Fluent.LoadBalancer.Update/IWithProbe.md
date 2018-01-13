<Type Name="IWithProbe" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe">
  <TypeSignature Language="C#" Value="public interface IWithProbe" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProbe" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProbe" />
  <TypeSignature Language="F#" Value="type IWithProbe = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ロード バランサーのステージでは、追加、削除または変更のプローブを許可するを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineHttpProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineHttpProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineHttpProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe.DefineHttpProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineHttpProbe (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineHttpProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithProbe.DefineHttpProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しいプローブの名前。</param>
        <summary>
            ロード バランサーに追加する新しい HTTP プローブの定義を開始します。
            定義は、LoadBalancerHttpProbe.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineTcpProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineTcpProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineTcpProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe.DefineTcpProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineTcpProbe (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineTcpProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithProbe.DefineTcpProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">新しいプローブの名前。</param>
        <summary>
            ロード バランサーに追加する新しい TCP プローブの定義を開始します。
            定義は、LoadBalancerHttpProbe.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateHttpProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate UpdateHttpProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate UpdateHttpProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe.UpdateHttpProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateHttpProbe (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateHttpProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate" Usage="iWithProbe.UpdateHttpProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">更新するプローブの名前。</param>
        <summary>
            このロード バランサー上の既存の HTTP プローブを更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>プローブの更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateTcpProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate UpdateTcpProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate UpdateTcpProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe.UpdateTcpProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTcpProbe (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateTcpProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate" Usage="iWithProbe.UpdateTcpProbe name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">更新するプローブの名前。</param>
        <summary>
            このロード バランサー上の既存の TCP プローブを更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>プローブの更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutProbe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutProbe (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutProbe(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithProbe.WithoutProbe(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutProbe (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutProbe : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithProbe.WithoutProbe name" />
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
        <param name="name">削除するプローブの名前。</param>
        <summary>
            存在する場合は、ロード バランサーから指定のプローブを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>