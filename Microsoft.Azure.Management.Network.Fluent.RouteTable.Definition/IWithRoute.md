<Type Name="IWithRoute" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute">
  <TypeSignature Language="C#" Value="public interface IWithRoute" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoute" />
  <TypeSignature Language="F#" Value="type IWithRoute = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ルートを追加できるように、ルート テーブル定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.DefineRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRoute (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;" Usage="iWithRoute.DefineRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">ルートの名前。</param>
        <summary>
            ルート テーブルに追加する新しいルートの定義を開始します。
            定義は、Route.DefinitionStages.WithAttach.attach() への呼び出しで完了する必要があります。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute (string destinationAddressPrefix, Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute(string destinationAddressPrefix, class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRoute(System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoute (destinationAddressPrefix As String, nextHop As RouteNextHopType) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRoute : string * Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRoute (destinationAddressPrefix, nextHop)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="nextHop" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix">送信先アドレス プレフィックス、CIDR 表記法のルートに適用するので表されます。</param>
        <param name="nextHop">次のホップの種類。</param>
        <summary>
            非仮想アプライアンスのルートを作成します。
            名前が自動的に生成されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRouteViaVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance (string destinationAddressPrefix, string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance(string destinationAddressPrefix, string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRouteViaVirtualAppliance(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRouteViaVirtualAppliance (destinationAddressPrefix As String, ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRouteViaVirtualAppliance : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRouteViaVirtualAppliance (destinationAddressPrefix, ipAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix">送信先アドレス プレフィックス、CIDR 表記法のルートに適用するので表されます。</param>
        <param name="ipAddress">通過するトラフィックをルーティングする仮想アプライアンスの IP アドレス。</param>
        <summary>
            仮想アプライアンス経由でのルートを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>