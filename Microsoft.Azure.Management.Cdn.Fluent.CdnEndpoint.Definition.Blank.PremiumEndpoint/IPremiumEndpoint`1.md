<Type Name="IPremiumEndpoint&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IPremiumEndpoint&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPremiumEndpoint`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPremiumEndpoint(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IPremiumEndpoint&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親 CDN プロファイル定義の段階です。</typeparam>
    <summary>
            CDN プロファイルのための原点を Premium Verizon SKU を指定するように、CDN プロファイルのエンドポイントの定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin originHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originHostName">配信元ホスト名です。</param>
        <summary>
            CDN エンドポイントの配信元を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt; WithPremiumOrigin (string originName, string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach`1&lt;!ParentT&gt; WithPremiumOrigin(string originName, string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.PremiumEndpoint.IPremiumEndpoint`1.WithPremiumOrigin(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumOrigin (originName As String, originHostName As String) As IWithPremiumAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumOrigin : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;'ParentT&gt;" Usage="iPremiumEndpoint.WithPremiumOrigin (originName, originHostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithPremiumAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originName">配信元の名前です。</param>
        <param name="originHostName">配信元ホスト名です。</param>
        <summary>
            CDN エンドポイントの配信元を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>