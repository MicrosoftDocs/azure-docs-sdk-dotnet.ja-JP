<Type Name="ServiceEndpointsVersion" FullName="System.Fabric.ServiceEndpointsVersion">
  <TypeSignature Language="C#" Value="public sealed class ServiceEndpointsVersion" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceEndpointsVersion extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceEndpointsVersion" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceEndpointsVersion" />
  <TypeSignature Language="F#" Value="type ServiceEndpointsVersion = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>2 つの比較に使用<see cref="T:System.Fabric.ServiceNotification" />オブジェクトおよび通知イベントの前に、その他を決定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Compare">
      <MemberSignature Language="C#" Value="public int Compare (System.Fabric.ServiceEndpointsVersion other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 Compare(class System.Fabric.ServiceEndpointsVersion other) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceEndpointsVersion.Compare(System.Fabric.ServiceEndpointsVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function Compare (other As ServiceEndpointsVersion) As Integer" />
      <MemberSignature Language="F#" Value="member this.Compare : System.Fabric.ServiceEndpointsVersion -&gt; int" Usage="serviceEndpointsVersion.Compare other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Fabric.ServiceEndpointsVersion" />
      </Parameters>
      <Docs>
        <param name="other">
          <para>比較する他のバージョンです。</para>
        </param>
        <summary>
          <para>このバージョンのバージョンと比較<paramref name="other" />です。</para>
        </summary>
        <returns>
          <para>この場合は 0 と<paramref name="other" />は同等ですが、負の値を使用している場合、これより小さい<paramref name="other" />と正の値を使用しているこれよりも大きい場合<paramref name="other" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>