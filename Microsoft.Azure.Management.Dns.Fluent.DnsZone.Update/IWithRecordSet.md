<Type Name="IWithRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet">
  <TypeSignature Language="C#" Value="public interface IWithRecordSet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRecordSet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRecordSet" />
  <TypeSignature Language="F#" Value="type IWithRecordSet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            DNS ゾーンの更新を許可するレコード セットを指定するの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAaaaRecordSet (name As String) As IAaaaRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">AAAA レコード セットの名前です。</param>
        <summary>
            DNS ゾーンにアタッチされている設定 AAAA レコードの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>AAAA レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineARecordSet (name As String) As IARecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">A レコード セットの名前です。</param>
        <summary>
            A レコードが DNS ゾーンにアタッチされている設定の定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>A レコードの構成を表す、ステージを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineCNameRecordSet (name As String) As ICNameRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineMXRecordSet (name As String) As IMXRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">MX レコード セットの名前です。</param>
        <summary>
            MX レコードが DNS ゾーンにアタッチされているセットの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>MX レコードの構成を表す、ステージを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNSRecordSet (name As String) As INSRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">NS レコード セットの名前です。</param>
        <summary>
            DNS ゾーンにアタッチされている設定の NS レコードの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>段階 NS レコード セットの構成を表すです。</return>
      </Docs>
    </Member>
    <Member MemberName="DefinePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefinePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefinePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefinePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePtrRecordSet (name As String) As IPtrRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefinePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">PTR のレコード セットの名前です。</param>
        <summary>
            PTR レコードが DNS ゾーンにアタッチされているセットの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>PTR のレコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSrvRecordSet (name As String) As ISrvRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">SRV レコード セットの名前。</param>
        <summary>
            SRV レコードが DNS ゾーンにアタッチされているセットの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SRV レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefineTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineTxtRecordSet (name As String) As ITxtRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">TXT レコード セットの名前。</param>
        <summary>
            TXT レコードが DNS ゾーンにアタッチされているセットの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>TXT レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet UpdateAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet UpdateAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAaaaRecordSet (name As String) As IUpdateAaaaRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet" Usage="iWithRecordSet.UpdateAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">AAAA レコード セットの名前です。</param>
        <summary>
            この DNS ゾーン内の既存の AAAA レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>AAAA レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet UpdateARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet UpdateARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateARecordSet (name As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithRecordSet.UpdateARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">A レコード セットの名前です。</param>
        <summary>
            この DNS ゾーンのレコード セットを既存の更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>A レコードの構成を表す、ステージを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet UpdateCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet UpdateCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateCNameRecordSet (name As String) As IUpdateCNameRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet" Usage="iWithRecordSet.UpdateCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet UpdateMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet UpdateMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMXRecordSet (name As String) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithRecordSet.UpdateMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">MX レコード セットの名前です。</param>
        <summary>
            この DNS ゾーン内の既存の MX レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>MX レコードの構成を表す、ステージを設定します。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet UpdateNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet UpdateNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNSRecordSet (name As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithRecordSet.UpdateNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">NS レコード セットの名前です。</param>
        <summary>
            この DNS ゾーン内の既存の NS レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>段階 NS レコード セットの構成を表すです。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet UpdatePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet UpdatePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdatePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePtrRecordSet (name As String) As IUpdatePtrRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdatePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet" Usage="iWithRecordSet.UpdatePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">PTR のレコード セットの名前です。</param>
        <summary>
            この DNS ゾーン内の既存の PTR レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>PTR のレコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSoaRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord UpdateSoaRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord UpdateSoaRecord() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateSoaRecord" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSoaRecord () As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member UpdateSoaRecord : unit -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithRecordSet.UpdateSoaRecord " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            TXT レコード セットの構成を表す、ステージを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet UpdateSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet UpdateSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSrvRecordSet (name As String) As IUpdateSrvRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet" Usage="iWithRecordSet.UpdateSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">SRV レコード セットの名前。</param>
        <summary>
            この DNS ゾーン内の既存の SRV レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>SRV レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet UpdateTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet UpdateTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTxtRecordSet (name As String) As IUpdateTxtRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet" Usage="iWithRecordSet.UpdateTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">TXT レコード セットの名前。</param>
        <summary>
            この DNS ゾーン内の既存の TXT レコードの更新プログラムの説明を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>TXT レコード セットの構成を表す段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithCNameRecordSet (string name, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithCNameRecordSet(string name, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCNameRecordSet (name As String, alias As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithCNameRecordSet (name, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">CNAME のレコード セットの名前です。</param>
        <param name="alias">CNAME レコードのエイリアスです。</param>
        <summary>
            CNAME レコードが DNS ゾーンにアタッチされているセットの定義を指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーン定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAaaaRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">AAAA レコード セットの名前です。</param>
        <summary>
            AAAA レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutAaaaRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAaaaRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAaaaRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutAaaaRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutARecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">A レコード セットの名前です。</param>
        <summary>
            A レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutARecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutARecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutARecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutARecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCNameRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">CNAME のレコード セットの名前です。</param>
        <summary>
            CNAME レコードが DNS ゾーンで設定を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCNameRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutCNameRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMXRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">MX レコード セットの名前です。</param>
        <summary>
            MX レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutMXRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMXRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMXRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutMXRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNSRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">NS レコード セットの名前です。</param>
        <summary>
            NS レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutNSRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNSRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNSRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutNSRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutPtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutPtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPtrRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutPtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">PTR のレコード セットの名前です。</param>
        <summary>
            PTR レコードの DNS ゾーンで設定を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutPtrRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPtrRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPtrRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutPtrRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSrvRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">SRV レコード セットの名前です。</param>
        <summary>
            SRV レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutSrvRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSrvRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSrvRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutSrvRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTxtRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">TXT レコード セットの名前です。</param>
        <summary>
            TXT レコードが DNS ゾーンのセットを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>DNS ゾーンの更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutTxtRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTxtRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTxtRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutTxtRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>