<Type Name="IWithTags" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags">
  <TypeSignature Language="C#" Value="public interface IWithTags" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTags" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTags" />
  <TypeSignature Language="F#" Value="type IWithTags = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            追加またはタグを更新できるように、仮想マシン拡張機能の更新プログラムの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTag (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTag : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithoutTag key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">削除するタグのキー。</param>
        <summary>
            仮想マシンの拡張機能からタグを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTag : string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">タグのキー。</param>
        <param name="value">タグの値です。</param>
        <summary>
            仮想マシンの拡張機能にタグを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IWithTags.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate" Usage="iWithTags.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags">タグを名前でインデックスを作成します。</param>
        <summary>
            仮想マシンの拡張機能用のタグを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>