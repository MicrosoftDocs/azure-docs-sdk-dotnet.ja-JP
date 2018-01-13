<Type Name="IDefinitionWithRegion&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IDefinitionWithRegion&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDefinitionWithRegion`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDefinitionWithRegion(Of T)" />
  <TypeSignature Language="F#" Value="type IDefinitionWithRegion&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRegion">
      <MemberSignature Language="C#" Value="public T WithRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1.WithRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'T" Usage="iDefinitionWithRegion.WithRegion region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region">地域、リソースの場所</param>
        <summary>
            リソースの地域を指定します。
            </summary>
        <returns>リソース定義の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithRegion">
      <MemberSignature Language="C#" Value="public T WithRegion (string regionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithRegion(string regionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1.WithRegion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRegion (regionName As String) As T" />
      <MemberSignature Language="F#" Value="abstract member WithRegion : string -&gt; 'T" Usage="iDefinitionWithRegion.WithRegion regionName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="regionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="regionName">regionName リソースの領域の名前</param>
        <summary>
            リソースの地域の名前を指定します。
            </summary>
        <returns>リソース定義の次のステージ</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>