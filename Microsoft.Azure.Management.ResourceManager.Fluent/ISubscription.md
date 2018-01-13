<Type Name="ISubscription" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription">
  <TypeSignature Language="C#" Value="public interface ISubscription : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubscription implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubscription&#xA;Implements IHasInner(Of SubscriptionInner), IIndexable" />
  <TypeSignature Language="F#" Value="type ISubscription = interface&#xA;    interface IIndexable&#xA;    interface IHasInner&lt;SubscriptionInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure サブスクリプションの変更できないクライアント側表現。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>人間の読み取りにサブスクリプションの名前</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLocationByRegion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.ILocation GetLocationByRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.ILocation GetLocationByRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.GetLocationByRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member GetLocationByRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.ILocation" Usage="iSubscription.GetLocationByRegion region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.ILocation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region">Azure のリージョン</param>
        <summary>
            選択されたサブスクリプションへのアクセス権がある場合は、指定した領域のデータ センターの場所を取得します。
            </summary>
        <returns>Azure データ センターの場所、または null の場合は、場所はこのサブスクリプションにアクセスできません。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ILocation&gt; ListLocations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.ILocation&gt; ListLocations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.ListLocations" />
      <MemberSignature Language="VB.NET" Value="Public Function ListLocations () As IEnumerable(Of ILocation)" />
      <MemberSignature Language="F#" Value="abstract member ListLocations : unit -&gt; seq&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ILocation&gt;" Usage="iSubscription.ListLocations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ILocation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サブスクリプションにアクセスする場所を一覧表示します。
            </summary>
        <returns>限定的な場所の一覧</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>サブスクリプションの状態。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>サブスクリプションの UUID</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionPolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionPolicies SubscriptionPolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionPolicies SubscriptionPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.SubscriptionPolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionPolicies As SubscriptionPolicies" />
      <MemberSignature Language="F#" Value="member this.SubscriptionPolicies : Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionPolicies" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ISubscription.SubscriptionPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.SubscriptionPolicies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>サブスクリプションで定義されたポリシー</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>